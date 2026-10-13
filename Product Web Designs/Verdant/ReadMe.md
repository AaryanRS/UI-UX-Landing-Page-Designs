---

# Welcome 👋

In this ReadMe you’ll find **all the important colors, fonts, and design rules** that define the landing page / frontend style system.  
Everything from typography scales to spacing tokens and component guidelines is documented here for easy reference.

---

## How to Use

The entire design system is written in **HTML‑ready code snippets**.  
That means you can simply **copy any section and paste it into your `.html` file** to bring the styles directly into your project.  
No complex setup required — just plug and play.

---

IMPORTANT - If u are opening folder in VSC MAKE SURE TO Install Live Server 

---

## Name: Organic Brutalism

---

colors:
  surface: '#fefae0'
  surface-dim: '#dedbc2'
  surface-bright: '#fefae0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f4db'
  surface-container: '#f2efd5'
  surface-container-high: '#ede9cf'
  surface-container-highest: '#e7e3ca'
  on-surface: '#1d1c0d'
  on-surface-variant: '#404943'
  inverse-surface: '#323120'
  inverse-on-surface: '#f5f1d8'
  outline: '#707972'
  outline-variant: '#c0c9c1'
  surface-tint: '#2e694d'
  primary: '#002e1d'
  on-primary: '#ffffff'
  primary-container: '#01472e'
  on-primary-container: '#79b595'
  inverse-primary: '#96d4b2'
  secondary: '#566342'
  on-secondary: '#ffffff'
  secondary-container: '#d7e5bb'
  on-secondary-container: '#5a6745'
  tertiary: '#232a10'
  on-tertiary: '#ffffff'
  tertiary-container: '#384024'
  on-tertiary-container: '#a3ac87'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b2f0cd'
  primary-fixed-dim: '#96d4b2'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#115137'
  secondary-fixed: '#dae8be'
  secondary-fixed-dim: '#becca3'
  on-secondary-fixed: '#141f05'
  on-secondary-fixed-variant: '#3f4b2c'
  tertiary-fixed: '#dee7bf'
  tertiary-fixed-dim: '#c2cba4'
  on-tertiary-fixed: '#171e06'
  on-tertiary-fixed-variant: '#424a2d'
  background: '#fefae0'
  on-background: '#1d1c0d'
  surface-variant: '#e7e3ca'

---

typography:
  display-xl:
    fontFamily: Anton
    fontSize: 112px
    fontWeight: '400'
    lineHeight: 96px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Anton
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.01em
  display-lg:
    fontFamily: Anton
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 68px
    letterSpacing: -0.01em
  display-lg-mobile:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.15em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.2em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4rem
---

## Brand & Style

This design system establishes an unapologetic collision between raw structural brutalism and earthbound botanical warmth. Built for modern wellness and sustainable consumer packaged goods, it strips away predictable sterile clinical minimalism in favor of visceral, editorial weight. The brand voice is grounded, radical, transparent, and authoritative—demanding consumer presence while offering sensory tactile comfort.

The aesthetic philosophy centers on exaggerated physical forms, unexpected scale, analog textures, and organic tension:
- **Massive Structural Contrast:** Monumental condensed display typography locks against clean, precision-spaced utilitarian micro-type.
- **Biomorphic Brutalism:** Extreme, bulbous container radii (40px to 80px) simulate river stones and compressed natural pulp, rejecting standard soft rectangles.
- **Physicality & Artifacting:** Micro-dithered analog film grain noise coats flat planes, imbuing high-contrast layouts with the tactile depth of risograph and recycled matte substrates.
- **Kinetic Dynamism:** Snappy custom mechanical spring curves (`cubic-bezier(0.16, 1, 0.3, 1)`) control component behavior alongside subtle floating parallax depth planes.

---

## Colors

The palette derives strictly from rich botanical strata: deep canopy foliage, sun-bleached lichens, and untreated card stock. Color interactions must favor extreme tonal splits rather than subtle middle-tone steps.

