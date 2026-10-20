# Experimental Editorial Product Designer Portfolio

An art-directed, typography-led, image-driven portfolio landing page created for a Senior / Principal UI/UX & Product Designer. Designed to break away from conventional SaaS templates, generic component libraries, and cookie-cutter agency websites in favor of an avant-garde digital exhibition aesthetic.

---

## 1. Project Overview & Intent

- **Project Type:** Portfolio Landing Page
- **Target Role:** Principal UI/UX & Digital Product Designer (Kaien Chen / KAIEN.studio)
- **Design Philosophy:** "Good design should feel obvious — even when the systemic process is not."
- **Visual Direction:** 
  - Editorial art direction inspired by high-fashion monographs and Swiss graphic design.
  - Asymmetric compositions with deliberate negative space and layered graphic planes.
  - Monumental display typography treated as architectural structure.
  - Gallery-grade project curation and cinematic visual rhythm.

---

## 2. Color System & Usage Rules

The palette employs confident, saturated blocks rather than timid pastel tints or generic gradient blobs:

| Token Name | Hex Code | Primary Role & Behavior |
| :--- | :--- | :--- |
| **Warm White** | `#F7F5EF` | Primary page canvas, negative breathing space, editorial column backdrops. |
| **Deep Black** | `#111111` | Primary text, 1px/2px technical grid rules, structural frames, dark manifesto section. |
| **Chartreuse** | `#D8FF3E` | Primary electric accent, active indicators, interactive CTA buttons, statement section backdrop. |
| **Lavender** | `#BFA7FF` | Large visual fields, Featured Case Study backdrop, offset image underlays, hover backplates. |
| **Tomato Red** | `#FF5B4D` | Focal attention moments, secondary CTA offset shadows, coordinate markers, geometric accents. |

---

## 3. Typographic Hierarchy

Typography is treated as a sculptural graphic object rather than mere copy inside cards:

- **Display Headline Font:** `Syne` (Weights: 700 Bold, 800 Extra Bold)
  - *Usage:* Hero title (`clamp(86px, 11vw, 170px)`), section headers (`56px–110px`), statement callouts.
  - *Tracking:* Controlled negative kerning (`-0.05em` to `-0.06em`) with tight line-height (`0.85–0.92`).
- **Body & Interface Font:** `Inter` (Weights: 400 Regular, 500 Medium, 600 SemiBold)
  - *Usage:* Navigation labels, case study narratives, capabilities descriptions, buttons.
  - *Tracking:* Generous reading line-height (`1.5–1.6`) with crisp legibility.
- **Editorial Accent Font:** `Instrument Serif` (Italic)
  - *Usage:* Used with strict restraint for selective italicized phrases and typographic tension (e.g. *systemic*, *delightfully*).

---

## 4. Architectural Layout & Sections

1. **Fixed Editorial Header:**
   - Wordmark `KAIEN.studio` with geometric accent markers.
   - Centered uppercase discipline taxonomy (`PRODUCT / UI / UX DESIGN`).
   - Editorial navigation (`WORK`, `ABOUT`, `CONTACT`) with chartreuse indicator states.
2. **Hero Exhibition (100svh):**
   - Monumental asymmetric typography: `I DESIGN DIGITAL EXPERIENCES`.
   - Underlaid chartreuse color plane and editorial studio portrait.
   - Coordinate measuring rules (`LAT. 52.5200° N`, `LON. 13.4050° E`).
   - Tactile CTA button with Tomato Red offset hover layer.
3. **Section 01 — Selected Work:**
   - Rejection of the standard 3-column card grid in favor of alternating scale:
     - *Project 01 (Aura OS):* 16:10 left-aligned display with lavender shadow plate.
     - *Project 02 (Fluent / 09):* 4:5 vertical mobile editorial spread with chartreuse framing.
     - *Project 03 (Chrono Console):* Full-width hardware + UI telemetry console.
4. **Section 02 — Featured Deep-Dive Case Study:**
   - Full lavender field backdrop (`#BFA7FF`) establishing section contrast.
   - Dual-column breakdown: Role specification, latency metrics, and layered UI telemetry.
