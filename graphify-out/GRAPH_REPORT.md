# Graph Report - kiss-and-kry-theme  (2026-10-21)

## Corpus Check
- 196 files · ~240,528 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 290 file(s) not represented in the graph (top: .liquid 286, .css 3, (none) 1)

## Summary
- 1347 nodes · 2784 edges · 91 communities (35 shown, 56 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 25 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Community 0
- Community 1
- Community 2
- Community 3
- Community 4
- Community 5
- Community 6
- Community 7
- Community 8
- Community 9
- Community 10
- Community 11
- Community 12
- Community 13
- Community 14
- Community 15
- Community 16
- Community 17
- Community 18
- Community 19
- Community 20
- Community 21
- Community 22
- Community 23
- Community 24
- Community 25
- Community 26
- Community 27
- Community 28
- Community 29
- Community 30
- Community 31
- Community 32
- Community 33
- Community 34
- Community 35
- Community 36
- Community 37
- Community 38
- Community 39
- Community 40
- Community 41
- Community 42
- Community 43
- Community 44
- Community 45
- Community 46
- Community 47
- Community 48
- Community 49
- Community 50
- Community 51
- Community 52
- Community 53
- Community 54
- Community 55
- Community 56
- Community 57
- Community 58
- Community 59
- Community 60
- Community 61
- Community 62
- Community 63
- Community 64
- Community 65
- Community 66
- Community 67
- Community 68
- Community 69
- Community 70
- Community 71
- Community 72
- Community 73
- Community 74
- Community 75
- Community 76
- Community 77
- Community 78
- Community 79
- Community 80
- Community 81
- Community 82
- Community 83
- Community 86

## God Nodes (most connected - your core abstractions)
1. `Component` - 127 edges
2. `Slideshow` - 41 edges
3. `QuickOrderListComponent` - 33 edges
4. `ProductCard` - 30 edges
5. `HeaderMenu` - 29 edges
6. `LayeredSlideshowComponent` - 29 edges
7. `morph()` - 27 edges
8. `ProductFormComponent` - 26 edges
9. `onAnimationEnd()` - 26 edges
10. `CartItemsComponent` - 23 edges

## Surprising Connections (you probably didn't know these)
- `CartNote` --inherits--> `Component`  [EXTRACTED]
  assets/cart-note.js → assets/component.js
- `AnchoredPopoverComponent` --inherits--> `Component`  [EXTRACTED]
  assets/anchored-popover.js → assets/component.js
- `AnnouncementBar` --inherits--> `Component`  [EXTRACTED]
  assets/announcement-bar.js → assets/component.js
- `BlogPostsList` --inherits--> `PaginatedList`  [EXTRACTED]
  assets/blog-posts-list.js → assets/paginated-list.js
- `CartDiscount` --inherits--> `Component`  [EXTRACTED]
  assets/cart-discount.js → assets/component.js

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Theme authoring contracts** — agents_settings_driven_styling, agents_css_architecture, agents_component_framework, agents_accessibility, agents_performance, agents_section_rendering_hydration [EXTRACTED 0.85]

## Communities (91 total, 56 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.07
Nodes (14): CartDiscount, CartItemsComponent, MORPH_OPTIONS, ProductRecommendations, hydrate(), hydrateSection(), buildSectionRenderingURL(), buildSectionSelector() (+6 more)

### Community 1 - "Community 1"
Cohesion: 0.08
Nodes (23): LocalPickup, attributesEqual(), collectHydrationTargets(), copyAttributes(), getNodeKey(), morph(), morphHydrationByKey(), PRESERVED_ATTRIBUTES (+15 more)

### Community 3 - "Community 3"
Cohesion: 0.05
Nodes (39): CartAjaxLine, CartAjaxResponse, CartDiscountUpdatePayloadDetail, CartDiscountUpdateResult, CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateEvent, CartLinesUpdatePayload (+31 more)

### Community 4 - "Community 4"
Cohesion: 0.11
Nodes (4): BlogPostsList, PaginatedListAspectRatioHelper, PaginatedList, ResultsList

### Community 5 - "Community 5"
Cohesion: 0.14
Nodes (30): apply(), checkPopoverValidity(), closeAllOpenPopovers(), closeAllOpenPopoversInList(), focusDelegate(), getPopoverVisibilityState(), getRootNode(), getStackPosition() (+22 more)

### Community 6 - "Community 6"
Cohesion: 0.09
Nodes (3): ProductCard, ProductCardLink, ProductComponent

### Community 7 - "Community 7"
Cohesion: 0.10
Nodes (8): Component, DeclarativeShadowElement, CopyToClipboardComponent, QRCodeImage, RTEFormatter, VideoBackgroundComponent, CollectionComponent, VolumePricingComponent

### Community 9 - "Community 9"
Cohesion: 0.10
Nodes (3): JumboText, OverflowList, OverflowMinimumEvent

### Community 10 - "Community 10"
Cohesion: 0.13
Nodes (19): calculateHeaderGroupHeight(), getIOSVersion(), getViewParameterValue(), isClickedOutside(), isDesktopBreakpoint(), isMobileBreakpoint(), isPointWithinElement(), isTouchDevice() (+11 more)

### Community 12 - "Community 12"
Cohesion: 0.15
Nodes (4): findMenuItem(), findSubmenu(), HeaderMenu, onDocumentLoaded()

### Community 13 - "Community 13"
Cohesion: 0.07
Nodes (27): ActionArgs, ActionConfiguration, ActionFunction, CartCost, CartDiscountCode, CartLine, CartLineInput, CartMutationUserError (+19 more)

### Community 15 - "Community 15"
Cohesion: 0.12
Nodes (4): DrawerLocalizationComponent, DropdownLocalizationComponent, LocalizationFormComponent, normalizeString()

### Community 16 - "Community 16"
Cohesion: 0.15
Nodes (6): CartSectionRestoredEvent, MediaStartedPlayingEvent, MegaMenuHoverEvent, QuantitySelectorUpdateEvent, ThemeEvents, ZoomMediaSelectedEvent

### Community 18 - "Community 18"
Cohesion: 0.17
Nodes (3): CartQuantitySelectorComponent, QuantitySelectorComponent, parseIntOrDefault()

### Community 20 - "Community 20"
Cohesion: 0.09
Nodes (15): CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateResultDetail, LoadCallback, ModelViewer, NavigationActivation, NavigationHistoryEntry, Navigator (+7 more)

### Community 21 - "Community 21"
Cohesion: 0.17
Nodes (11): HeaderComponent, getIntersectionRoot(), getScrollContainer(), getScrollEventTarget(), getScrollTop(), originalPushState, restoreSavedScrollTop(), saveScrollPosition() (+3 more)

### Community 22 - "Community 22"
Cohesion: 0.12
Nodes (20): Accessibility, Color values and active context, JavaScript and the Component framework, CSS architecture, Merchant settings as public API, Module resolution, fetching, and execution, Performance, Schema ownership (+12 more)

### Community 23 - "Community 23"
Cohesion: 0.16
Nodes (8): DialogCloseEvent, DialogOpenEvent, ANIMATION_OPTIONS, ScrollHint, scrollIntoView(), debounce(), isRTL(), prefersReducedMotion()

### Community 24 - "Community 24"
Cohesion: 0.17
Nodes (8): SlideshowSelectEvent, cycleFocus(), center(), clamp(), closest(), getDirectionMultiplier(), preventDefault(), scheduler

### Community 25 - "Community 25"
Cohesion: 0.13
Nodes (5): DialogComponent, QuickAddDialog, pruneDisconnectedScrollLockOwners(), syncScrollLock(), unlockScroll()

### Community 27 - "Community 27"
Cohesion: 0.13
Nodes (8): getTypeNumber(), getUTF8Length(), onMakeImage(), QRCode(), QRCodeModel(), QRErrorCorrectLevel, QRMaskPattern, QRMode

### Community 31 - "Community 31"
Cohesion: 0.20
Nodes (7): isLowPowerDevice(), preloadImage(), shouldDisableCrossDocumentViewTransitions(), startViewTransition(), supportsViewTransitions(), getMostVisibleElement(), ZoomDialog

### Community 32 - "Community 32"
Cohesion: 0.17
Nodes (4): calculatePaddingStart(), getScrollAxis(), Scroller, throttle()

### Community 33 - "Community 33"
Cohesion: 0.22
Nodes (3): HeaderDrawer, reset(), removeWillChangeOnAnimationEnd()

### Community 36 - "Community 36"
Cohesion: 0.29
Nodes (7): getFocusableElements(), removeTrapFocus(), trapFocus(), trapFocusHandlers, DrawerOpenEvent, lockScroll(), onAnimationEnd()

### Community 43 - "Community 43"
Cohesion: 0.15
Nodes (8): CartDiscountUpdateEvent, CartDiscountUpdatePayload, CartLinesUpdateEventImpl, PageViewEvent, PageViewPayload, ProductSelectEvent, ProductSelectPayload, ShopifyStandardEvent

### Community 44 - "Community 44"
Cohesion: 0.20
Nodes (6): getAncestor(), getClosestComponent(), MissingRefError, parseData(), parseValue(), registerEventListeners()

### Community 47 - "Community 47"
Cohesion: 0.17
Nodes (11): compilerOptions, baseUrl, checkJs, noImplicitAny, noUncheckedIndexedAccess, paths, strictNullChecks, target (+3 more)

### Community 48 - "Community 48"
Cohesion: 0.25
Nodes (3): FloatingPanelComponent, requestIdleCallback, viewTransition

### Community 49 - "Community 49"
Cohesion: 0.38
Nodes (5): CartNote, cartPerformance, fetchConfig(), normalizeVariantId(), resolveVariantId()

### Community 52 - "Community 52"
Cohesion: 0.18
Nodes (5): carouselState, isIOS, layeredSlideshowState, matches(), slideshowState

### Community 57 - "Community 57"
Cohesion: 0.50
Nodes (6): convertMoneyToMinorUnits(), CURRENCY_DECIMALS, formatCents(), formatMoney(), getCurrencyDivisor(), getCurrencyPrecision()

### Community 64 - "Community 64"
Cohesion: 0.33
Nodes (3): CollectionComponent, ProductComponent, Refs

### Community 65 - "Community 65"
Cohesion: 0.53
Nodes (4): isLowPowerDevice(), prefersReducedMotion(), shouldDisableCrossDocumentViewTransitions(), shouldSkipViewTransition()

### Community 71 - "Community 71"
Cohesion: 0.50
Nodes (4): DocumentEventMap, ElementEventMap, StandardStorefrontEventMap, WindowEventMap

## Knowledge Gaps
- **11 isolated node(s):** `Kiss & Kry working rules`, `Settings-driven styling`, `Theme map (layout, templates, sections, blocks, snippets, assets, config, locales)`, `Merchant settings as public API`, `Liquid composition` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 390 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **56 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Component` connect `Community 7` to `Community 0`, `Community 1`, `Community 2`, `Community 4`, `Community 8`, `Community 9`, `Community 10`, `Community 11`, `Community 12`, `Community 14`, `Community 15`, `Community 16`, `Community 17`, `Community 18`, `Community 19`, `Community 21`, `Community 23`, `Community 24`, `Community 25`, `Community 26`, `Community 28`, `Community 29`, `Community 30`, `Community 31`, `Community 33`, `Community 34`, `Community 35`, `Community 36`, `Community 37`, `Community 38`, `Community 40`, `Community 41`, `Community 42`, `Community 44`, `Community 45`, `Community 46`, `Community 48`, `Community 49`, `Community 50`, `Community 51`, `Community 53`, `Community 54`, `Community 55`, `Community 56`, `Community 57`, `Community 58`, `Community 59`, `Community 60`, `Community 61`, `Community 62`, `Community 64`, `Community 66`, `Community 67`, `Community 68`, `Community 69`, `Community 70`, `Community 72`, `Community 73`, `Community 74`?**
  _High betweenness centrality (0.502) - this node is a cross-community bridge._
- **What connects `Kiss & Kry working rules`, `Settings-driven styling`, `Theme map (layout, templates, sections, blocks, snippets, assets, config, locales)` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06896551724137931 - nodes in this community are weakly interconnected._
- **Why does `LayeredSlideshowComponent` connect `Community 14` to `Community 10`, `Community 7`?**
  _High betweenness centrality (0.056) - this node is a cross-community bridge._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.0821256038647343 - nodes in this community are weakly interconnected._
- **Why does `Slideshow` connect `Community 2` to `Community 24`, `Community 7`?**
  _High betweenness centrality (0.040) - this node is a cross-community bridge._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.07564102564102564 - nodes in this community are weakly interconnected._