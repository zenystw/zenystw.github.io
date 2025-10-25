# Commit History

Generated at: 2025-10-25 11:25:35 +08:00


## 2025-10-25
- refactor(components): enhance `Figure` with skeleton loader & remove poster prop
- refactor(scripts): migrate README generation from batch to TypeScript & automate via build hook

## 2025-10-24
- feat(config): add preconnect links for Google Fonts optimization
- feat(config): integrate `nuxt-vitalizer` & enable asset compression

## 2025-10-22
- refactor(i18n): normalize content structure & convert plural fields to singular
- refactor(scripts): relocate README generator to scripts dir & add dedicated build task
- refactor(scripts): move README generation to build step & update target directory
- feat(scripts): add automated README generation for deployment
- refactor(assets): optimize video poster images for improved performance

## 2025-10-21
- feat(config): set icon mode to SVG rendering
- refactor(theme): relocate theme files to app assets & update path resolution

## 2025-10-20
- refactor(components): improve UI consistency & transition handling
- refactor(components): remove `to-fade` transition classes from section headings
- feat(components): implement lazy poster loading with IntersectionObserver in `Figure`
- feat(config): disable SSR for client-side only rendering
- refactor(styles): optimize transitions & streamline menu animations
- refactor(assets): optimize video assets & add WebP posters for lazy loading
- refactor(composables): standardize client-side guard pattern with early returns
- feat(config): enable icon server bundle with specified collections
- refactor(composables): migrate transitions to theme-aware composable & optimize loading

## 2025-10-19
- feat(components): add conditional nav visibility with `show` property
- refactor(assets): convert avatar image from PNG to WebP format
- feat(seo): add sitemap generation with dynamic routes & update robots.txt
- feat(components): add poster support & improve video preloading in `Figure`
- refactor(components): improve header navigation & spacing consistency
- refactor(config): consolidate public assets under `static` directory for unified caching
- chore(deps): add `gh-pages` package & deploy script for GitHub Pages deployment
- refactor(composables): replace type assertion with runtime check in `useI18nArray`
- refactor(config): rename preload script & add cache headers for static assets
- refactor(theme): migrate theme CSS to public dir & simplify icon sizing
- refactor(icon): simplify icon configuration & remove collection scanning
- refactor(deps): remove @nuxt/image & migrate to native img with asset imports
- refactor(config): optimize prerendering & image handling configuration
- feat(components): add explicit dimensions to all portfolio media
- refactor(styles): increase container padding & round header height
- refactor(components): improve responsive layout & spacing consistency
- refactor(styles): expand container width & add consistent horizontal padding
- refactor(components): improve button variants & locale UI spacing
- refactor(styles): consolidate spacing logic with semantic CSS variables
- refactor(components): remove unused `mdIconClass` from `ThemeIcon`
- refactor(assets): relocate avatar to assets & replace Reka UI with `NuxtImg`
- refactor(components): enhance a11y with ARIA labels & radio group patterns

## 2025-10-18
- refactor(composables): make `currentLocale` writable in `useLocale`
- refactor(components): add `xs` icon size & improve icon alignment
- refactor(composables): consolidate theme switching logic & encapsulate mode transition
- feat(seo): add structured data, meta tags & i18n SEO content
- chore(lint): exclude JSON-LD properties from naming convention rules
- refactor(components): improve alt text fallback logic in `Figure` component

## 2025-10-17
- refactor(components): add alt text to images for accessibility
- refactor(components): replace lazy figures with eager loading & add autoplay control
- refactor(components): implement dynamic mode transition & remove static transition classes
- refactor(components): add `aria-hidden` to `BaseOverlay` for accessibility
- refactor(utils): optimize transition system & improve semantic HTML
- refactor(components): adjust spacing & simplify gallery heading layout
- refactor(components): redesign menu layout & add `menu-trigger` variant to `UiButton`
- refactor(components): simplify `ModeToggleButton` & add icon transition
- refactor(components): use `span` with block display for gallery heading slot
- refactor(components): remove `AppTitle` & inline avatar/contact info rendering
- refactor(components): rename component prop from `is` to `as`
- refactor(lint): adjust vue attribute order rule
- refactor(components): separate link & button components, remove `BaseButton`
- refactor(components): simplify `ThemeIcon` & add small icon size variant
- feat(i18n): add mode preference translation & clean language label

