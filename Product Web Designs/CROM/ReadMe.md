# CROM // Project A-01 Product Experience

## 1. Project Brief & Overview
**CROM** (developed under CROM Labs / Technical Apparel Systems) is a high-end futuristic fashion and technology experience designed as an interactive, cinematic product reveal. It sits at the intersection of a **luxury fashion campaign**, a **technical product presentation**, a **digital editorial**, and a **futuristic product laboratory**.

The product experience showcases the **A-01 Exoskeleton Jacket**—an ultra-ergonomic adaptive garment engineered from reactive graphene lattices and aerogel thermal matrices for extreme atmospheric volatility.

---

## 2. Visual Identity & Atmosphere
- **Dominant Page Environment**: `#050505` to `#0e0e0e` (pitch-black / deep obsidian charcoal).
- **Subtle Technical CAD Grid**: Fine engineering paper pattern with millimeter tick crosshairs and blueprint reticles integrated directly into the background texture to evoke an aerospace CAD workbench without distracting from the hero garment.
- **Color Discipline & Accents**:
  - Primary UI Neutral: Pitch black `#050505`, container low `#131313`, slate gray `#8e9192`.
  - Precision Accent: Electric Cyan / Blueprint Blue (`#00f0ff` / `#00e5ff`).
  - Product Chromatic Accents:
    - **Acid Tactical**: Neon Lime (`#a3e635` / `#bef264`)
    - **Hyperion Glow**: Hot Neon Magenta (`#f43f5e` / `#ec4899`)
    - **Thermal Hazard**: Safety Fiery Orange (`#f97316` / `#ea580c`)
    - **Obsidian Core**: Luminescent Cyan / Electric Blue (`#00f0ff` / `#38bdf8`)
- **Restraint**: Flat, dark surfaces with high-contrast hairline borders (`rgba(255, 255, 255, 0.08)`) and targeted luminescent glow states on active elements.

---

## 3. Typography & Microcopy Hierarchy
- **Primary Display Font**: `Barlow Condensed` / Technical Condensed Sans (`uppercase`, tight tracking, architectural weight 700–900).
  - Used for primary scene titles: `CROM`, `MICRON-CALIBRATED ANATOMY`, `COLORWAY CHROMATICS & BAY DEPLOYMENT`, `TECHNOLOGY ENGINEERED TO ENDURE`, `NEED TO KNOW.`
- **Secondary & Body Font**: Clean geometric technical sans-serif (`Space Grotesk` / `Inter`) for editorial statements and technical paragraphs.
- **Data & Telemetry Font**: Monospaced font (`JetBrains Mono` / `Courier Prime` / `Share Tech Mono`) with wide letter-spacing (`tracking-widest`), small font sizes (`10px`–`12px`), and low visual weight for:
  - CAD coordinates (`POS: 35.6762° N / 139.6503° E`)
  - Sub-system status tags (`STATUS: NOMINAL`, `04 // COMPOSITE MATRIX`)
  - Product hardware specs (e.g., `HYDROSTATIC: 28,000 MM`, `TENSILE COMPRESSION: 1,420 MPA`).

---

## 4. UI Components & Layout Architecture
1. **Streamlined Header**:
   - Clean, balanced, non-flashy navigation bar with minimal visual noise.
   - Wordmark: **CROM** uppercase with subtle `LABS` subtext.
   - Evenly spaced links: `OVERVIEW`, `SPECIFICATIONS`, `ARCHIVE`, `LAB`, `SYSTEM`.
   - Outlined hairline button for quick serialized pre-orders (`ORDER // A-01`).
2. **Hero Stage (Suspended Zero-G Inspection)**:
   - Floating weightless jacket asset illuminated with cinematic rim lighting.
   - Interactive reticle HUD markers targeting Collar Gasket, Fidlock Titanium Hardware, and Articulated Cuff.
3. **Anatomy Inspection Studio**:
   - Split-screen technical documentation with macro crop viewport and interactive subsystem telemetry rows.
4. **Bay Deployment (Variant Showcase)**:
   - 4-column tactical bay cards displaying Acid, Hyperion, Thermal, and Obsidian colorways with allocation meters and live selection triggers.
5. **Exploded Composite Material Stack**:
   - Layer-by-layer architectural breakdown of 4 aerospace materials (Aerospace Membrane, Hexagonal Micro-Mesh, Technical Aerogel Core, Carbon-Weave Exoskeleton).
6. **Device Showcase Terminals**:
   - Realistic workstation laptop viewport with interactive scene simulator + mobile companion console.

---

