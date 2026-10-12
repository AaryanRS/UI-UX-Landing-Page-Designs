# Kai Rennard — Portfolio Experience

A cinematic, editorial web portfolio experience created for Formula Grand Prix driver **Kai Rennard** (Halden Motorsport #77). The design departs from traditional web component layouts, operating as a continuous art-directed editorial spread set within an atmospheric, floating canvas environment.

---

## 1. Project Overview & Architecture

### Concept & Philosophy
- **Art Direction**: Combines high-fashion magazine editorial layouts with high-performance motorsport telemetry aesthetics.
- **Continuous Surface**: Designed as a single, fluid art-directed experience rather than disconnected cards and generic sections.
- **Atmospheric Outer Viewport**: On desktop screens, the website surface is presented as a floating rounded container (`rounded-3xl` / `rounded-4xl`) set within a deep cyan-and-black atmospheric background featuring subtle diagonal racing speed streaks and ambient telemetry glow.

---

## 2. Visual Design System

### Color Palette
| Token | Hex Code | Purpose |
| :--- | :--- | :--- |
| **Cream / Off-White** | `#F1EFE9` | Primary hero background, editorial paper texture, high-contrast light space |
| **Dark Base** | `#071116` | Deep racing garage black, night track sections, archival gallery |
| **Near Black** | `#04090C` | Viewport outer background, cinematic vignettes, helmet backdrops |
| **Electric Turquoise** | `#19E5D0` | Signature brand accent, telemetry highlights, active indicators, CTA buttons |
| **Editorial Grey** | `#858585` | Subtle metadata, secondary timestamps, technical specifications |
| **Border / Rule Line** | `rgba(0, 0, 0, 0.08)` / `rgba(255, 255, 255, 0.12)` | Hairline dividers, technical telemetry grids, topographic contours |

### Topographic & Graphic Language
- **Contour / Topographic Lines**: Ultra-fine SVG vector strokes (`0.75px` to `1px`) mimicking track elevation maps, aerodynamic wind tunnel flowlines, and organic topographic contours.
- **Telemetry Grid & Markers**: Technical corner brackets (`+` markers, corner crosshairs, `// 2025` volume tags, circuit GPS coordinates).
- **Asymmetric Grid Composition**: Off-center hero staging, overlapping photographic cutouts, and generous negative space reminiscent of print publications (*L'Équipe Sport & Style*, *GQ Motorsport*, *The New Order*).

---

## 3. Typography & Type Scale

The typographic hierarchy relies on a pairing between high-contrast editorial serifs and ultra-clean modernist grotesk sans-serifs, accented by monospace telemetry tags.

### Typefaces Used
1. **Primary Editorial Grotesk (Sans)**:
   - Font Family: `Inter`, `-apple-system`, `BlinkMacSystemFont`, `"Helvetica Neue"`, sans-serif
   - Usage: Navigation bar, uppercase micro-labels, technical telemetry, data stats, section tags.
   - Styling: High tracking (`letter-spacing: 0.15em` to `0.3em`), ultra-fine weights (`font-medium`, `font-semibold`), uppercase transformation.

2. **Editorial Display Serif**:
   - Font Family: `Playfair Display`, `Cormorant Garamond`, `Canela`, serif
   - Usage: Hero narrative accents (*"CHASING"*, *"RESPECT"*, *"STORY"*), introspective driver quotes, and magazine headline callouts.
   - Styling: Italicized styling, tight line heights, dynamic size scaling against heavy uppercase grotesks.

3. **Heavy Motorsport Display (Impact Typography)**:
   - Font Family: `Inter` (Extra Bold / Black 900) or `Syne`
   - Usage: Viewport-dominant racing statements (`"CHASING THE APEX"`, `"NEVER LIFTING OFF THE THROTTLE"`).
   - Styling: Compact leading, negative letter-spacing on display scales (`tracking-tighter`), full horizontal viewport stretch.

4. **Telemetry Monospace**:
   - Font Family: `ui-monospace`, `SFMono-Regular`, `Menlo`, monospace
   - Usage: Lap times, grid positions, coordinate readings, volume tags (`GRID: #77`, `SEASON 2025 // VOL. 04`).

---

## 4. Key Interactive Components & Motion Design

1. **Floating Racing Helmet Overlay**:
   - High-fidelity carbon-fiber helmet cutout (`#19E5D0` visor/accents) floating dynamically in front of Kai's editorial portrait.
   - Smooth mouse parallax and CSS float kinetics simulating zero-gravity aerodynamic isolation.

2. **SVG Signature Stroke Draw**:
   - Vector signature progressively revealing via `stroke-dasharray` and `stroke-dashoffset` animation in vivid turquoise over dark editorial photography.

3. **Interactive ON TRACK / OFF TRACK Switcher**:
   - Editorial state machine that dynamically switches the page's photographic mood between aggressive track day imagery (Suzuka dusk race) and moody paddock/garage lifestyle portraits.

4. **Helmets Hall of Fame Archive**:
   - Asymmetric dark museum gallery showcasing bespoke aerodynamic lid specs and historic Grand Prix race helmets.