5. **Section 03 — Design Philosophy Manifesto:**
   - Deep obsidian field (`#111111`) with monumental Warm White typography.
   - Three core principles: *Reduction as Force*, *Axial Rigidity*, and *Physical Feedback*.
6. **Section 04 — Capabilities:**
   - Full-width horizontal rows separated by 1px black structural borders.
   - Micro-interactions revealing category classifications and hover arrow indicators.
7. **Section 05 — About & Practice:**
   - Asymmetric two-column composition with studio portraiture overlapping tomato red blocks.
   - Practice history (`Independent`, `Summit AI`, `Studio Mono`).
8. **Section 06 — Call to Action Statement:**
   - High-voltage Chartreuse canvas (`#D8FF3E`).
   - Oversized text: `LET'S MAKE SOMETHING PEOPLE REMEMBER.`
   - Sharp rectangular primary action button with deep black fill.
9. **Editorial Footer:**
   - Direct correspondence line, time-zone coordinates, and back-to-top navigation.

---

## 5. Craft & Micro-Interactions

- **Borders & Radii:** Geometric precision (0px to 4px). Avoids ballooned, bubbly border radii.
- **Shadows:** No generic Gaussian blurs; uses hard offset 1-bit style layered slabs.
- **Hover Transitions:** 300ms–500ms easing (`cubic-bezier(0.22, 1, 0.36, 1)`) with subtle vertical coordinate displacement.


---
name: Kinetic Editorial
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#454934'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#757962'
  outline-variant: '#c5c9ae'
  surface-tint: '#536600'
  primary: '#536600'
  on-primary: '#ffffff'
  primary-container: '#d8ff3e'
  on-primary-container: '#607400'
  inverse-primary: '#b0d500'
  secondary: '#6750a1'
  on-secondary: '#ffffff'
  secondary-container: '#bea6fe'
  on-secondary-container: '#4d3786'
  tertiary: '#b5251f'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffebe8'
  on-tertiary-container: '#c9342b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cbf230'
  primary-fixed-dim: '#b0d500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#cfbcff'
  on-secondary-fixed: '#22025b'
  on-secondary-fixed-variant: '#4e3887'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4aa'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#92050a'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 140px
    fontWeight: '800'
    lineHeight: 126px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.03em
  display-editorial:
    fontFamily: Newsreader
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-editorial-mobile:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 62px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Syne
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-editorial:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0em
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
    letterSpacing: 0em
  label-code:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
  label-action:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
  space-2xl: 5rem
  space-3xl: 8rem
---

## Brand & Style

This design system expresses the tension between rigid Swiss modernist architecture and radical digital editorial design. It positions the product designer not merely as an interface technician, but as an author, curator, and systems architect. 

### Brand Personality & Emotional Impact
- **Hyper-Articulate & Uncompromising:** Clean structural axes clash directly with oversized, audacious typography. The experience feels deliberate, bespoke, and authoritative.
- **Museum Installation meets Print Broadside:** Navigating the interface simulates moving through an art-directed gallery catalog. Visual planes slip behind sharp viewports; high-energy color slabs frame nuanced case studies.
- **Audience:** Design leadership, venture-backed founders, creative directors, and cross-disciplinary curators seeking rare, world-class product craftsmanship.

### Visual Style
- **Movement:** Neo-Brutalist High Editorial.
- **Techniques:** Architectural hairline grids (1px solid black borders), technical coordinate markers (e.g., `[ 01 // ARCHIVE ]`), layered planar color blocking, and dramatic scale contrasts between massive headline type and ultra-rational UI typography.

## Colors

The palette avoids safe corporate pastels in favor of high-chroma editorial impact balanced by warm archival paper neutrals.