## 2025-10-16
- refactor(i18n): rename brand image terminology to brand visual image
- refactor(components): improve responsive layout & consolidate tag styles
- refactor(components): improve project block & bot demo responsive layouts
- refactor(components): enhance responsive layout & add directional border utilities
- refactor(styles): reduce container min-width & tighten FAB spacing
- feat(components): add accordion-based language selector to mobile menu
- feat(components): add mobile menu with sidebar navigation
- feat(components): add focus states to buttons & nav items for accessibility
- fix(components): add href to header title link for accessibility
- refactor(layout): change header to sticky positioning & fix scroll behavior
- feat(config): add Reka UI component prefix for namespace clarity
- refactor(i18n): shorten language preference labels for compact UI
- refactor(components): add `menu-item` button variant with selected state support
- refactor(components): optimize button transitions for better performance
- refactor(portfolio): restructure project data & move components to dedicated folder
- refactor(components): remove `AppPreference` & simplify navigation with native elements
- refactor(components): center sidebar content & remove unused transition
- refactor(components): replace container-based icon sizing with explicit size prop
- refactor(components): centralize header styling & standardize `at` prop usage
- refactor(i18n): consolidate locale switching logic & remove middleware
- feat(components): add animated arrow rotation for dropdown toggle states
- feat(styles): add responsive text utilities & enhance error page layout
- refactor(components): replace `LocaleSelect` with `LocaleDropdown` & simplify preference props
- refactor(styles): move disabled state styling to global scope

## 2025-10-15
- chore(config): disable Nuxt DevTools
- refactor(components): normalize Vue directive syntax & enhance component props system
- refactor(styles): standardize design tokens & optimize button/tag styling
- refactor(components): remove `BaseSection` & improve attrs inheritance in page sections
- feat(styles): add `close` icon to theme icon registry
- refactor(components): improve responsive layout & spacing in skills section
- refactor(i18n): adjust line break positioning in skill category labels
- feat(components): add `BaseSidebar` component for side panel layouts
- feat(components): add `BaseOverlay` component for modal backgrounds
- refactor(components): add directional nav layout & responsive header visibility
- feat(components): add menu button variant with theme-aware styling
- refactor(styles): add blur variable & fix scroll-padding calculation
- refactor(components): normalize spacing & increase container width for improved layout consistency
- refactor(components): simplify layout utilities & optimize responsive structure in `AboutMe`
- refactor(i18n): reorder personalities
- refactor(styles): replace mobile-first text scaling with proportional responsive system
- refactor(components): add bottombar support & fix z-index layering
- refactor(styles): split global CSS into modular architecture, rename responsive utilities & add safe area support

## 2025-10-14
- refactor(components): increase icon size & simplify conditional styling in `ThemeIcon`
- fix(layouts): add width constraints to prevent horizontal overflow in default layout
- refactor(i18n): restructure locale files by language & add a11y translations
- refactor(components): apply responsive text & replace opacity hover with color in `AppNav`
- refactor(components): apply responsive text utilities & split email styles in `ContactInfo`
- refactor(components): split `Avatar` styles by context & add responsive border
- refactor(components): improve alignment in `AppTitle` with responsive adjustments
- refactor(styles): enhance design tokens, add responsive utilities & optimize layout scaling
- refactor(styles): remove `check` icon & add `menu` icon in theme icon record
- refactor(styles): centralize design tokens & replace hardcoded values with token-based classes
- refactor(utils): simplify `setHtmlClass` conditional logic
- config(nuxt): disable SSR & remove prerender rules for client-side rendering
- feat(utils): add `fade` & `fade-up` transition system with scroll-triggered animations
- refactor(components): change `SkillBlock` root element from article to div

