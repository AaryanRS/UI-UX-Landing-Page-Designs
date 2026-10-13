# Parker — Maker's Landing Page

## Project Brief
A maker's landing page designed for **Parker**, engineered around a single travelling drafting fountain pen machined from bead-blasted Grade 5 titanium and blackened brass. Rather than repeating static product cutouts across sections, the page employs a single fixed product element keyframed across scroll positions. In addition, an interactive autonomous drafting demonstration allows the page to directly perform the precision instrument's craft, complemented by a spread wordmark anchored to the base of the page.

---

## Design System & Aesthetics

### Visual Identity & Philosophy
- **Style**: Warm artisan stationery and precision engineering benchmark.
- **Surface Texture**: Tactile warm paper ground reminiscent of Arches aquarelle hot-pressed vellum and Japanese ledger paper.
- **Geometry**: Strict `0px` border-radius across all buttons, panels, tags, and measurement strips. No modern gradients, glows, or bento grids.

### Color Palette
- **Ground (Primary)**: `#EFE9DD` (Warm paper ground)
- **Secondary Ground**: `#E5DED0` (Recessed paper tone for hero / contrast zones)
- **Primary Ink**: `#141C2B` (Deep near-black ink for headlines, structural borders, and copy)
- **Secondary Ink**: `#4A5364` (Secondary technical copy and metadata)
- **Muted Ink**: `#767E8C` (De-emphasized labels, footnotes, timestamps)
- **Accent Ink Blue**: `#2C4A8F` (Precision ink blue — strictly reserved for emphasized typographic italics, rules, and drawn line paths; never used as a solid fill)
- **Hairlines**: `rgba(20, 28, 43, 0.16)` (Micro-metric technical divider lines)

### Typography Hierarchy
- **Display & Headings**:
  - **Family**: `Newsreader` (High-contrast transitional serif)
  - **Weight**: 400–600
  - **Tracking**: `-0.02em`
  - **Italic Rule**: Specific emphasized phrases in headings are styled in `Newsreader Italic` set to Ink Blue (`#2C4A8F`).
- **Technical Labels, Specs & Body**:
  - **Family**: `Courier Prime` (Monospaced typewriter font)
  - **Size**: 11px – 12px
  - **Tracking**: `0.07em` – `0.10em` (Uppercase letter-spaced)
  - **Line Height**: `~1.9` for optimal technical legibility.

---

## Page Architecture & Layout

1. **Fixed Precision Navigation** (58px):
   - Translucent paper ground with `12px` backdrop blur and hairline divider.
   - Serif wordmark `Parker.` with accent blue trailing period.
   - Uppercase monospaced navigation items with accent hover transitions.
   - Square action button (`ACQUIRE SPECIMEN`).

2. **Hero Section**:
   - Monospaced technical kicker.
   - Fluid typography headline (`clamp(32px, 4.6vw, 68px)`) with italicized accent phrase.
   - Twin zero-radius action buttons (`INSPECT DEMONSTRATION`, `FULL TOLERANCES`).
   - Hairline-topped bottom specification ticker (`Dry Mass: 42.80 g`, `Barrel Runout: ≤ 0.003 mm`, etc.).
   - Letter-by-letter spread wordmark across the baseline.

3. **01 / The Mechanics of Capillary Balance (Argument)**:
   - Two-column technical breakdown comparing mass-produced plastic feeds with sixty-four sub-millimeter natural hard ebonite fins.
   - Calibrated measurement tabular data (`Geometry: 11.20 mm`, `Cap Seal: 1.25 Turns`, `Tension Bias: 2.4 N`).

4. **02 / Autonomous Line Demonstration**:
   - Interactive calibrated drafting bed demonstrating line continuity without railroading.
   - Nib width variant selector (`EF / 0.32 mm`, `F / 0.50 mm`, `M / 0.75 mm`, `1.1 Stub`) with `aria-pressed` states.
   - Real-time SVG path redrawing with dynamic specification updates below.

5. **03 / Metallurgy & Substrates (Material Specs)**:
   - Specification rows for Titanium Ti-6Al-4V, Blackened C36000 Brass, Natural Nikko Grade A Ebonite, and Ruthenium-tipped 18k nib.

6. **04 / Caliber & Benchmarks (Inspection Data)**:
   - Empirical tolerance measurements covering length capped (138.50 mm), grip diameter, un-capped balance mass, and reservoir capacity.

7. **05 / Commissioning & Close**:
   - Final purchase callout, lathe shop coordinates (`45° 26' N, 9° 11' E`), and baseline cropped brand wordmark.

---

## Motion Models & Animations

### 1. The Travelling Product
- **Fixed Coordination**: Single cutout of the precision titanium instrument positioned as `position: fixed`.
- **Scroll Interpolation**: Smoothly keyframed along viewport coordinates (`vw`/`vh`), applying proportional translation, rotation angle (from 25° down to 10° and 0°), and scale adjustments.
- **Blend Mode**: Uses `mix-blend-mode: multiply` on the isolated studio shot to merge seamlessly into warm paper tones without harsh box boundaries.
- **Dismissal**: Smoothly fades out and applies `visibility: hidden` once past the materials section to prevent blocking pointer events.
- **Accessibility**: Automatically hidden when `prefers-reduced-motion` is active.

### 2. Autonomous SVG Self-Drawing Path
- Measures dynamic SVG curve length via `getTotalLength()`.
- Initializes `strokeDasharray` and `strokeDashoffset` to total length, smoothly animating offset to zero upon trigger.
- Synchronized with nib selector controls to adjust stroke weight and amplitude on selection.

### 3. Spread Wordmark Mechanics
- Letterforms (`P A R K E R`) configured in a flex row spanning `justify-content: space-between`.
- Translates downward to crop baselines against the frame.
- Expands dynamically outwards from center upon initial viewport scroll.
