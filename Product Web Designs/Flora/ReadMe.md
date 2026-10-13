# Flora — Heirloom Seed House Landing Page

## Project Brief & Overview
Flora (operating as Fallow Row Seed House) is a scroll-choreographed, warm-print editorial e-commerce landing page. The narrative thread guides the visitor from agricultural variety provenance down to the physical, verified seed packet artifact.

---

## Design System & Visual Register

### 1. Aesthetic Direction
- **Warm Print Editorial**: Inspired by vintage horticultural ledgers, Swiss modernist typesetting, archival specimen records, and agrarian taxonomy.
- **Substrate & Form**: Zero border radii across all elements (`border-radius: 0`), 1.5px solid ink borders on paper substrate elements, and 1px hairlines (`rgba(23, 23, 23, 0.16)` and `0.08`).
- **Texture & Canvas**: No external photographic assets or icon fonts. All graphic plates (tilled soil field, geometric specimen seeds, topographical contour curves) are generated programmatically via HTML5 Canvas.

### 2. Color Palette
- **Cream Ground**: `#E7E2D8` — Primary paper background tone across stages 2, 3, 5, price table, and FAQ.
- **Dark Loam**: `#241A12` — Heavy contrast ground used for stage 1 (Hero), stage 4 (The Physical Artifact), and the archival footer.
- **Deep Ink**: `#171717` — Primary typographic ink color, card borders, and primary rules.
- **Hot Red**: `#EF493C` — Rationed accent color used exclusively for functional marks: unit pricing, progress meters, live status cues, packet data stamps, and wordmark highlight.
- **Deep Red**: `#B92725` — Secondary accent tone for depth and high-contrast alert states.
- **Off-White Paper Stock**: `#FFFDF8` — Substrate fill for cards, specimen plates, and seed packet artifacts.
- **Hairlines**: `rgba(23, 23, 23, 0.16)` and `rgba(23, 23, 23, 0.08)`.
- **Muted Inks**: `rgba(23, 23, 23, 0.56)` and `rgba(23, 23, 23, 0.34)`.

### 3. Typography & Hierarchy
- **Display Typeface**: **Anton**
  - Use: Display headlines, hero poster lockup, section titles, card specimen names.
  - Characteristics: Uppercase, letter-spacing `-0.02em` to `-0.045em`, line-height `0.86`.
- **Body & Editorial Typeface**: **Inter**
  - Weights: 400 (Regular), 500 (Medium), 700 (Bold).
  - Use: Narrative copy, manifesto lede, product notes, FAQ answers, legal copy.
- **Metadata, Monospace & Technical Typeface**: **Martian Mono**
  - Size: Fixed at 10.5px.
  - Letter-spacing: `+0.18em` (wide-tracked uppercase).
  - Use: Every label, lot number, germination assay result, coordinate, price tag, table row code, and status indicator.

---

## Architectural & Motion Blueprint

### Pinned Stages (Driven by Single Scroll Handler via `:root` CSS Custom Properties)

1. **Stage 1: Hero Poster (280svh, Dark Loam `#241A12`)**
   - Interactive full-bleed HTML5 canvas drawing tilled-soil stroke matrices drifting on harmonic sines (5%–19% alpha).
   - Dynamic poster lockup calculated from line character count: `min(vw, calc(92vw / (chars * 0.44)))`.
   - Driven by 3 independent CSS variables: `--hero-type-y` (0px to -90px), `--hero-type-scale` (1.0 to 0.74), `--hero-type-alpha` (1.0 to 0.0).

2. **Stage 2: Manifesto Clip-Wipe (260svh, Cream `#E7E2D8`)**
   - Single thesis statement rendered in 34% muted ink.
   - Exact duplicate overlay rendered in 100% ink wiped from bottom to top via:
     `clip-path: inset(calc(100% - var(--manifesto-wipe)) 0 0)`.
   - Simultaneous micro-scaling on `--manifesto-scale` (1.0 to 1.05).

3. **Stage 3: Horizontal Specimen Rail (340svh, Cream `#E7E2D8`)**
   - 6 non-wrapping botanical variety cards (`clamp(230px, 26vw, 330px)` width) with generative 3/4 canvas seed plates.
   - Rail translated sideways by exact measured overflow: `calc(-1 * progress * overflowWidth)`.
   - Running hairline progress track with hot red indicator bar.
   - Accessible graceful fallback: wraps and centers under `prefers-reduced-motion`.

4. **Stage 4: The Physical Artifact (420svh, Dark Loam `#241A12`)**
   - Two-column layout: sliding narrative notes on left, physical seed packet on right.
   - Packet driven by 6 variables: `--packet-alpha`, `--packet-enter`, `--packet-scale`, `--packet-cut`, `--packet-meter`, and `--packet-copy-x`.
   - Discontinuous phase indexing triggering: cumulative cue lights, live typewriter status bar, dynamic data population (Lot No., Germination test status transitioning from 'Pending' to '94% ISTA', sowing window), and ending with a dashed tear-strip perforation opening.

5. **Stage 5: Parallax Season Band (300svh, Cream `#E7E2D8`)**
   - 22-line stacked topographical contour canvas undergoing vertical parallax (`--season-y`: -4% to +4%) and scaling (`--season-scale`: 1.10 to 1.055), every 5th line accented in hot red.
   - 3 seasonal propagation chapters swapping visibility sequentially via `floor(progress * 3)`.

### Post-Pin Sections & Micro-Motion System
- **Ruled Commercial Price Sheet**: Monospace tabular specification of packaging formats, gram counts, minimum orders, and direct unit prices.
- **Native FAQ Accordion**: Unstyled semantic `<details>` and `<summary>` tags styled with 1.5px ink hairlines, mono counters, and custom animated carets.
- **Archival Footer**: Dark loam ground, provenance credentials, newsletter dispatch form, and dual legal metadata columns.
- **200-Atom Motion Budget**: Per-word inline spans staggered at 38ms intervals, and elements with `data-rev` staggered between 40ms and 100ms on `IntersectionObserver` entry.
