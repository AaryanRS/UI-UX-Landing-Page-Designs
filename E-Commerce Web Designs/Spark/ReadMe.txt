# Project Brief: SPARK⚡ Store

## Executive Summary
A high-converting, premium multi-product e-commerce storefront crafted in a strict Neo-Brutalist aesthetic with high-voltage industrial utility accents. The design reimagines the physical, tactile energy of utility-grade hardware, electro-mechanical prototypes, and curated design editions for modern retail under the **SPARK⚡** brand identity.

---

## 1. Visual & Aesthetic Architecture

### Palette
- **Primary Yellow:** `#ffe17c` — Hero backgrounds, badge accents, high-priority CTAs, interactive highlights, and high-voltage tags.
- **Primary Dark (Charcoal):** `#171e19` — Structural marquees, editorial promo containers, dark mode tiles, footer base, and inverted SPARK⚡ brand badge.
- **Accent Sage:** `#b7c6c2` — Category cards, customer review backgrounds, secondary metadata surfaces.
- **UI White:** `#ffffff` — Primary product card surfaces, modal dialogs, input fields.
- **Border & Shadow Black:** `#000000` — Universal border strokes, zero-blur hard offset shadows.
- **Exception Accent (Stars & Indicators):** `#ffbc2e` — Star ratings and pulsing high-voltage indicators.

### Strict Negative Constraints
- **NO Gradients:** Every surface is a solid, unblended pigment.
- **NO Soft/Diffuse Shadows:** All shadows utilize `0px` blur radius.
- **NO Glassmorphism:** All backdrops and cards are 100% opaque.
- **NO Thin 1px UI Borders:** All borders strictly measure `2px solid #000000`.

---

## 2. Brand Identity & Motifs: SPARK⚡

- **Primary Logo:** Inverted charcoal badge (`#171e19`) with high-voltage yellow (`#ffe17c`) bold geometric letterforms: `SPARK⚡` with a `2px 2px 0px #000000` offset shadow.
- **High-Voltage Tactical Badges:** `[ PROTOCOL: HIGH-VOLTAGE SPARK ⚡ // LIVE ]` status pills and rotated tactical badges (`⚡ HIGH-VOLTAGE UTILITY`).
- **Headings & Accents:** `Cabinet Grotesk` (Weights: 700 Bold, 800 ExtraBold).
  - Signature Motif: `-webkit-text-stroke: 2px #000000; color: transparent;` applied to headline keywords.
- **Body & Metadata:** `Satoshi` (Weight: 500 Medium, 600 SemiBold).
- **Technical & Monospace Accents:** `Space Grotesk` / Monospace brackets: high-density bracketed specs, e.g. `[ INDEX 01 ]`, `[ MATRIX SELECT ]`, serialized batch numbers.

---

## 3. Physical & Tactile Interaction System

- **Universal Hard Box Shadows:**
  - Standard cards & buttons: `4px 4px 0px 0px #000000`
  - Featured & large modules: `8px 8px 0px 0px #000000`
  - Hero & focal components: `12px 12px 0px 0px #000000`
- **Button "Press-In" Physics:**
  - `default`: `transform: translate(0, 0); box-shadow: 4px 4px 0px #000;`
  - `hover`: `transform: translate(2px, 2px); box-shadow: 2px 2px 0px #000;`
  - `active`: `transform: translate(4px, 4px); box-shadow: 0px 0px 0px #000;`
  - Easing: `cubic-bezier(0.175, 0.885, 0.32, 1.275)`

---

## 4. Architectural Sections
1. **Header Navigation:** 80px fixed bar in `#ffe17c` with inverted `SPARK⚡` logo badge, central links (`SHOP`, `COLLECTIONS`, `NEW`, `BESTSELLERS`, `ABOUT`), and live cart (`[3]`) and wishlist badge counters.
2. **Hero Stage:** `#ffe17c` with a 32×32px radial dot matrix, oversized `Cabinet Grotesk` typography ("GOOD PRODUCTS. LOUDER DESIGN."), high-voltage status pill, and asymmetrical multi-product editorial collage.
3. **Continuous Marquee:** Charcoal ticker streaming `SPARK⚡ ARTIFACTS`, curated partner brands, and `⚡ HIGH-VOLTAGE UTILITY`.
4. **Category Explorer:** Bento grid showcasing 5 distinct product realms (`Tech & Controls`, `Monolith Objects`, `Habitat & Light`, `Tactile EDC`, `Workshop Textiles & Armor`).
5. **Featured Hardware Grid:** Asymmetric 6-product layout featuring ratings, dual-tier pricing, and responsive physical Quick Add buttons.
6. **Campaign Drop:** Charcoal focal container breaking out of standard grid alignment (`The Drafting Monolith, $340`).
7. **Active Registry Catalog:** 10-item browsing gallery equipped with category filter pills (`ALL`, `NEW`, `POPULAR`, `SALE`) and sorting toggles.
8. **High-Velocity Artifacts Leaderboard:** 4-tier leaderboard highlighting the #1 ranked `Tactile Cherry Switch Totem` in vibrant yellow.
9. **Editorial Manifesto:** Dual-column statement on zero-plastic manufacturing with industrial workshop lathe photography.
10. **Shop by Archetype:** 3 distinct persona calibration tiles (`The Minimalist`, `The Collector`, `The Everyday Icon`).
11. **Field Evaluations:** Sage backdrop holding asymmetric customer testimonial cards with `#ffbc2e` star ratings.
12. **Dispatch Terminal:** Newsletter signup with bold technical monospace inputs and authorization CTA.
13. **Footer Chrome:** 4-column directory under `SPARK⚡` branding, high-voltage kinetic design manifesto, and reactive hover-inverting social blocks (`© 2025 SPARK CORP. ALL SPECIFICATIONS RESERVED.`).

