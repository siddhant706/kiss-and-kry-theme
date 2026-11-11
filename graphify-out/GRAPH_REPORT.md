# Graph Report - kiss-and-kry-theme  (2026-11-11)

## Corpus Check
- 162 files · ~243,297 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 412 file(s) not represented in the graph (top: .liquid 408, .css 3, (none) 1)

## Summary
- 1349 nodes · 2790 edges · 95 communities (34 shown, 61 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 25 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `7c1eb429`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- CartItemsComponent
- morph.js
- Slideshow
- standard-events.d.ts
- PaginatedList
- popover-polyfill.js
- ProductCard
- Component
- ProductFormComponent
- OverflowList
- utilities.js
- QuickOrderListComponent
- HeaderMenu
- standard-actions.d.ts
- LayeredSlideshowComponent
- LocalizationFormComponent
- ref_shopify_events
- PredictiveSearchComponent
- QuantitySelectorComponent
- DragZoomWrapper
- global.d.ts
- section-renderer.js
- Theme authoring guide
- ScrollHint
- slideshow.js
- DialogComponent
- GiftCardRecipientForm
- qr-code-generator.js
- ThemeDrawer
- DeferredMedia
- QuickAddComponent
- startViewTransition
- Scroller
- morph
- ProductHotspotComponent
- FacetsFormComponent
- product-card.js
- MarqueeComponent
- StickyAddToCartComponent
- AccordionCustom
- AnchoredPopoverComponent
- AnnouncementBar
- CollectionLinks
- ShopifyStandardEvent
- getClosestComponent
- DisclosuresSummaryFit
- PriceFacetComponent
- compilerOptions
- paginated-list.js
- component-cart-items.js
- CartDrawerComponent
- CartIcon
- theme-editor.js
- ComparisonSliderComponent
- MediaGallery
- PricePerItemComponent
- ShowMoreComponent
- facets.js
- FacetInputsComponent
- SortingFilterComponent
- FacetClearComponent
- FacetStatusComponent
- CartDiscount
- ThemePerformance
- view-event-elements.d.ts
- view-transitions.js
- VolumePricingInfoComponent
- FacetRemoveComponent
- ProductInventory
- ProductPrice
- ProductSkuComponent
- StandardStorefrontEventMap
- .connectedCallback
- ProductCustomProperty
- SearchPageInputComponent
- CartErrorEvent
- CartNoteUpdateEvent
- CartViewEvent
- CollectionUpdateEvent
- CollectionViewEvent
- ProductViewEvent
- SearchUpdateEvent
- Dynamic and static theme blocks
- package.json
- ViewEventElement
- local-pickup.js
- ProductRecommendations
- throttle

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

## Communities (95 total, 61 thin omitted)

### Community 1 - "morph.js"
Cohesion: 0.22
Nodes (18): attributesEqual(), collectHydrationTargets(), copyAttributes(), getNodeKey(), morphHydrationByKey(), PRESERVED_ATTRIBUTES, PRESERVED_ATTRIBUTES_SET, same() (+10 more)

### Community 3 - "standard-events.d.ts"
Cohesion: 0.05
Nodes (39): CartAjaxLine, CartAjaxResponse, CartDiscountUpdatePayloadDetail, CartDiscountUpdateResult, CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateEvent, CartLinesUpdatePayload (+31 more)

### Community 4 - "PaginatedList"
Cohesion: 0.07
Nodes (15): BlogPostsList, HeaderComponent, PaginatedListAspectRatioHelper, PaginatedList, ResultsList, getIntersectionRoot(), getScrollContainer(), getScrollEventTarget() (+7 more)

### Community 5 - "popover-polyfill.js"
Cohesion: 0.14
Nodes (30): apply(), checkPopoverValidity(), closeAllOpenPopovers(), closeAllOpenPopoversInList(), focusDelegate(), getPopoverVisibilityState(), getRootNode(), getStackPosition() (+22 more)

### Community 6 - "ProductCard"
Cohesion: 0.08
Nodes (4): ProductCard, ProductCardLink, isDesktopBreakpoint(), ProductComponent

### Community 7 - "Component"
Cohesion: 0.12
Nodes (7): Component, CopyToClipboardComponent, FlyToCart, QRCodeImage, RTEFormatter, VideoBackgroundComponent, VolumePricingComponent

### Community 9 - "OverflowList"
Cohesion: 0.10
Nodes (3): JumboText, OverflowList, OverflowMinimumEvent

### Community 10 - "utilities.js"
Cohesion: 0.12
Nodes (17): calculateHeaderGroupHeight(), changeMetaThemeColor(), isClickedOutside(), isMobileBreakpoint(), isPointWithinElement(), isTouchDevice(), mediaQueryLarge, onDocumentLoaded() (+9 more)

### Community 12 - "HeaderMenu"
Cohesion: 0.14
Nodes (4): MegaMenuHoverEvent, findMenuItem(), findSubmenu(), HeaderMenu

### Community 13 - "standard-actions.d.ts"
Cohesion: 0.07
Nodes (27): ActionArgs, ActionConfiguration, ActionFunction, CartCost, CartDiscountCode, CartLine, CartLineInput, CartMutationUserError (+19 more)

### Community 14 - "LayeredSlideshowComponent"
Cohesion: 0.14
Nodes (3): cycleFocus(), LayeredSlideshowComponent, getDirectionMultiplier()

### Community 15 - "LocalizationFormComponent"
Cohesion: 0.12
Nodes (4): DrawerLocalizationComponent, DropdownLocalizationComponent, LocalizationFormComponent, normalizeString()

### Community 16 - "ref_shopify_events"
Cohesion: 0.20
Nodes (4): MediaStartedPlayingEvent, QuantitySelectorUpdateEvent, ThemeEvents, ZoomMediaSelectedEvent

### Community 18 - "QuantitySelectorComponent"
Cohesion: 0.17
Nodes (3): CartQuantitySelectorComponent, QuantitySelectorComponent, parseIntOrDefault()

### Community 20 - "global.d.ts"
Cohesion: 0.09
Nodes (15): CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateResultDetail, LoadCallback, ModelViewer, NavigationActivation, NavigationHistoryEntry, Navigator (+7 more)

### Community 21 - "section-renderer.js"
Cohesion: 0.19
Nodes (10): hydrate(), hydrateSection(), buildSectionRenderingURL(), buildSectionSelector(), containsShadowRoot(), injectSectionStylesheet(), morphSection(), normalizeSectionId() (+2 more)

### Community 22 - "Theme authoring guide"
Cohesion: 0.12
Nodes (20): Accessibility, Color values and active context, JavaScript and the Component framework, CSS architecture, Merchant settings as public API, Module resolution, fetching, and execution, Performance, Schema ownership (+12 more)

### Community 24 - "slideshow.js"
Cohesion: 0.23
Nodes (6): SlideshowSelectEvent, center(), clamp(), closest(), getVisibleElements(), scheduler

### Community 25 - "DialogComponent"
Cohesion: 0.12
Nodes (6): DialogCloseEvent, DialogComponent, DialogOpenEvent, QuickAddDialog, getIOSVersion(), preventDefault()

### Community 27 - "qr-code-generator.js"
Cohesion: 0.13
Nodes (8): getTypeNumber(), getUTF8Length(), onMakeImage(), QRCode(), QRCodeModel(), QRErrorCorrectLevel, QRMaskPattern, QRMode

### Community 28 - "ThemeDrawer"
Cohesion: 0.07
Nodes (15): getFocusableElements(), removeTrapFocus(), trapFocus(), trapFocusHandlers, HeaderActions, HeaderDrawer, reset(), DrawerCloseEvent (+7 more)

### Community 31 - "startViewTransition"
Cohesion: 0.18
Nodes (9): scrollIntoView(), isLowPowerDevice(), onAnimationEnd(), prefersReducedMotion(), preloadImage(), startViewTransition(), supportsViewTransitions(), getMostVisibleElement() (+1 more)

### Community 32 - "Scroller"
Cohesion: 0.23
Nodes (3): calculatePaddingStart(), getScrollAxis(), Scroller

### Community 33 - "morph"
Cohesion: 0.19
Nodes (3): morph(), recreateAppBlockScripts(), VariantPicker

### Community 36 - "product-card.js"
Cohesion: 0.24
Nodes (5): MORPH_OPTIONS, SwatchesVariantPickerComponent, getViewParameterValue(), ResizeNotifier, yieldToMainThread()

### Community 43 - "ShopifyStandardEvent"
Cohesion: 0.15
Nodes (8): CartDiscountUpdateEvent, CartDiscountUpdatePayload, CartLinesUpdateEventImpl, PageViewEvent, PageViewPayload, ProductSelectEvent, ProductSelectPayload, ShopifyStandardEvent

### Community 44 - "getClosestComponent"
Cohesion: 0.11
Nodes (9): DeclarativeShadowElement, getAncestor(), getClosestComponent(), MissingRefError, parseData(), parseValue(), registerEventListeners(), ANIMATION_OPTIONS (+1 more)

### Community 47 - "compilerOptions"
Cohesion: 0.17
Nodes (11): compilerOptions, baseUrl, checkJs, noImplicitAny, noUncheckedIndexedAccess, paths, strictNullChecks, target (+3 more)

### Community 49 - "component-cart-items.js"
Cohesion: 0.27
Nodes (6): CartNote, cartPerformance, debounce(), fetchConfig(), normalizeVariantId(), resolveVariantId()

### Community 52 - "theme-editor.js"
Cohesion: 0.18
Nodes (5): carouselState, isIOS, layeredSlideshowState, matches(), slideshowState

### Community 57 - "facets.js"
Cohesion: 0.50
Nodes (6): convertMoneyToMinorUnits(), CURRENCY_DECIMALS, formatCents(), formatMoney(), getCurrencyDivisor(), getCurrencyPrecision()

### Community 64 - "view-event-elements.d.ts"
Cohesion: 0.33
Nodes (3): CollectionComponent, ProductComponent, Refs

### Community 65 - "view-transitions.js"
Cohesion: 0.53
Nodes (4): isLowPowerDevice(), prefersReducedMotion(), shouldDisableCrossDocumentViewTransitions(), shouldSkipViewTransition()

### Community 71 - "StandardStorefrontEventMap"
Cohesion: 0.50
Nodes (4): DocumentEventMap, ElementEventMap, StandardStorefrontEventMap, WindowEventMap

## Knowledge Gaps
- **11 isolated node(s):** `Accessibility`, `Color values and active context`, `Merchant settings as public API`, `Settings-driven styling`, `Theme map (layout, templates, sections, blocks, snippets, assets, config, locales)` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 388 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **61 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Component` connect `Component` to `morph.js`, `Slideshow`, `PaginatedList`, `ProductFormComponent`, `OverflowList`, `utilities.js`, `QuickOrderListComponent`, `HeaderMenu`, `LayeredSlideshowComponent`, `LocalizationFormComponent`, `ref_shopify_events`, `PredictiveSearchComponent`, `QuantitySelectorComponent`, `DragZoomWrapper`, `section-renderer.js`, `slideshow.js`, `DialogComponent`, `GiftCardRecipientForm`, `ThemeDrawer`, `DeferredMedia`, `QuickAddComponent`, `startViewTransition`, `morph`, `ProductHotspotComponent`, `FacetsFormComponent`, `product-card.js`, `MarqueeComponent`, `StickyAddToCartComponent`, `AnchoredPopoverComponent`, `AnnouncementBar`, `CollectionLinks`, `getClosestComponent`, `DisclosuresSummaryFit`, `PriceFacetComponent`, `paginated-list.js`, `component-cart-items.js`, `CartDrawerComponent`, `CartIcon`, `ComparisonSliderComponent`, `MediaGallery`, `PricePerItemComponent`, `ShowMoreComponent`, `facets.js`, `FacetInputsComponent`, `SortingFilterComponent`, `FacetClearComponent`, `FacetStatusComponent`, `CartDiscount`, `view-event-elements.d.ts`, `VolumePricingInfoComponent`, `FacetRemoveComponent`, `ProductInventory`, `ProductPrice`, `ProductSkuComponent`, `ProductCustomProperty`, `SearchPageInputComponent`, `local-pickup.js`, `ProductRecommendations`?**
  _High betweenness centrality (0.507) - this node is a cross-community bridge._
- **What connects `Accessibility`, `Color values and active context`, `Merchant settings as public API` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Slideshow` be split into smaller, more focused modules?**
  _Cohesion score 0.09359605911330049 - nodes in this community are weakly interconnected._
- **Why does `LayeredSlideshowComponent` connect `LayeredSlideshowComponent` to `utilities.js`, `Component`?**
  _High betweenness centrality (0.056) - this node is a cross-community bridge._
- **Should `standard-events.d.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._
- **Why does `Slideshow` connect `Slideshow` to `slideshow.js`, `.connectedCallback`, `.#handleMouseDown`, `Component`?**
  _High betweenness centrality (0.040) - this node is a cross-community bridge._
- **Should `PaginatedList` be split into smaller, more focused modules?**
  _Cohesion score 0.06666666666666667 - nodes in this community are weakly interconnected._