## 5. Animations & Motion System
- **Scroll-Driven Depth & Parallax**: Layered depth composition moving background CAD grid, midground floating jacket, and foreground HUD coordinates at varying velocity rates.
- **HUD Reticle Pulsing**: Ambient subtle cyan glow animations (`@keyframes pulse-glow`) on calibration points.
- **Smooth Interactive State Transitions**:
  - Smooth card translation (`translate-y-[-4px]`) on bay card hover with chromatic border illumination.
  - Interactive variant tabs switching hardware preview images without layout shifts.
- **Device Simulator Cycle**: Multi-viewport hardware preview simulating live responsive rendering on titanium laptop and mobile terminals.


---
name: Obsidian Blueprint
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#dcb8ff'
  on-secondary: '#480081'
  secondary-container: '#7701d0'
  on-secondary-container: '#dcb7ff'
  tertiary: '#dbffd7'
  on-tertiary: '#003911'
  tertiary-container: '#00fa64'
  on-tertiary-container: '#006e27'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#efdbff'
  secondary-fixed-dim: '#dcb8ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6700b5'
  tertiary-fixed: '#6bff83'
  tertiary-fixed-dim: '#00e55b'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#00531b'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Barlow Condensed
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 76px
    letterSpacing: 0.08em
  display-xl-mobile:
    fontFamily: Barlow Condensed
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: 0.06em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: 0.06em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: 0.05em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0.05em
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.04em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.12em
  label-xs:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '400'
    lineHeight: 12px
    letterSpacing: 0.14em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The brand occupies the intersection of avant-garde high fashion, military-grade utility, and cybernetic precision. Tailored for discerning collectors, technical apparel enthusiasts, and digital-first design purists, the interface evokes an ultra-exclusive industrial prototyping lab. Users should feel as though they are accessing a classified procurement terminal for experimental ergonomic armor.

The visual style is **Cybernetic Blueprint Brutalism**:
- **Canvas:** Pure pitch-black voids punctuated by calibrated Cartesian coordinate lines, millimeter tick-marks, and wireframe schematics.
- **Tone:** Authoritative, razor-sharp, surgical, and uncompromised.
- **Structural Integrity:** Heavy reliance on thin hairline divisions, technical corner brackets, dynamic monospaced telemetry, and stark, architectural geometry balanced against rich photographic textures of weatherproof fabrics, magnetic hardware, and matte composite textiles.

## Colors

The palette is engineered around pure pitch dark space with high-luminance technical accent signals:

- **Primary (`#00F0FF` - Electric Cyan / Blueprint Blue):** Applied to active states, critical specs, precision reticles, primary CTAs, and structural accents.
- **Secondary (`#8A2BE2` - Ultraviolet Void):** Used for ambient energy glows, elevation accents, secondary highlights, and specialized tier badges.
- **Tertiary (`#00FF66` - Tactical Radar Green):** Reserved for live telemetry, stock availability counters, status pings, and hardware validation states.
- **Neutral (`#050505` - Monolithic Pitch Black):** The deepest foundation surface. Nested surfaces transition through `#0D0F12` (Container Base) to `#161A1F` (Card Surface), bound by `#242B35` (Grid Line / Hairline Border). Text renders primarily in `#E6EDF3` (Standard Microcopy) and `#8B949E` (Technical Labels).

## Typography

Typography establishes an unambiguous hierarchical tension between raw industrial drafting notes and imposing brutalist headlines:

- **Display & Headlines (`Barlow Condensed`):** Rendered uniformly in uppercase. Employs wide letter-spacing (`0.04em` to `0.08em`) to mirror architectural structural drawings and precision flight equipment nomenclature.
- **Body (`Geist`):** Delivers neutral, hyper-legible descriptions for product ergonomics, material engineering disclosures, and narrative briefings without competing with technical markings.
- **Telemetry & Labels (`JetBrains Mono`):** Applied to product serials, fabric composition formulas, garment dimensions, thermal ratings, coordinate indicators, and navigational markers. Always paired with distinct letter spacing to enforce tactical precision.

## Layout & Spacing

The layout is anchored to a calibrated 12-column fluid grid governed by strict engineering geometry:

- **Grid Framework:** 12 columns on desktop with `1.5rem` gutters, collapsing to 6 columns on tablet and 4 columns on mobile with `1rem` gutters.
- **Canvas Margins:** Wide `3rem` frame boundaries on desktop establish an intentional viewfinder/chassis framing effect around the viewport; narrows to `1.25rem` on mobile.
- **Blueprint Coordinate Rhythm:** Spacing adopts a strict base-4 cadence (0.25rem to 2.5rem). Components nest inside perimeter coordinate lines, with corner crosshairs (`+`) marking primary module intersections.
- **Reflow Architecture:** Technical spec tables display multi-column diagnostic grids on desktop, collapsing into vertical indexed accordion modules on mobile devices while maintaining strict border alignments.

