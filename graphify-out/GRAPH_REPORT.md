# Graph Report - kiss-and-kry-theme  (2026-11-03)

## Corpus Check
- 162 files · ~242,482 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 502 file(s) not represented in the graph (top: .liquid 498, .css 3, (none) 1)

## Summary
- 1347 nodes · 2783 edges · 91 communities (35 shown, 56 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 25 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `d8b1196d`
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
- scroll-container.js
- Theme authoring guide
- dialog.js
- slideshow.js
- DialogComponent
- GiftCardRecipientForm
- qr-code-generator.js
- ThemeDrawer
- DeferredMedia
- QuickAddComponent
- startViewTransition
- Scroller
- HeaderDrawer
- ProductHotspotComponent
- FacetsFormComponent
- onAnimationEnd
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
- header-actions.js
- ThemePerformance
- view-event-elements.d.ts
- view-transitions.js
- VolumePricingInfoComponent
- FacetRemoveComponent
- ProductInventory
- ProductPrice
- ProductSkuComponent
- StandardStorefrontEventMap
- FlyToCart
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

### Community 0 - "CartItemsComponent"
Cohesion: 0.07
Nodes (14): CartDiscount, CartItemsComponent, MORPH_OPTIONS, ProductRecommendations, hydrate(), hydrateSection(), buildSectionRenderingURL(), buildSectionSelector() (+6 more)

### Community 1 - "morph.js"
Cohesion: 0.08
Nodes (23): LocalPickup, attributesEqual(), collectHydrationTargets(), copyAttributes(), getNodeKey(), morph(), morphHydrationByKey(), PRESERVED_ATTRIBUTES (+15 more)

### Community 3 - "standard-events.d.ts"
Cohesion: 0.05
Nodes (39): CartAjaxLine, CartAjaxResponse, CartDiscountUpdatePayloadDetail, CartDiscountUpdateResult, CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateEvent, CartLinesUpdatePayload (+31 more)

### Community 4 - "PaginatedList"
Cohesion: 0.11
Nodes (4): BlogPostsList, PaginatedListAspectRatioHelper, PaginatedList, ResultsList

### Community 5 - "popover-polyfill.js"
Cohesion: 0.14
Nodes (30): apply(), checkPopoverValidity(), closeAllOpenPopovers(), closeAllOpenPopoversInList(), focusDelegate(), getPopoverVisibilityState(), getRootNode(), getStackPosition() (+22 more)

### Community 6 - "ProductCard"
Cohesion: 0.09
Nodes (3): ProductCard, ProductCardLink, ProductComponent

### Community 7 - "Component"
Cohesion: 0.10
Nodes (8): Component, DeclarativeShadowElement, CopyToClipboardComponent, QRCodeImage, RTEFormatter, VideoBackgroundComponent, CollectionComponent, VolumePricingComponent

### Community 9 - "OverflowList"
Cohesion: 0.10
Nodes (3): JumboText, OverflowList, OverflowMinimumEvent

### Community 10 - "utilities.js"
Cohesion: 0.13
Nodes (19): calculateHeaderGroupHeight(), getIOSVersion(), getViewParameterValue(), isClickedOutside(), isDesktopBreakpoint(), isMobileBreakpoint(), isPointWithinElement(), isTouchDevice() (+11 more)

### Community 12 - "HeaderMenu"
Cohesion: 0.15
Nodes (4): findMenuItem(), findSubmenu(), HeaderMenu, onDocumentLoaded()

### Community 13 - "standard-actions.d.ts"
Cohesion: 0.07
Nodes (27): ActionArgs, ActionConfiguration, ActionFunction, CartCost, CartDiscountCode, CartLine, CartLineInput, CartMutationUserError (+19 more)

### Community 15 - "LocalizationFormComponent"
Cohesion: 0.12
Nodes (4): DrawerLocalizationComponent, DropdownLocalizationComponent, LocalizationFormComponent, normalizeString()

### Community 16 - "ref_shopify_events"
Cohesion: 0.15
Nodes (6): CartSectionRestoredEvent, MediaStartedPlayingEvent, MegaMenuHoverEvent, QuantitySelectorUpdateEvent, ThemeEvents, ZoomMediaSelectedEvent

### Community 18 - "QuantitySelectorComponent"
Cohesion: 0.17
Nodes (3): CartQuantitySelectorComponent, QuantitySelectorComponent, parseIntOrDefault()

### Community 20 - "global.d.ts"
Cohesion: 0.09
Nodes (15): CartDiscountUpdateResultDetail, CartErrorPayloadDetail, CartLinesUpdateResultDetail, LoadCallback, ModelViewer, NavigationActivation, NavigationHistoryEntry, Navigator (+7 more)

### Community 21 - "scroll-container.js"
Cohesion: 0.17
Nodes (11): HeaderComponent, getIntersectionRoot(), getScrollContainer(), getScrollEventTarget(), getScrollTop(), originalPushState, restoreSavedScrollTop(), saveScrollPosition() (+3 more)

### Community 22 - "Theme authoring guide"
Cohesion: 0.12
Nodes (20): Accessibility, Color values and active context, JavaScript and the Component framework, CSS architecture, Merchant settings as public API, Module resolution, fetching, and execution, Performance, Schema ownership (+12 more)

### Community 23 - "dialog.js"
Cohesion: 0.16
Nodes (8): DialogCloseEvent, DialogOpenEvent, ANIMATION_OPTIONS, ScrollHint, scrollIntoView(), debounce(), isRTL(), prefersReducedMotion()

### Community 24 - "slideshow.js"
Cohesion: 0.17
Nodes (8): SlideshowSelectEvent, cycleFocus(), center(), clamp(), closest(), getDirectionMultiplier(), preventDefault(), scheduler

### Community 25 - "DialogComponent"
Cohesion: 0.13
Nodes (5): DialogComponent, QuickAddDialog, pruneDisconnectedScrollLockOwners(), syncScrollLock(), unlockScroll()

### Community 27 - "qr-code-generator.js"
Cohesion: 0.13
Nodes (8): getTypeNumber(), getUTF8Length(), onMakeImage(), QRCode(), QRCodeModel(), QRErrorCorrectLevel, QRMaskPattern, QRMode

### Community 31 - "startViewTransition"
Cohesion: 0.20
Nodes (7): isLowPowerDevice(), preloadImage(), shouldDisableCrossDocumentViewTransitions(), startViewTransition(), supportsViewTransitions(), getMostVisibleElement(), ZoomDialog

### Community 32 - "Scroller"
Cohesion: 0.17
Nodes (4): calculatePaddingStart(), getScrollAxis(), Scroller, throttle()

### Community 33 - "HeaderDrawer"
Cohesion: 0.22
Nodes (3): HeaderDrawer, reset(), removeWillChangeOnAnimationEnd()

### Community 36 - "onAnimationEnd"
Cohesion: 0.29
Nodes (7): getFocusableElements(), removeTrapFocus(), trapFocus(), trapFocusHandlers, DrawerOpenEvent, lockScroll(), onAnimationEnd()

### Community 43 - "ShopifyStandardEvent"
Cohesion: 0.15
Nodes (8): CartDiscountUpdateEvent, CartDiscountUpdatePayload, CartLinesUpdateEventImpl, PageViewEvent, PageViewPayload, ProductSelectEvent, ProductSelectPayload, ShopifyStandardEvent

### Community 44 - "getClosestComponent"
Cohesion: 0.20
Nodes (6): getAncestor(), getClosestComponent(), MissingRefError, parseData(), parseValue(), registerEventListeners()

### Community 47 - "compilerOptions"
Cohesion: 0.17
Nodes (11): compilerOptions, baseUrl, checkJs, noImplicitAny, noUncheckedIndexedAccess, paths, strictNullChecks, target (+3 more)

### Community 48 - "paginated-list.js"
Cohesion: 0.25
Nodes (3): FloatingPanelComponent, requestIdleCallback, viewTransition

### Community 49 - "component-cart-items.js"
Cohesion: 0.38
Nodes (5): CartNote, cartPerformance, fetchConfig(), normalizeVariantId(), resolveVariantId()

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
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 390 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **56 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Component` connect `Component` to `CartItemsComponent`, `morph.js`, `Slideshow`, `PaginatedList`, `ProductFormComponent`, `OverflowList`, `utilities.js`, `QuickOrderListComponent`, `HeaderMenu`, `LayeredSlideshowComponent`, `LocalizationFormComponent`, `ref_shopify_events`, `PredictiveSearchComponent`, `QuantitySelectorComponent`, `DragZoomWrapper`, `scroll-container.js`, `dialog.js`, `slideshow.js`, `DialogComponent`, `GiftCardRecipientForm`, `ThemeDrawer`, `DeferredMedia`, `QuickAddComponent`, `startViewTransition`, `HeaderDrawer`, `ProductHotspotComponent`, `FacetsFormComponent`, `onAnimationEnd`, `MarqueeComponent`, `StickyAddToCartComponent`, `AnchoredPopoverComponent`, `AnnouncementBar`, `CollectionLinks`, `getClosestComponent`, `DisclosuresSummaryFit`, `PriceFacetComponent`, `paginated-list.js`, `component-cart-items.js`, `CartDrawerComponent`, `CartIcon`, `ComparisonSliderComponent`, `MediaGallery`, `PricePerItemComponent`, `ShowMoreComponent`, `facets.js`, `FacetInputsComponent`, `SortingFilterComponent`, `FacetClearComponent`, `FacetStatusComponent`, `header-actions.js`, `view-event-elements.d.ts`, `VolumePricingInfoComponent`, `FacetRemoveComponent`, `ProductInventory`, `ProductPrice`, `ProductSkuComponent`, `FlyToCart`, `ProductCustomProperty`, `SearchPageInputComponent`?**
  _High betweenness centrality (0.502) - this node is a cross-community bridge._
- **What connects `Accessibility`, `Color values and active context`, `Merchant settings as public API` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `CartItemsComponent` be split into smaller, more focused modules?**
  _Cohesion score 0.06896551724137931 - nodes in this community are weakly interconnected._
- **Why does `LayeredSlideshowComponent` connect `LayeredSlideshowComponent` to `utilities.js`, `Component`?**
  _High betweenness centrality (0.056) - this node is a cross-community bridge._
- **Should `morph.js` be split into smaller, more focused modules?**
  _Cohesion score 0.0821256038647343 - nodes in this community are weakly interconnected._
- **Why does `Slideshow` connect `Slideshow` to `slideshow.js`, `Component`?**
  _High betweenness centrality (0.040) - this node is a cross-community bridge._
- **Should `Slideshow` be split into smaller, more focused modules?**
  _Cohesion score 0.07564102564102564 - nodes in this community are weakly interconnected._