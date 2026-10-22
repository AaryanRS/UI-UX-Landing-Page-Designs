# ASTRA — Kinetic Brutalist Service Studio

## 1. Project Brief
ASTRA is a high-impact, digital-first brutalist service web application landing page. The design creates a palpable sense of urgency, technical sophistication, and uncompromising precision. It strips away ornamental fluff, soft pastel palettes, gradients, and gentle drop shadows in favor of a raw, geometric, high-contrast aesthetic calibrated for modern software architecture studios, WebGL engineering teams, and high-velocity digital product shops.

---

## 2. Visuals & Aesthetic Direction
- **Style Archetype**: Kinetic Brutalism.
- **Visual Tenets**:
  - Raw, uncompromised contrast between electric brand orange, solid ink black, and surgical white.
  - Skewed structural transitions (-2deg) breaking conventional responsive web grids.
  - Infinite linear marquee animations that communicate high throughput and active data streaming.
  - Sharp 2px+ structural boundaries with zero border-radius, except for deliberate pill-shaped tactile controls.
  - Precision mechanical metadata rows grounding massive display headers with geographical coordinates and system telemetry.

---

## 3. Color System
The aesthetic strictly adheres to a three-color brutalist hierarchy:

| Color Name | Hex Code | Primary Application |
| :--- | :--- | :--- |
| **Brand Orange** | `#FF4D00` | Canvas background, highlight text, brand marks, active status accents |
| **Solid Black** | `#000000` | Display headlines, section dividing lines (2px), dark service section background, pill container background |
| **Pure White** | `#FFFFFF` | High-contrast body copy on black surfaces, badge tag labels, inverted hover states |

### Text Selection Behavior
- `::selection` background: `#000000`
- `::selection` text color: `#FF4D00`

---

## 4. Typography Hierarchy

| Role | Font Family | Size / Weights | Spec & Formatting |
| :--- | :--- | :--- | :--- |
| **Display Headings** | `Archivo Black`, sans-serif | 16vw (Hero), 14vw (CTA), 6.5vw (Services) | Strict UPPERCASE, tracking `-0.04em`, line-height `0.85`–`0.90` |
| **Technical Metadata & UI Labels** | `Space Mono`, monospace | 9px – 14px, Regular (400) & Bold (700) | Tracking `-0.02em`, uppercase data stamps, system telemetry, pill links |
| **Body & Supporting Copy** | `Inter`, sans-serif | 14px – 16px, Regular (400) & Medium (500) | High readability, clean geometry |

---

## 5. Layout & Structural Breakdown

### A. Floating Navigation Bar
- Fixed top positioning with non-blocking pointer events.
- Left: Solid black ASTRA brand badge with square orange indicator and system status stamp.
- Center: Black pill container (`bg-[#000000]`, `rounded-full`, 2px solid border) housing navigation links in white `Space Mono` (12px). Hover state smoothly inverts link background to `#FFFFFF` and text to `#000000`.
- Right: Online heartbeat indicator (pulsing green dot) and social icon links.

### B. Typographic Hero Section
- Fullscreen viewport layout with a massive centered headline (`ASTRA`) rendered in `Archivo Black` at 16vw.
- Separated from metadata by a 2px solid black horizontal rule.
- Three-column ground row:
  - **Left**: Location telemetry (`BASED IN BERLIN & TOKYO`, 52.5200° N, 13.4050° E).
  - **Center**: The interactive circular rotating scroll indicator component.
  - **Right**: Technical disciplines and active contract status.

### C. Skewed Marquee Section
- Background `#000000`, rotated/skewed at `-2deg` with a 105% viewport scale to eliminate edge clipping.
- **Row 1**: Electric orange text (`#FF4D00`) in `Archivo Black` (10vw), infinite scroll to the left.
- **Row 2**: Pure white text at 80% opacity (`#FFFFFF/80`) in `Archivo Black` (9vw), infinite reverse scroll to the right.

### D. Vertical Service List (Core Protocols)
- Full-bleed dark surface (`#000000`) with crisp `1px solid rgba(255,255,255,0.2)` dividers.
- Items feature:
  - Numeric index in `#FF4D00` (`Space Mono`).
  - Giant service titles in `Archivo Black` (6.5vw).
  - Pill-shaped technical tag badges.
  - Interactive hover state: background shifts to 5% white opacity, title translates right (`translate-x-4`), and a circular `#FF4D00` arrow icon fades in and rotates 45 degrees.
- Telemetry matrix grid featuring Lighthouse score (100/100), deployment speed (< 14 days), uptime SLA (99.99%), and carbon efficiency.

### E. Giant CTA & Clean Footer
- Centered 14vw headline: `LET'S BUILD`.
- Massive rounded pill button (`bg-[#000000]`, white text, orange accent arrow) that scales up (`scale-110`) on hover.
- Footer anchored with a 2px black border, copyright notation, and direct links in 12px `Space Mono`.

---

## 6. Special Component Specifications