### Palette Architecture
- **Primary Accent (`#D8FF3E` — Chartreuse):** Used for focal points, interaction targets, status chips, primary interactive states, and active category tags. It acts as a digital highlighter over stark structural layouts.
- **Secondary Field (`#BFA7FF` — Lavender):** Used for planar backplates behind project imagery, oversized decorative canvas shapes, and secondary section backgrounds to break layout monotony.
- **Tertiary Accent (`#FF5B4D` — Tomato Red):** Reserved for urgent editorial interventions, interactive hover strikes, project index numbering, and high-impact CTA points.
- **Structural Neutral (`#111111` — Ink Black):** All structural framing rules (1px–2px), dense typography, hairline borders, and primary navigation elements.
- **Canvas (`#F7F5EF` — Warm White):** The universal background surface simulating uncoated tactile archival paper. Prevents the harsh optical fatigue of raw `#FFFFFF`.

### Surface & Border Rules
- Background canvas: `#F7F5EF`
- Card surface (flat): `#FFFFFF` or `#F7F5EF`
- Contrast color planes: `#BFA7FF` and `#D8FF3E`
- Structural outlines & split rules: `#111111` (100% opacity for primary grids, 15% opacity for sub-measurement guidelines)

## Typography

The typographic hierarchy orchestrates a high-tension dynamic between three distinct typographic voices:

1. **Display Primary (`Syne`):** Unconventional, geometric, unapologetically bold. Used for main statement titles, project names, index headings, and kinetic display banners. Clamped dynamically for extreme scale without breaking line balance.
2. **Editorial Counterpoint (`Newsreader` / Serif Accent):** Fluid, literary, and italicized. Used strictly for selective phrases, footnotes, pulls, and emotional narrative interludes inside hero statements.
3. **Information Spine (`Inter`):** Modernist, razor-sharp, hyper-legible. Handles all case study body text, navigation bars, metadata labels, coordinates, and system metrics.

### Composition Guidelines
- Never set full paragraphs in `Syne`.
- Use all-caps with generous letter-spacing (`0.08em`) for `label-code` metadata (e.g., `FIG 04. — SYSTEM SPECS`).
- Integrate `display-editorial` inline within `display-hero` sentences to create rhythm shifts (e.g., Syne: "ENGINEERING" + Newsreader Italic: "*poetic interfaces*").

## Layout & Spacing

The layout is built upon an **Asymmetric Architectural Fluid Grid** enclosed by full-bleed perimeter frames.

### Grid Framework
- **Desktop (1200px+):** 12-column asymmetric grid. Columns break across split ratios (e.g., 7:5 or 4:8) with `2.5rem` gutters and `3.5rem` outer canvas boundaries. Sections are demarcated by visible `1px solid #111111` lines that run edge-to-edge.
- **Tablet (768px – 1199px):** 8-column layout with `2rem` gutters and `2rem` canvas margins.
- **Mobile (< 768px):** 4-column layout with `1.5rem` gutters and `1.25rem` canvas margins. Structural grids collapse vertically into stacked single-column boxes lined with hairline dividers.

### Layout Principles
- **Coordinate Registration:** Key grid intersections feature bracket notations, registration crosses (`+`), and catalog indices (e.g., `POS: 04/12`).
- **Offset Overlaps:** Images do not sit passively in standard cards; they bleed through their bounding boxes into adjacent lavender (`#BFA7FF`) or chartreuse (`#D8FF3E`) color planes by `space-lg` to `space-xl` offsets.

## Elevation & Depth

This design system deliberately rejects blurred drop shadows, ambient diffuse glow, and simulated light sources. Depth is mechanical, physical, and graphic.

### Mechanical Depth Rules
- **Zero Ambient Shadows:** `box-shadow: none` is the default standard for all baseline cards, surfaces, and dialogs.
- **Solid Offset Planes (Hard Cast):** Elevation is achieved exclusively via hard, non-blurred vector drops: `box-shadow: 4px 4px 0px #111111`. For high-emphasis floating objects, the offset expands to `8px 8px 0px #111111`.
- **Structural Outlines:** Every container tier is bound by a crisp `1px` or `2px solid #111111` structural border.
- **Z-Index Layering:** Depth is communicated by planar overlap: a `#F7F5EF` canvas tier, topped by a solid `#BFA7FF` offset backdrop, capped by the primary card container with a `1px` stroke and hard shadow.