---
name: Neo-Brutalist Retail Matrix
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4c4637'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#7d7765'
  outline-variant: '#cfc6b2'
  surface-tint: '#715c00'
  primary: '#715c00'
  on-primary: '#ffffff'
  primary-container: '#ffe17c'
  on-primary-container: '#786303'
  inverse-primary: '#e1c563'
  secondary: '#59605a'
  on-secondary: '#ffffff'
  secondary-container: '#dde5dc'
  on-secondary-container: '#5f6660'
  tertiary: '#53615e'
  on-tertiary: '#ffffff'
  tertiary-container: '#d7e6e2'
  on-tertiary-container: '#596764'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe17c'
  primary-fixed-dim: '#e1c563'
  on-primary-fixed: '#231b00'
  on-primary-fixed-variant: '#554500'
  secondary-fixed: '#dde5dc'
  secondary-fixed-dim: '#c1c8c0'
  on-secondary-fixed: '#161d18'
  on-secondary-fixed-variant: '#414943'
  tertiary-fixed: '#d7e6e2'
  tertiary-fixed-dim: '#bbcac6'
  on-tertiary-fixed: '#111e1c'
  on-tertiary-fixed-variant: '#3c4a47'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  title-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: DM Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: DM Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers an unfiltered, high-velocity commerce experience built on the tenets of Neo-Brutalism paired with tactile physical feedback. It discards modern UI homogenization—eschewing soft gradients, subtle blurs, and illusory depth—in favor of structural honesty, graphic impact, and unambiguous boundaries.

### Brand Personality & Emotional Impact
- **Graphic & Decisive:** Every interaction delivers immediate visual certainty through structural 2px black boundaries and zero-blur offset geometry.
- **Physical & Kinetic:** Components behave like mechanical switchgear. Interactive states visibly compress into the page, providing physical satisfaction in a digital catalog.
- **Utilitarian Confidence:** High contrast, deliberate density, and unvarnished architectural layout prioritize immediate product evaluation and rapid conversion.

### Style Archetype
- **Neo-Brutalist / Tactile Kinetic:** Heavy structural ink borders (`#000000`), saturated primary yellow contrast, muted industrial sage accents, and mechanical hard-drop offset shadows. Depth is dimensional and physical, never atmospheric.

## Colors

The palette relies on absolute contrast and high-saturation focal points grounded by deep carbon and structural black outlines. 

### Palette Application Rules
- **Primary Yellow (`#ffe17c`):** High-priority operational triggers: main Add to Cart CTAs, active filter pills, promotional badges, and cart count indicators. Never used for large passive backgrounds.
- **Primary Dark (`#171e19`):** Deep carbon utilized for high-impact inverted sections (such as site footers or high-tier editorial modules), primary text, and high-emphasis tags.
- **Accent Sage (`#b7c6c2`):** Industrial neutral accent used for secondary metadata badges, secondary container fills, category headers, and muted table headers.
- **UI White (`#ffffff`):** Base canvas background and product card surfaces to allow commercial photography to read cleanly without color contamination.
- **Structural Black (`#000000`):** Mandatory 2px ink lines across all interactive borders, dividers, typography outlines, and directional drop shadows.

```
Canvas:            #ffffff
Borders & Shadows: #000000
Hero/CTA Accent:   #ffe17c
Dark Surfaces:     #171e19
Secondary Support: #b7c6c2
```

## Typography

The typographic hierarchy pairs high-impact geometric grotesque headings with a clean, low-contrast neutral grotesque for high-density product data and commerce copy.

- **Headlines & Display:** Space Grotesk. Rendered tight, punchy, and confident. Headings at `display` and `headline-lg` levels use heavy weights with slightly negative tracking to emulate vintage industrial signage and bold print editorial.
- **Body & Commerce Copy:** DM Sans. Delivers neutral, highly legible legibility across variable product specifications, descriptions, prices, and shipping disclosures.
- **Labels, Badges & Microcopy:** Space Grotesk in uppercase with deliberate positive letter-spacing (`+0.04em` to `+0.08em`) to enforce structural, technical clarity on buttons, metadata pills, and SKU identifiers.

## Layout & Spacing