### 1. Rotating Scroll Indicator
- **Geometry**: 144px diameter circular SVG.
- **Text Path**: SVG `<textPath>` bound to a circular coordinate path repeating `"SCROLL DOWN • "` in uppercase `Space Mono` (9px bold).
- **Animation**: Seamless linear infinite CSS rotation (`360deg` over 12s).
- **Core Element**: Center circular black node housing a Lucide arrow-down icon in `#FF4D00`.

### 2. Kinetic Brutalist Card
- Full-width interactive list row.
- Zero border radius; crisp dividing rules.
- State transforms: `translateX(16px)` title shift with synchronized `opacity: 1` and `rotate(45deg)` on directional icon.

---
name: Kinetic Brutalism
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#e6beb2'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#ad897e'
  outline-variant: '#5c4037'
  surface-tint: '#ffb59e'
  primary: '#ffb59e'
  on-primary: '#5e1700'
  primary-container: '#ff571a'
  on-primary-container: '#521300'
  inverse-primary: '#ae3200'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#929090'
  on-tertiary-container: '#2a2a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#3a0b00'
  on-primary-fixed-variant: '#852400'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Archivo Narrow
    fontSize: 72px
    fontWeight: '900'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Archivo Narrow
    fontSize: 40px
    fontWeight: '900'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Archivo Narrow
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-mono-lg:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-mono-md:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-mono-sm:
    fontFamily: Space Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.08em
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-energy neo-brutalism engineered for high-density, technical platforms that demand urgency, absolute clarity, and unyielding posture. The aesthetic pairs raw industrial architecture with hyper-kinetic electronic instrumentation.

### Target Audience & Tone
Engineers, quantitative analysts, terminal power-users, and technical operators who favor information density, structural legibility, and high-contrast precision over ornamental softness. The UI evokes ruthless efficiency, technical dominance, kinetic energy, and immediate situational awareness.

### Style Directives
- **Structural Brutalism:** Monolithic grids defined by stark 2px structural containment borders. No arbitrary floating components; elements snap flush to adjacent containers.
- **Monochrome Foundation with Kinetic Hyper-Accents:** Solid black foundation with optical white high-contrast elements, sliced through by pure radioactive orange (`#FF4D00`) to direct attention instantaneously.
- **Tension of Forms:** Severe, hard-edged right-angle boundaries for layout panes, data cards, and metric pods, contrasted sharply with oversized hyper-radius pill shapes exclusively reserved for dynamic controls, filters, and status toggles.

## Colors

The palette operates under an uncompromising high-contrast dark mode protocol. Chromatic noise is strictly prohibited; color represents kinetic state, critical action, or functional segmentation.

### Palette Architecture
- **Primary (`#FF4D00`):** Kinetic Orange. High-voltage highlight used for primary calls-to-action, active indicators, interactive hover targets, live status beacons, and critical thresholds.
- **Secondary (`#FFFFFF`):** Pure White. The primary luminance channel. Reserved for prominent headers, active glyphs, stark outlines, and focused states.
- **Tertiary (`#1A1A1A`):** Hardened Carbon. Used for nested sub-surfaces, alternating row tracks, inactive container fills, and low-priority structural bounds.
- **Neutral (`#000000`):** Absolute Pitch Black. The absolute baseline canvas background, primary surface fill, and inverse typography color when sitting on Kinetic Orange or Pure White fills.

### Rules of Engagement
- Never use soft, low-contrast grays for critical UI text; maintain minimum WCAG AAA contrast across all critical data.
- Hover states invert foreground and background colors completely rather than shifting transparency (e.g., a black-filled button with white text flips to a kinetic orange fill with solid black text).
- Borders never use opacity or alpha-channel fading. They remain 100% solid white, solid black, or solid kinetic orange.

## Typography

The typographic hierarchy is built on a high-tension triad: heavy display impact, utilitarian reading comfort, and precise computational telemetry.

### Typographic Roles
- **Display & Headlines (`Archivo Narrow`, Extra Bold / Black):** Set strictly in uppercase. Characters sit compact, commanding, and punchy. Used for hero impact statements, page titles, and dominant section callouts.
- **Body & Long-form (`Inter`):** Neutral, hyper-legible, geometric sans-serif for contextual copy, explanatory content, data tables, and modal instructions. Ensures effortless high-speed reading.
- **Labels, Telemetry & Metadata (`Space Mono`):** Fixed-width, clinical, and unapologetically technical. Mandated for all timestamps, status badges, telemetry feeds, financial parameters, system alerts, table headers, and coordinates. Space Mono labels must always be formatted in uppercase.

## Layout & Spacing

The structural layout relies on an industrial, full-bleed 12-column fluid grid. Layout frames and parent containers visually snap to each other using shared borders rather than floating margins.