## 2025-10-13
- refactor(components): use relative spacing in `ProjectBlock` & ensure full-width figures
- refactor(styles): change main content margin from vertical to top-only & add bottom margin to index page
- feat(components): add motion design portfolio subsection with Planet X & Nineteen projects
- feat(components): add graphic design portfolio subsection with brand & holiday designs
- feat(components): add 3D modeling portfolio subsection with Syranya animation demo
- feat(components): add game development portfolio subsection with RS1 & Engie demos
- feat(components): add bot development portfolio subsection with LINE Bot demo
- feat(components): add frontend development portfolio subsection with project galleries
- refactor(utils): optimize `setHtmlClass` with conditional DOM operations
- refactor(components): flatten structure & distribute spacing control to consumers
- feat(components): add `PortfolioProjectGallery` for flexible image galleries
- feat(components): add `PortfolioProjectBlock` for structured project display
- feat(components): add `PortfolioProjectDescriptions` for tech stack display
- refactor(components): enhance heading weights & adjust spacing consistency
- feat(components): add `UiCode` component for inline code styling
- feat(components): add `UiFigure` component for images & videos with captions
- refactor(styles): extract icon styles to dedicated file & consolidate list/note markers
- refactor(data): add `instructions` content type & `continuations` label with `TechStacks` extraction
- feat(styles): add `.note` pseudo-element with warning icon & theme-aware styling
- refactor(components): rename button `link` variant to `external-link` & use relative offset
- refactor(i18n): update portfolio captions & simplify labels
- refactor(components): export `PortfolioSectionProps` interface for extensibility
- refactor(components): extract `PageSection` props to page level for flexibility
- feat(components): add `PortfolioSection` & implement portfolio structure
- refactor(config): restructure navs with nested schema & migrate all i18n references
- refactor(components): flatten app component structure & standardize naming
- refactor(components): normalize icon sizing & enhance theme-aware styles

## 2025-10-12
- refactor(constants): replace `exclamation` icon with semantic variants
- refactor(i18n): consolidate holiday greeting projects & fix caption key
- refactor(data): normalize project keys to camelCase & expand i18n captions
- refactor(components): use auto-import for `UiButton` & add link security attrs
- feat(style): add exclamation icon & update i18n caption text
- refactor(styles): add global address style & simplify contact layout logic
- refactor(components): enhance `UiTag` with intrinsic styles & relative units
- refactor(components): move icon positioning to usage context & update shadows
- refactor(components): rename `variant` to `custom` & remove `skipModeClass` option
- refactor(components): extract list rendering into reusable `UiList` component
- feat(assets): add 3D modeling & LINE bot video demos
- feat(i18n): expand portfolio captions & refactor project notes
- feat(assets): add portfolio project video demos
- feat(assets): add portfolio project images
- refactor(data): extract `Content` type from `Project` interface
- style(i18n): improve text spacing in portfolio headings & command names

## 2025-10-11
- refactor(styles): centralize vertical spacing with `my-main` utility
- refactor(components): improve spacing consistency & simplify utility classes
- refactor(components): reorganize & rename page components with updated references
- config(setup): add `image.dir` config for assets directory
- refactor(components): consolidate transitions & improve `Tag` spacing
- feat(components): add home button & enhance error page layout
- refactor(components): extract scale effects into dedicated `buttonClass`
- style(components): add `tracking-widest` to `Section` heading
- style(components): reduce drop shadow opacity in `SkillIcon` for `dd` context
- style(components): use bg opacity instead of `opacity` utility in `Tag` solid variant
- refactor(components): migrate `AppTitle` to use `BaseButton` with direct anchor element
- feat(components): add `LocaleSelect` component with theme-aware styling
- refactor(components): rename `minimized` to `isEqualSize` & use aspect ratio utilities
- feat(composables): add `useThemeProps()` & clean up `useThemeClass()`
- feat(styles): add `cursor-pointer` to `a` tags
- refactor(components): export `UiButtonProps` & simplify `Button` type system
- refactor(components): migrate `ModeToggleButton` to use `Button` variant prop
- refactor(components): clean up utility classes in `AppTitle` & `ContactInfo`
- refactor(components): add outlined variant to `Tag` component
- refactor(components): enhance `Button` API with variants & type safety
- refactor(styles): extract reusable styles & consolidate theme configs
- refactor(components): relocate `SkillIcon`, enhance drop-shadow & update WordPress icon
- feat(i18n): add portfolio goal field & update baowin entries
- refactor(components): standardize gap utilities & simplify layout classes
- refactor(components): merge nav components into single file