The layout is engineered around an architectural grid with visible framing demarcations. Grid cells maintain strict mathematical borders; adjacent cards often touch or sit within a dense 12-column layout.

### Layout Matrix
- **Desktop (12 Columns):** 1440px max viewport width, `2rem` outer canvas margin, `1.5rem` gutters. Product grids feature 3-column or 4-column structures with uniform 2px border divisions.
- **Tablet (8 Columns):** Fluid layout down to 768px, `1.5rem` margins, `1rem` gutters. Product listings drop to 2-column arrays.
- **Mobile (4 Columns):** Fluid layout down to 360px, `1rem` outer canvas margins, `1rem` gutters. Single or alternating compact 2-column cards.

### Spacing Scale Rhythm
- Use `space-xs` (4px) and `space-sm` (8px) for internal micro-gaps (e.g., button icons, rating badges).
- Use `space-md` (16px) for interior component padding (inputs, card bodies, chip clusters).
- Use `space-lg` (24px) and `space-xl` (40px) for separating major functional commerce modules and grid blocks.

## Elevation & Depth

This system outright rejects blur-based, diffuse elevation models. Depth is hard-edged, physical, and cartesian, simulated via black directional drops.

### Offset Shadow Hierarchy
All drop shadows have `0px` blur radius and use absolute black (`#000000`).

- **Base Interactive Tier (`shadow-sm`):** `4px 4px 0px #000000`. Used for standard buttons, inputs, pills, and interactive cards in their resting state.
- **Prominent Module Tier (`shadow-md`):** `8px 8px 0px #000000`. Used for featured product cards, hovering states, flyout carts, and sticky filtering bars.
- **Modal & Flagship Tier (`shadow-lg`):** `12px 12px 0px #000000`. Used for mega-drawers, cart flyouts, quick-view dialogs, and hero purchase matrices.

### Kinetic Tactile Push Mechanism
Buttons and cards physically press down along the 45-degree shadow vector on click:
- **Resting:** `box-shadow: 4px 4px 0px #000000; transform: translate(0, 0);`
- **Active / Pressed:** `box-shadow: 0px 0px 0px #000000; transform: translate(4px, 4px);`
- **Focus-Visible:** Add an additional `2px solid #000000` outline offset by `2px`.

## Shapes

The geometric framework is razor-sharp. `roundedness` is set to `0` across all structural containers, cards, dialogs, inputs, and primary buttons. 

- **Edge Definition:** Zero radius (`0px`) on all corners. Clean 90-degree junctions emphasize the raw industrial grid.
- **Exception for Pills/Badges:** High-contrast notification counts (e.g., cart quantity badge) may use a circular container, but all structural elements, interactive controls, and UI panels remain strictly rectangular with 2px borders.

## Components

### Buttons
- **Primary Action (Add to Cart / Checkout):** Background `#ffe17c`, color `#000000`, 2px solid `#000000` border, `4px 4px 0px #000000` shadow. Font: Space Grotesk Bold, all-caps. Active state: translates `4px 4px`, shadow collapses to `0px 0px 0px`.
- **Secondary Action:** Background `#ffffff`, color `#000000`, 2px solid `#000000` border, `4px 4px 0px #000000` shadow. Active state compresses by 4px.
- **Inverted Dark Action:** Background `#171e19`, color `#ffffff`, 2px solid `#000000` border, `4px 4px 0px #000000` shadow.

### Product Cards
- Background `#ffffff`, 2px solid `#000000` border.
- Shadow: `4px 4px 0px #000000` resting; transitions to `8px 8px 0px #000000` on hover (with a `-2px -2px` translation).
- Image section separated from product details by a horizontal 2px solid `#000000` rule.
- Product tags positioned absolute top-left with a 2px border and `#b7c6c2` or `#ffe17c` background.

### Input Fields & Selects
- Background `#ffffff`, 2px solid `#000000` border, `0px` radius, padding `12px 16px`.
- Shadow: Resting `2px 2px 0px #000000`. On focus: `4px 4px 0px #000000`, background changes to `#ffffff`, label text becomes bold.

### Chips & Filter Tags
- Background `#ffffff`, 2px solid `#000000` border, `2px 2px 0px #000000` shadow.
- **Selected State:** Fills with `#ffe17c` (Primary Yellow) or `#b7c6c2` (Accent Sage), translated `2px 2px` with shadow reduced to zero.

### Checkboxes & Radio Buttons
- Custom square boxes: `20px x 20px`, 2px solid `#000000`, `2px 2px 0px #000000` shadow.
- **Checked State:** Solid `#ffe17c` fill with an inset thick black checkmark graphic. Active state presses down by 2px.

### Slide-Over Cart Drawer
- Docked flush right, 2px solid `#000000` left border, `12px 12px 0px #000000` offset shadow.
- Header features high-contrast `#171e19` background with `#ffffff` text or high-energy `#ffe17c` with `#000000` text.
- Line items are separated by full-width 2px solid horizontal rules.
