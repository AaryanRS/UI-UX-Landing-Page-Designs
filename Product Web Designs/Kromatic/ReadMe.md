# KROMATIK — Project Brief & Visual Design System

## 1. Project Brief & Overview
**KROMATIK** is a high-craft product landing page dedicated to an artisanal, hand-manufactured horological balance and escapement mechanism (Caliber K.01). The digital experience mirrors the uncompromising discipline of haute horlogerie: precision-engineered, unadorned, mathematically grounded, and free of artificial consumer marketing tropes (no fake quotes, no generic badges, no decorative gradients).

The signature experience centers around mechanical physical reality:
- **Horizontal Wordmark Interruption**: The `KROMATIK` brand wordmark is split physically across a single baseline. The mechanical escapement sits right in the gap, weaving through the letterforms (left half `KROM` behind the object, right half `ATIK` in front). As the user scrolls, the product rotates along its escapement axis while the wordmark halves part laterally.
- **Computed Oscillation Harmonic**: A pinned study section calculating real kinematics from the caliber's verified frequency (3.00 Hz / 21,600 VPH, 290° amplitude sweep, 72-hour power reserve). The oscillation angle, damping envelope curve, accumulated beats, and instantaneous torque are directly tied to scroll physics rather than an artificial timer loop.

---

## 2. Visual Style & Philosophy
- **Aesthetic**: Instrument-Grade Dark Craft / Haute Horlogerie Technical Metrology.
- **Form Language**: Sharp geometry with zero border-radius (`border-radius: 0px` globally). Every element — buttons, indicators, reticles, tables, and borders — maintains pure orthogonal edges.
- **Ornamentation**: Strictly forbidden. No gradients, glow overlays, bento grids, rounded card containers, or drop shadows (except soft ambient occlusion on the product cut-out).

---

## 3. Color Palette & Roles

| Role | Hex / RGBA | Usage Description |
| :--- | :--- | :--- |
| **Ground (Primary)** | `#09090B` | Main page background; velvety matte obsidian tone |
| **Secondary Ground** | `#101013` | Hero backdrop & table striping for subtle tonal separation |
| **Surface / Card Ground**| `#161619` | Elevated panels, inspect callouts, modal overlays |
| **Ink (Primary)** | `#EDE8DF` | Warm bone white for titles, values, primary display copy |
| **Secondary Ink** | `#9E988E` | Subtitles, labels, descriptions, and structural tags |
| **Muted Ink** | `#615D56` | De-emphasized indices, timestamps, hairline markers |
| **Brass Accent** | `#C5A059` / `#D4AF37` | Champagne horological brass accent; used **only** for typographic emphasis, rules, reticle highlights, and active status indicators. Never as a filled background. |
| **Hairline Rules** | `rgba(237, 232, 223, 0.08)` | Clean 1px structural dividers framing rows and viewports |

---

## 4. Typography System

The design enforces a strict dual-font discipline: an ultra-condensed display typeface for all headlines and wordmarks, paired with an ultra-wide technical monospace for all data, copy, and figures.

### Headings & Wordmark: **Big Shoulders Display**
- **Classification**: Ultra-condensed display sans-serif
- **Weights**: `700` (Bold), `800` (ExtraBold), `900` (Black)
- **Casing**: Uppercase throughout (`text-transform: uppercase`)
- **Letter Spacing**: Normal to tight (`-0.02em` to `0.02em`)
- **Line Heights**: Compact line-height rhythm (`0.74` – `0.96`)
- **Scale**:
  - Hero Brand Wordmark: `clamp(96px, 25vw, 370px)` at `line-height: 0.74` (`KROM` / `ATIK`)
  - Section Headlines: `clamp(32px, 4.5vw, 68px)`
  - Subheads & Table Names: `clamp(18px, 2vw, 26px)`
  - Footer Cropped Wordmark: `clamp(84px, 22vw, 340px)`

### Labels, Metrology & Body: **Martian Mono**
- **Classification**: Wide technical monospace
- **Weights**: `400` (Regular), `500` (Medium), `600` (SemiBold)
- **Labels & Micro-data**: `9.5px` – `11px`, `letter-spacing: 0.08em` – `0.14em`, uppercase
- **Body & Technical Prose**: `11px`, `line-height: 1.85` – `1.90`, sentence case or uppercase tags
- **Tabular Figures**: Standard `font-variant-numeric: tabular-nums` for rock-solid vertical alignment across metric tables.

---

## 5. Layout Architecture & Sections

1. **Precision Header Navigation (`60px`)**:
   - Translucent obsidian ground with backdrop blur (`20px`) and bottom hairline border.
   - Monospaced navigation links (`9.5px`) with champagne brass hover underline.
   - `KROMATIK.` wordmark at `22px` with brass trailing period and acquisition action button (`border-radius: 0`).

2. **Hero Section (The Signature Wordmark Bracket)**:
   - Full viewport stage with overflow clipped.
   - Copy stack pinned to the left (`<= 44vw`): monospaced index tags, three-line display headline with brass highlight, monospaced lede.
   - Top-right instrument datum sheet with certified chronometer status indicators.
   - Central horological balance assembly rotating on scroll while the horizontal `KROM` and `ATIK` wordmark segments separate outward.

3. **Pinned Oscillation Harmonic**:
   - Dynamic SVG balance wheel arc with instantaneous needle deflection.
   - Real-time kinematic mathematical model computing torque, damping curves, and frequency pulses (21,600 VPH / 3.00 Hz).

4. **Architectural Specification (Dual-Column)**:
   - Technical prose against hairline-divided metrology rows with right-aligned tabular metrics.
   - High-magnification 100% optical macro inspection frame with laser-interferometry reticle markings.

5. **Seven Stages of Mechanical Refinement**:
   - Single-column sequential manufacture ledger detailing billet cutting, anglase, tooth truing, hairspring pinning, and observatory testing with verified craft hours.

6. **Limited Horological Registry & Commissioning**:
   - Tabular edition registry (Titanium Gunmetal, Anthracite DLC, Raw Brass Atelier) displaying chassis alloys, balance rim specs, calibration runs, and acquisition statuses.
   - Terminal commissioning CTA section and oversized bottom-cropped `KROMATIK` signature wordmark anchored at `-0.16em`.
