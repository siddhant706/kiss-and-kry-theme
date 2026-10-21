## Kiss & Kry working rules (read first)
- Find involved files with `graphify query "<question>"`, then read those files fully. Don't scan the whole repo.
- Ignore minified assets, settings_data.json and other-language locale files. When adding text, edit only locales/en.default.json and en.default.schema.json.
- Smallest possible edit. No full-file rewrites or reformatting of untouched code.
- Put section CSS in the owning section's {% stylesheet %}. Use the theme's existing CSS variables and settings, never hardcoded colors or spacing.
- Homepage is JSON-driven: check templates/index.json for the section list, and keep section IDs stable.
- Visual targets: header, hero, content sections and footer share one container width and side padding. Mobile-first, breakpoints at 768px and 1024px.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

A Shopify Online Store 2.0 theme (Liquid + native ES modules, no build step). It was pulled from Shopify theme `193402863897` (see git history). There is no `package.json`, bundler, or test suite; `.gitignore` only excludes `.shopify/`.

**Read [AGENTS.md](AGENTS.md) first.** It is the authoritative theme authoring guide (settings-driven styling, CSS ownership, Component framework, accessibility, performance, section hydration). Do not duplicate it here; follow it.

## Commands

No scripts exist in the repo. Use the Shopify CLI against a development theme:

- `shopify theme dev` — local preview with hot reload
- `shopify theme check` — Theme Check lint (no `.theme-check.yml` is present, so defaults apply)
- `shopify theme pull` / `shopify theme push` — sync with the store (push/pull affect a live store; confirm before running)

## Architecture notes (beyond AGENTS.md)

- No `schemas/` directory exists, so the `{% schema %}` JSON embedded in each section/block `.liquid` file is the source of truth. Edit it directly. `config/settings_schema.json` is also edited directly.
- `assets/` is flat: JS modules, `base.css`, and `icon-*.svg` live together. `assets/global.d.ts` provides types for the JS.
- JS module wiring lives in `snippets/scripts.liquid`: an import map maps `@theme/*` specifiers (e.g. `@theme/component`, `@theme/section-renderer`) to asset URLs, and `@shopify/events` loads from the Shopify CDN. A new module imported via `@theme/*` needs an entry there, plus an executing module path on every page that renders its markup.
- `snippets/theme-styles-variables.liquid` defines the CSS custom properties (including `--opacity-*`); `snippets/color-palette.liquid` and `snippets/contrast-override.liquid` handle settings-backed and scoped colors.
- Shared CSS lives in "style-owner" snippets (e.g. `product-card-styles`, `add-to-cart-button-styles`) that consumers must `render` so subsetting includes their CSS; AGENTS.md lists the dependencies that must be preserved.
- Template JSON IDs must stay stable because saved merchant configuration depends on them. `templates/gift_card.liquid` is the only Liquid template.
- Runtime strings go in `locales/en.default.json`; schema labels go in `locales/en.default.schema.json` and are referenced by `t:` keys.

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- When graphify-out/graph.json exists, run `graphify query "<question>"` before your first grep, search or source-file read for a codebase question, and put this rule in every subagent prompt that explores code. Read raw files only for lines the graph or an earlier read already located. Use `graphify path "<A>" "<B>"` for relationships and `graphify explain "<concept>"` for focused concepts. These return a scoped subgraph, usually much smaller than GRAPH_REPORT.md or raw grep output.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- Read graphify-out/GRAPH_REPORT.md only for broad architecture review or when query/path/explain do not surface enough context.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).
- A committed graphify-out/graph.json is rewritten whole on every build, so a large diff to it in a pull request is expected. Do not flag it as churn or suggest skipping the graph rebuild or its hooks.