## Shapes

The shape vocabulary is strictly **architectural, sharp, and planar**.

### Shape Standard
- **Level 0 (Sharp):** All standard containers, buttons, tags, dialogs, media viewports, and color slabs utilize `border-radius: 0px`. 
- **Exception Context:** Selected inline pill tags or micro status-dots may utilize full circular radii (`border-radius: 9999px`) to create an immediate graphic contrast against the dominant brutalist square grid.
- **Rules & Dividers:** Sharp corners extend to horizontal and vertical rules. Borders join at sharp 90-degree intersections without corner smoothing.

## Components

### Buttons
- **Primary Button:** Rectangular, sharp (`0px`). Background `#D8FF3E`, text `#111111`, border `1.5px solid #111111`. Hard drop shadow `3px 3px 0px #111111`. On hover: translate `2px 2px`, shadow reduces to `1px 1px 0px #111111`. Typography: `label-action`.
- **Secondary / Ghost Button:** Background transparent, text `#111111`, border `1.5px solid #111111`. On hover: background fills with `#BFA7FF` or `#111111` (with text inverted to `#F7F5EF`).
- **Accent Action (Editorial CTA):** Background `#FF5B4D`, text `#F7F5EF`, border `1.5px solid #111111`, shadow `4px 4px 0px #111111`.

### Chips & Metadata Tags
- **Technical Tag:** Background `#F7F5EF`, border `1px solid #111111`, padding `4px 10px`, typography `label-code`. Preceded by an index symbol (e.g., `// 01 ARCHITECTURE`).
- **Active Filter Chip:** Background `#D8FF3E`, border `1px solid #111111`, text `#111111`, shadow `2px 2px 0px #111111`.

### Case Study Cards
- **Structure:** Framed with `1.5px solid #111111` over background `#FFFFFF`. Imagery is locked in a sharp rectangular container.
- **Plates & Backing:** Projects can feature an asymmetric color backplate (`#BFA7FF`) protruding `16px` outside the upper-right or lower-left corner.
- **Metadata Header:** Top panel separated by a hairline `1px solid #111111` border displaying project year, client, and deliverable categories in `label-code`.

### Lists & Index Rows
- **Editorial Archive List:** Single horizontal rows separated by `1px solid #111111` rules.
- **Hover Behavior:** Hovering over an item reveals an instant preview card and floods the row background with `#D8FF3E`, shifting the index number to `#FF5B4D`.
- **Typography:** Row titles use `headline-sm` in `Syne`, counter-balanced by delivery year in `Newsreader` italic.

### Form Inputs & Text Fields
- **Input Canvas:** Background `#FFFFFF`, border `1.5px solid #111111`, zero radius, padding `14px 16px`. Typography `body-md`.
- **Focus State:** Background remains `#FFFFFF`, border thickens to `2px solid #111111`, shadow jumps to `3px 3px 0px #D8FF3E`. Outline is disabled.
- **Labels:** Set in `label-code` positioned outside the field, accompanied by an alphanumeric index (e.g., `[ 01 ] INPUT QUERY`).

### Checkboxes & Radios
- **Checkbox:** `18px x 18px` sharp square, `1.5px solid #111111`, background `#F7F5EF`. When checked: fill becomes `#D8FF3E` with a solid black diagonal slash (`/`) or `X` mark.
- **Radio Button:** `18px x 18px` square container with an inner solid square (`8px x 8px`) in `#111111` on active state.

### Specialized Components
- **Editorial Marquee:** Edge-to-edge ticker framed top and bottom by `1px solid #111111`, background `#D8FF3E` or `#111111`, cycling massive bold typography in `Syne`.
- **Coordinate Anchor:** Floating corner metadata badge fixed to viewport edges (e.g., `LAT / LON` or `VIEWPORT: 1440PX // STATUS: AVAILABLE`) set in `label-code`.