## 2025-10-10
- style(components): adjust spacing & icon sizing across layout
- refactor(composables): improve type safety & naming in i18n & theme utils
- refactor(pages): simplify error page & add theme styling
- feat(data): add ngrok & jQuery to skills list
- style(theme): add underline styling to non-header links
- refactor(styles): add word spacing utilities & refactor typography
- feat(config): add fallback locale to i18n browser detection
- style(components): add drop shadow to skill icons & adjust spacing
- refactor(components): remove heading wrappers & use native HTML elements
- refactor(components): centralize section heading & icon logic in `UiSection`
- feat(i18n): use locale-aware links in navigation & refine zh-TW translation
- refactor(components): extract skill icon logic into dedicated `SkillIcon` component
- refactor(data): rename portfolio category from `bot` to `botDevelopment`
- refactor(components): simplify description list markup in `AboutMe`
- refactor(data): replace portfolio boolean flags with `contents` array
- feat(i18n): add portfolio project translations with multi-file locale structure
- refactor(config): centralize navigation sections in app config
- chore(setup): add JSON schema validation for portfolio locale files
- feat(i18n): add portfolio section translations & tech stack labels

## 2025-10-09
- style(components): adjust spacing & icon alignment for better layout
- feat(components): implement `Skills` section with grid layout & skill blocks
- refactor(i18n): add line breaks to skill category titles for better text wrapping
- refactor(styles): consolidate heading & paragraph text wrapping styles
- feat(components): add section icons to `H2` headings with theme-aware styling
- refactor(components): replace icon component with list-image styling in `AboutMe` descriptions
- chore(setup): add Tailwind CSS custom directives for VSCode IntelliSense
- feat(data): add portfolio data structure with project metadata
- refactor(composables,middleware): simplify locale handling & rename `setLocale` to `setLocaleStorage`
- refactor(constants,config): convert `collections` to `getCollections()` function
- fix(data): correct feature filter for `frontendDevelopmentSkills`
- refactor(styles): remove `--height-header-2x` variable & adjust scroll padding
- refactor(components): reorganize heading hierarchy & add H3-H6 components
- fix(styles,components): correct `flex-end` utility & update `Preference` to use `flex-end-center`
- feat(data): add skills data structure with categories & icon mappings
- feat(i18n): add skills section with language & category labels
- style(components): reduce vertical margin in `PageContainer`
- style(components): reduce gap in `Section` component
- refactor(components): reorganize nav components into subdirectory & rename `Item` to   `NavItem`
- style(components): adjust gap & add `justify-between` to `AppTitle`
- style(components): use `size-fit` instead of `w-fit` in `H1`
- feat(components,i18n): implement `AboutMe` section with i18n content
- feat(components): add `Tag` component for personality tags
- feat(components): add `RatingStars` component for skill ratings
- feat(composables): add `useI18nArray` composable for i18n array handling
- refactor(components): rename `Title` to `AppTitle` & refine styles
- feat(constants,composables): add star rating icons & fallback logic to `useThemeIcon`
- feat(components,styles): add `H2` component & base heading/paragraph styles
- refactor(components,i18n): rename `SkillsAndExpertise` to `Skills` & update i18n keys
- style(components): refine `emailClass` alignment in `ContactInfo`
- config(nuxt): enable client-side icon scanning

## 2025-10-08
- feat(components): add context-based sizing to `ThemeIcon`
- style(components): add `size-fit` & `break-keep` classes to `H1`
- refactor(components): consolidate `ContactInfo` sub-components & use semantic HTML
- feat(styles): add `button` variant & `flex-center-end` utility
- refactor(components): rename `UiContainer` to `PageContainer` & remove `at` prop
- chore(scripts): add `nuxt prepare` to dev script
- feat(composables): add `currentLanguage` & `localeOptions` to `useLocale()`
- feat(constants): auto-generate icon collections from `themeIconRecord`
- chore(lint): exclude `acc` parameter from array naming enforcement
- refactor(components): move header button styles to `UiButton`
- style(components): adjust spacing, sizing & layout utilities
- refactor(components): move responsive classes to `HeaderBar` from children
- refactor(components): extract `UiSection` from `BaseSection` styling
- refactor(components): reorganize structure & rename `UiIcon` to `ThemeIcon`
- feat(components): add page sections & integrate into index page
- feat(components): add `BaseSection` layout component
- feat(components): add styled `H1` heading component
- style(components): adjust header font sizing & use outline email icon
- refactor(components): add `main` variant & update context-specific styles
- refactor(components): rename plural components to singular & add SSR guard
- feat(components): add `Preference` container & integrate into header
- feat(components): add `ModeToggleButton` for mode toggling
- refactor(components): flatten `HeaderBar` & add context-aware `Title`
- feat(styles): add `flex-stretch` utility & smooth scroll behavior
- refactor(components): add responsive nav visibility & restructure `NavItem`
- feat(components): add anchor support to `BaseButton` & `UiButton`
- refactor(components): make `at` prop optional in `BaseContainer`