### Grid & Breakpoints
- **Desktop (1200px+):** 12 columns, 24px (`1.5rem`) gutters, 32px (`2rem`) canvas outer margins. Multi-column command decks with simultaneous telemetry views.
- **Tablet (768px - 1199px):** 8 columns, 16px (`1rem`) gutters, 24px (`1.5rem`) margins. Side rails collapse into dense horizontal tab bars.
- **Mobile (< 768px):** 4 columns, 16px (`1rem`) gutters, 16px (`1rem`) margins. Linear stack; multi-tier cards break into modular, flush-stacked rectangular sections.

### Spacing Discipline
- Maintain tight internal padding inside data cards (`space-md` or `space-sm`) to maximize density.
- Do not introduce arbitrary whitespace or soft guttering. Distances between elements must consistently resolve to the strict 4px/8px incremental tokens.

## Elevation & Depth

This design system explicitly rejects drop shadows, blurred ambient lighting, simulated 3D bevels, and atmospheric depth. The interface occupies an absolute planar space.

### Depth Mechanics
- **Hard 2px Borders:** All separation between UI modules is established via crisp, opaque 2px structural lines in either `#FFFFFF`, `#1A1A1A`, or `#FF4D00`.
- **Tonal Stepping:** Surfaces stack flatly like circuit boards. Base canvas sits at `#000000`, active cards or panels sit at `#0A0A0A` or `#121212`, and secondary inspection trays rest on `#1A1A1A`.
- **Hard Offset Brutalist Depth:** When intentional elevation must be visualized (e.g., active floating tooltips, drag targets, or focused popovers), use a hard 4px solid diagonal displacement offset shadow: `box-shadow: 4px 4px 0px 0px #FF4D00` or `4px 4px 0px 0px #FFFFFF`. No blur radius allowed under any condition.

## Shapes

The geometric rule is binary and non-negotiable: all layout containers are razor-sharp right angles, while interactive toggles, badge chips, and kinetic pills are fully rounded cylinders.

### The Binary Shape System
1. **0px (Sharp Right Angles):** Applied to the entire structural architecture: cards, modals, table cells, code blocks, viewports, and primary visual containers. There are no softened corners on structural architecture.
2. **Infinite Radius (Pure Pill-Shape):** Reserved exclusively for state toggles, interactive navigation pills, status badges, and chip filters. A pill shape explicitly communicates to the user: "This item is an interactive control or a live status beacon."

## Components

### Buttons
- **Primary Kinetic Button:** Pill-shaped boundary or sharp rectangular block (depending on context). Default: Solid `#FF4D00` fill, `#000000` bold `Space Mono` typography, zero blur. Active hover state: Immediate invert to solid `#FFFFFF` fill with 2px solid `#FF4D00` border, shifting text to `#000000`.
- **Secondary Ghost Button:** Sharp 2px solid `#FFFFFF` border, solid `#000000` fill, `#FFFFFF` text. Hover: Immediate color swap to `#FFFFFF` solid fill with `#000000` text.
- **Destructive/Command Button:** 2px solid `#FF4D00`, text in `#FF4D00`. Hover fills `#FF4D00` with text turning `#000000`.

### Navigation & Toggles (Pill Controls)
- Segmented switches and view pickers must be encapsulated inside a dark 2px bordered pill container (`border-radius: 9999px`).
- Active items inside the switch trigger a solid `#FF4D00` pill indicator with crisp `#000000` typography. Inactive items display in `#FFFFFF` with transparent background.

### Chips & Badges
- Strict pill architecture (`border-radius: 9999px`), padding: 4px 12px.
- Built using `label-mono-sm`.
- Status configurations:
  - **Live / Operational:** 2px solid `#FF4D00`, background transparent, text `#FF4D00`, preceded by a 6px solid `#FF4D00` circular dot.
  - **Neutral / Dormant:** 2px solid `#FFFFFF`, text `#FFFFFF`.
  - **System Trace:** Solid `#1A1A1A` background with crisp white text.

### Input Fields
- Razor-sharp corners (`0px` radius) with a solid 2px `#FFFFFF` structural border on a `#000000` background.
- Label sits directly atop or inset-pinned to the top-left border line using uppercase `Space Mono` text.
- Focused state snaps the entire 2px border instantly to `#FF4D00`, accompanied by an immediate `4px 4px 0px 0px #FF4D00` hard brutalist shadow. Caret is styled solid `#FF4D00`.

### Checkboxes & Radio Buttons
- **Checkboxes:** Crisp 18x18px squares, 2px solid `#FFFFFF`, no radius. Checked state fills with `#FF4D00` displaying a solid `#000000` angled vector check.
- **Radio Buttons:** Outer 18x18px sharp square or circular pill ring with 2px `#FFFFFF` outline. Selected state inserts a centered, unblurred 8x8px `#FF4D00` core.

### Cards & Telemetry Blocks
- Enclosed with continuous 2px solid `#FFFFFF` or `#1A1A1A` perimeter lines.
- Card Headers: Separated by a horizontal 2px divider rule; header text styled in uppercase `Archivo Narrow` with accompanying system timestamp in `Space Mono` positioned flush-right.
- Content zone maintains zero internal corner radius and high data density.