## Elevation & Depth

Visual hierarchy rejects organic soft drop shadows in favor of tonal planar stratification and luminous optical bleeding:

- **Surface Tiers:**
  - `Base`: `#050505` (Deep space void with persistent subtle 32px blueprint grid pattern rendered in `rgba(0, 240, 255, 0.04)`).
  - `Level 1 (Panels & Trays)`: `#0B0E12` with a 1px border of `rgba(255, 255, 255, 0.08)`.
  - `Level 2 (Tactical Spec Cards)`: `#11161D` with a 1px border of `rgba(0, 240, 255, 0.22)`.
  - `Level 3 (Modals & HUD Overlays)`: `#151B24` with a 1px border of `rgba(0, 240, 255, 0.45)`.
- **Luminescence & Glow:** Focused neon bleeding replaces natural drop shadows. Focused elements (active cards, primary buttons) cast an ultra-tight ambient cyan aura: `box-shadow: 0 0 18px rgba(0, 240, 255, 0.25), inset 0 0 12px rgba(0, 240, 255, 0.08)`.
- **Ultraviolet Depth:** Secondary atmospheric backdrops utilize blurred vector orbs of `#8A2BE2` at 12% opacity behind imagery to generate depth and contrast against cold technical vector strokes.

## Shapes

The interface embraces complete mathematical precision:
- **Zero Radius (`roundedness: 0`):** Curvature is forbidden. All elements have 90-degree corners to evoke industrial chassis panels, microchip dies, and mil-spec housings.
- **Technical Chamfers:** Distinct cards and primary trigger controls utilize a geometric 45-degree corner cut (`clip-path: polygon(...)` of 8px to 12px) on top-right and bottom-left vertices.
- **Reticle & Framing Accents:** Structural cards display open-bracket corners (`┌ ┐ └ ┘`) using hairline pseudo-elements tinted in Electric Cyan.

## Components

### Buttons & Action Triggers
- **Primary CTA:** Pure Electric Cyan background (`#00F0FF`) with dark obsidian text (`#050505`), chamfered top-right corner, uppercase `JetBrains Mono` label, and a leading index tag (`[01 // ACQUIRE]`). Hover triggers an internal white flash with a 2px offset border.
- **Secondary CTA:** Ghost structure with a 1px border (`rgba(0, 240, 255, 0.3)`), transparent background, uppercase text in `#E6EDF3`, and bracketed corner indicators. Hover shifts border to solid Ultraviolet (`#8A2BE2`).

### Chips & Metadata Tags
- **Telemetry Chips:** Monospaced micro-containers (`label-xs`) displaying technical specs (e.g., `GORE-TEX PRO 3L`, `WATERPROOF 28,000MM`, `WEIGHT // 412G`).
- **Styling:** Inset `#080B0E` background, 1px perimeter border in `#242B35`, prefixed with status dot or tiny crosshair.

### Tactical Spec Cards
- **Architecture:** Flat `#11161D` plate surface encased in a hairline technical grid frame with chamfered edges and printed dimensional metadata along the outer perimeter (e.g., `REF. TY-892 // SEC.04`).
- **Interactive State:** Hover elevates border luminance to Electric Cyan, displaying crosshair reticles over the garment blueprint visual.

### Lists & Data Matrices
- **Diagnostic Rows:** Structured as strict multi-column tables with hairline horizontal separators (`#1A212B`).
- **Data Points:** Left-aligned technical spec key in `label-sm` muted gray (`#8B949E`), followed by dotted leader lines (`. . . . .`), right-aligned to high-contrast cyan values (`#00F0FF`).

### Input Fields & Selectors
- **Input Design:** Rectangular, zero-radius fields with dark void background (`#080B0E`) and bottom-border priority (1px solid `#242B35`). Focus activates a full perimeter neon border and a pulsing vertical terminal cursor.
- **Checkboxes & Radios:** Sharp square boxes with cyan bracket markers when active; status confirmed via monospaced binary indicators (`[X]` or `[0/1]`).

### Additional Specialized Components
- **HUD Reticle Viewfinder:** Interactive image magnifier for textile microscopic weaves, rendered with dynamic crosshairs, coordinate readouts, and scale ratios (`1:1.4`).
- **Telemetry Stock Barometer:** Stock levels displayed as segmented neon indicator bars resembling battery or radiation cell levels.