## 2025-10-07
- fix(components): make `Names` locale checks reactive with `computed()`
- refactor(components): make `Email` context-aware & adjust opacity
- refactor(components): rename `ContactInfo` to `ContactInfos` & use semantic tag
- refactor(components): rename `AppNav` to `AppNavs` & adjust layout
- refactor(components): rename `HeaderTitle` to `HeaderTitleButton` & add active state
- feat(styles): add `flex-end` utility class
- refactor(components): add `UiIcon` wrapper & integrate into `Email`
- refactor(utils): extract `scrollToTop()` to reusable utility
- refactor(components): extract `UiButton` wrapper from `BaseButton`
- feat(composables): add `skipModeClass` option to `useThemeClass()`
- refactor(components): rename `Container` to `UiContainer`
- feat(constants): add dark & light mode icons to `themeIconRecord`
- feat(components): add `AppNav` & integrate into header
- refactor(components): make `Email` clickable & adjust styling
- feat(components): add `HeaderTitle` with scroll-to-top functionality
- feat(components): add `AppContactInfo` & sub-components for contact display
- feat(composables): add `useThemeIcon` for theme-based icon selection
- feat(constants): add icon constants with theme-based email icons
- feat(config): add name fields to `contactInfos`
- feat(components): add `AppAvatar` component & avatar image
- feat(pages): add error page with homepage link
- feat(i18n): add common & navigation translations
- feat(styles): add flex utilities with `items-start` alignment
- refactor(components): move `HeaderBar` to `header/Bar` & update import
- refactor(components): adjust container layout & spacing
- refactor(composables): support array values in `useThemeClass`
- refactor(styles): simplify `header` variant selector
- feat(config): add `contactInfos` section with email
- feat(components): add `BaseButton` component
- feat(styles): add `on-header` variant & update `disabled` variant
- style(theme): adjust transition speed & container width
- feat(config): enable routing & add i18n `baseUrl` config
- feat(pages): add index page with `Container`
- feat(layouts): add default layout with `HeaderBar`
- feat(components): add `BaseBar` & `HeaderBar` components
- feat(components): add `BaseContainer` & `Container` components
- feat(styles): add `flex-around` & `flex-evenly` utilities
- chore(lint): disable `vue/multi-word-component-names` rule
- fix(composables): correct `currentLocale` type & return value in `useLocale`

## 2025-10-06
- fix(styles): adjust `--height-main` to account for doubled header height
- feat(composables): add `useThemeClass` for theme & mode-aware CSS classes
- feat(styles): add `flex-start` & `flex-start-center` utilities
- feat(utils): add `tw` utility for Tailwind class string handling
- feat(plugin): add global theme plugin for preference initialization
- feat(plugin): add global mode plugin for preference initialization
- feat(middleware): add global locale middleware for URL-based locale detection
- add `useTheme` for dynamic theme switching & persistence
- feat(composables): add `useMode` for dark/light mode management
- feat(composables): add `useLocale` for locale management & persistence
- feat(utils): add `switchTheme` for dynamic theme stylesheet loading
- feat(utils): add `isType` generic type guard utility
- feat(scripts): add preload class script for FOUC prevention
- chore(config): add TypeScript config for scripts directory
- feat(composables): add `usePreference` for locale, mode & theme detection
- feat(composables): add `useAppStorage` for reactive localStorage access
- chore(lint): allow leading underscore for function names
- feat(composables): add `useAppCookie` with `StorageKey` type definition
- refactor(constants): extract locale constants & configure i18n defaults
- feat(utils): add `setHtmlClass` helper for managing root element classes
- feat(config): add app config with defaults for locale, mode & theme
- chore(deps): remove pinia
- chore(config): configure Nitro for GitHub Pages deployment
- fix(styles): correct utility class definitions in global.css
- chore(deps): remove pinia-plugin-persistedstate

## 2025-10-05
- chore(deps): add vue-tsc for type checking
- feat(constants): add app & iconify constants, refactor i18n config
- chore(lint): allow leading underscore for array variables
- feat(assets): update favicon
- feat(theme): add minimal & breathe themes

## 2025-10-03
- init(setup): setup nuxt 4 portfolio with i18n & tailwind