### Roles & Semantic Mapping
- **Primary (`#01472E` - Deep Forest):** Structural anchor. Serves as default dark canvas surface, maximum-contrast headline color on light fields, primary button fill, and high-impact framing rules.
- **Secondary (`#A3B18A` - Moss):** Intermediate tactile layer. Applied to interactive surface states, secondary action buttons, badges, and active state pill indicators.
- **Tertiary (`#CCD5AE` - Sage):** Soft highlight surface. Deployed for subtle container fills, accent dividers, hover states on Cream, and muted badges.
- **Accent Olive (`#E9EDC9`):** High-light botanical flash. Used for urgent metadata tags, critical badge callouts, and cursor/focus ring enhancements.
- **Neutral Canvas (`#FEFAE0` - Cream):** Primary ambient backdrop and base typography color when set against Deep Forest. Evokes raw unbleached cotton and heavyweight card stock.

### Color Rules
- Maintain pure `#01472E` on `#FEFAE0` for core transactional and reading contexts to preserve AAA compliance.
- Never use pure black (`#000000`) or pure white (`#FFFFFF`). Pure tints flatten the natural analog depth.
- Tint overlays, noise layers, and ambient shadow structures must derive from `#01472E` at varying opacities to maintain environmental cohesion.

---

## Typography

The typographic tension relies on the extreme polarization between **Anton** and **Inter**.

### Execution Rules
- **Display & Headlines (Anton):** Always rendered in tight line-heights where descenders nearly kiss ascenders. Do not track out Anton; preserve its compressed, monolithic vertical rhythm. Use uppercase for high-impact brand statements, ingredient headlines, and key landing metrics.
- **Body & Utility (Inter):** Serves functional copy, regulatory data, nutritional callouts, and interactions. 
- **Tracked Uppercase Styling:** All `label-*` tokens must be rendered in `text-transform: uppercase` with generous tracking (`0.12em` to `0.20em`) to mimic raw industrial shipping marks and laboratory batch typography.

---

## Layout & Spacing

The layout model is a modular, fluid column grid designed to accommodate hyper-dense typographic posters alongside sweeping negative space.

### Grid Architecture
- **Desktop (≥ 1280px):** 12-column layout with `2.5rem` gutters and `3rem` frame margin. Asymmetrical container spans (e.g., 7-column primary card opposing a 5-column stacked metadata tray) break standard corporate symmetry.
- **Tablet (768px – 1279px):** 8-column layout with `1.5rem` gutters and `2rem` frame margin.
- **Mobile (≤ 767px):** 4-column layout with `1rem` gutters and `1.25rem` outer canvas padding.

### Layout Principles
- Stack cards vertically on mobile with negative margins or deliberate overlaps to simulate physically layered card stock.
- Use wide gaps (`space-xl`) between distinct thematic narrative blocks, contrasted with tight padding (`space-xs` to `space-sm`) inside brutalist data tables.
- Floating parallax elements (e.g., floating ingredient badges, floating circular seal elements) must sit outside the strict vertical flow, moving with viewport scrolling speeds adjusted between `0.05` and `0.15`.

---

## Elevation & Depth

Visual hierarchy eschews artificial drop shadows in favor of tinted atmospheric displacement and physical surface layering.

### Surface Depth Layers
- **Substrate (Base 0):** Unbleached Cream (`#FEFAE0`) or inverted deep Forest (`#01472E`). Coated with an SVG-driven, 4% opacity analog grain filter simulating fibrous packaging paper.
- **Floating Containers (Level 1):** Solid colored slabs (`#E9EDC9` or `#CCD5AE`) floating above base canvases.
- **Modal & Overlay Plates (Level 2):** Elevated interactive components with zero blur offset, strictly cast with deep tinted environmental shadows.

### Shadow Character
Shadows must never use achromatic grey. All shadows are cast using translucent Deep Forest:
- **Default Elevated:** `0 20px 40px -15px rgba(1, 71, 46, 0.22)`
- **Floating Element / Hover:** `0 32px 64px -20px rgba(1, 71, 46, 0.32)`
- **Inverted State (on Forest):** Cards do not use drop shadows; they rely on 1.5px solid borders of `#A3B18A` or stark tonal fills of `#CCD5AE`.

### Transitions & Motion
All dynamic transformations, elevations, and hover responses strictly use:
`transition: all 400ms cubic-bezier(0.16, 1, 0.3, 1);`
This curve provides an aggressive snap out with a long, elegant physical settling curve.

---

## Shapes

The shape system is deliberately radical: ultra-rounded pebble forms meet raw tabular geometry.

### Radius Application Guidelines
- **Core Structural Units (Level 3 Token System):**
  - **Hero Containers & Major Visual Cards:** Override base system tokens using custom ultra-radii ranging from `2.5rem` (40px) on mobile up to `5rem` (80px) on expansive desktop displays.
  - **Standard Cards & Segmented Modals:** Built with `2rem` (32px) corner radii.
  - **Buttons, Pills, Inputs, and Tags:** Full `9999px` capsule radii.
- **Asymmetric Tension:** Occasional structural blocks feature intentional diagonal rounding (e.g., `top-left: 5rem`, `bottom-right: 5rem`, with alternating corners set to `1rem`) to resemble polished botanical fragments.

---

## Components

### Buttons
- **Primary Pill:** Background `#01472E`, text `#FEFAE0`, font `label-lg`, tracked uppercase. Border-radius `9999px`. Height `3.75rem` (60px), horizontal padding `2.5rem`. Hover behavior: scale `1.03` with a snapping translate-y `-2px` using `cubic-bezier(0.16, 1, 0.3, 1)` and shadow `0 16px 32px -8px rgba(1, 71, 46, 0.28)`.
- **Secondary Pebble:** Background `#CCD5AE`, text `#01472E`. Hover switches fill to `#E9EDC9`.
- **Ghost Utility:** Background transparent, 1.5px outline in `#01472E`, text `#01472E`. Hover: fill `#01472E`, text `#FEFAE0`.

### Cards & Packaging Tiles
- **CPG Product Hero Tile:** Background `#E9EDC9`, border-radius `3.5rem`. Internal padding `2.5rem`. Contains Anton headline pinned to bottom, oversized raw cutout product photography overlapping container bounds with floating parallax scroll offset.
- **Ingredient Dossier Card:** Background `#CCD5AE` with integrated film grain overlay, border-radius `2.5rem`. High-contrast data badges nested inside.

### Chips & Micro-Badges
- **Form Factor:** Fully rounded pill (`rounded-full`), height `2rem` (32px), internal horizontal padding `1rem`.
- **Typographic Treatment:** `label-sm` in Inter, strictly uppercase with `0.2em` letter spacing.
- **Variants:** Active selection in `#01472E` text `#FEFAE0`; inactive in `#A3B18A` with 20% opacity background.

### Input Fields & Controls
- **Text Inputs:** Pill shaped (`3.5rem` height), background `#FEFAE0`, border `2px solid #01472E`. Inset padding `1.75rem`. Placeholder text in muted `#A3B18A`. Focus state: border expands to `3px solid #01472E`, with an ambient ring offset in `#CCD5AE`.
- **Checkboxes & Radios:** Heavy `2px solid #01472E` containers. Checkboxes use custom squircle geometry (`0.5rem` radius); radios remain round. Active fill snaps quickly into `#01472E` with Cream glyph indicators.

### Lists & Data Displays
- **Nutritional / Provenance Rows:** Separated by horizontal hairpins (`1.5px solid rgba(1, 71, 46, 0.15)`). Left-aligned category label in `label-md` tracked Inter; right-aligned metrics set in condensed `headline-sm` Anton.

### Specialized System Element: Analog Texture Overlay
- All viewport surfaces and card backgrounds feature a non-interactive pointer-events-none SVG noise overlay:
  `filter: contrast(120%) brightness(100%); mix-blend-mode: multiply; opacity: 0.04;`