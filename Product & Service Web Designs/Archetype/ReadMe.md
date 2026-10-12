# ARCHETYPE · Studio Landing Page

A brutalist, architectural editorial landing page for a monolithic stonework and terracotta sculpture studio. The page explores the intersection of tectonic materiality, physical calibration, and spatial permanence.

---

## 1. Project Overview & Narrative
- **Brand/Studio**: `ARCHETYPE` (Milan Studio 4, Via Privata Orobia 11, Milano).
- **Discipline**: Architectural stoneware cast through subtractive tectonic calibration, dry-stack mortise interlocks, and compressive dead-weight equilibrium.
- **Core Concept**: A signature split-wordmark hero where the studio mark (`ARCHE` / `TYPE.`) fractures along an axis of gravity on scroll while a high-key cut-out stoneware specimen rises through the rift.
- **Philosophy**: *Form exists as the equilibrium between compressive dead weight and planetary pull.* Every sculpture operates as an independent dry-stack puzzle without concealed rebar or synthetic adhesives.

---

## 2. Design System & Visual Language

### Palette
| Role | Hex / Value | Application |
|---|---|---|
| **Primary Ground** | `#E7E3DA` | Main page parchment / warm bone field |
| **Secondary Ground** | `#DCD7CB` | Hero backdrop & technical elevation background |
| **Primary Ink** | `#1A1917` | High-contrast body, titles, structural borders |
| **Secondary Ink** | `#4A4741` | Secondary headings, technical metadata labels |
| **Muted Tone** | `#6E6A61` | Hairline annotations, notes, fine copy |
| **Earth Pigment** | `#9B3418` | Single red-oxide accent: typographic italics, markers, crosshairs (never a fill) |
| **Hairlines / Rules** | `rgba(26, 25, 23, 0.16)` | Grid lines, table rules, dimension leaders |

### Typography
- **Display & Headings**: `'Instrument Serif'`, Roman & Italic
  - Letter spacing: `-0.015em` to `-0.02em`
  - Sizes: `clamp(30px, 4vw, 56px)` down to `clamp(18px, 1.8vw, 24px)`
  - Usage: All expressive titles. Italics are reserved strictly for phrases accentuated in the `#9B3418` oxide pigment.
  - Monumental Wordmark: `clamp(74px, 17.5vw, 258px)` at line-height `0.82`.
- **Data, Labels, Body & Schematics**: `'Azeret Mono'`, 400–600 weight
  - Uppercase labels: `10.5px – 12.5px` with wide letter-spacing (`0.15em – 0.17em`).
  - Sentence-case descriptions & body: `12.5px` with line-height `1.65`.
  - Usage: All factual data, dimensions, geodetic coordinates, formulas, and tabular matrices.

### Architectural Styling Rules
- **Border Radius**: `0px` universally across all elements, buttons, badges, and modals.
- **Elevation & Shadows**: Flat 2D rendering. Shadows are disallowed on all UI containers and exclusively reserved for the 3D cut-out artifact subject.
- **Fills**: Zero gradients; zero glassmorphism cards; zero solid pigment block fills. `#9B3418` functions purely as stroke, line, marker node, or text emphasis.

---

## 3. Structural Breakdown & Sections

1. **Fixed Navigation Bar (60px)**
   - Translucent bone ground with `14px` backdrop blur.
   - Serif wordmark `ARCHETYPE.` with pigment period.
   - Monospaced navigation links (`STUDIO`, `SPECIFICATION`, `PINNED STUDY`, `MATERIAL MATRIX`, `CATALOGUE`) with animated underline on hover.
   - Square high-contrast button `ENQUIRE →`.

2. **Hero: Split-Wordmark Tectonic Bracket**
   - Left column (within `44vw`): Monospaced eyebrow, main headline with italic oxide phrase, lede description, interactive CTA buttons, and bottom corner-pinned geodetic coordinate datums (`LAT 45.4642° N`, `LON 9.1900° E`, `TOLERANCE ±0.05 MM`).
   - Right bracket: Stacked wordmark `ARCHE` (z-index 25, above specimen) and `TYPE.` (z-index 10, below specimen).
   - Cut-out artifact (`Isolated studio cut-out sculpture...`) anchored in the rift at z-index 15.

3. **Section 02: Orthographic Drawing (1:5 True Scale)**
   - Left: Construction narrative and hairline-ruled specifications table (`BASE FOOTPRINT`, `VERTICAL ELEVATION`, `CYLINDER BORE`, `BLOCK INTERLOCK`, `FIRING CYCLE`).
   - Right: Real-scale SVG architectural orthographic elevation with center of gravity line, dimension leaders, datum levels, compression lap lines, and graphic scale bar.

4. **Section 03: Pinned Equilibrium Study**
   - Full-height stage modeling dynamic deflection along an arc of equilibrium.
   - Computes live physics:
     - Deflection angle: $\theta(s) = \theta_{\max} \cdot \sin(\pi s) \cdot \cos(0.5\pi s)$
     - Restoring moment: $M_R = W \cdot h \cdot \sin(\theta)$
     - Eccentricity: $e_x$
   - Real-time SVG trajectory arc with dynamic vertex marker and synchronized tabular readouts.

5. **Section 04: Material Matrix & Studio Philosophy**
   - 4 hairline rows detailing raw mineral compositions (`Terracotta Argilla`, `Travertino Romano`, `Basalt Dense Rock`, `Oxide Pigment #9B3418`).
   - Two-column prose pairing with verified Studio Accreditation metrics (annual tonnage, kiln fuel, zero sealant compliance).

6. **Section 05: Catalogue of Works (Registered Specimens & Editions)**
   - Monospaced table headers with hairline dividers.
   - Detailed specimen inventory (`ARC-24/09 Tectonic Totem VII`, `ARC-24/06 Cantilever Column III`, `ARC-23/18 Stepped Arch Vessel`, etc.).
   - Interactive row states with hover translation and status tags.

7. **Epilogue & Cropped Bookend Wordmark**
   - Commissioning inquiry block with action triggers (`INITIATE STUDIO COMMISSION`, `DOWNLOAD CATALOGUE`).
   - Giant bottom wordmark `ARCHETYPE.` at `clamp(80px, 20vw, 300px)` shifted down `0.17em` to be cropped cleanly by the bottom page margin.
   - Persistent live coordinate HUD tracking cursor movement.

---

## 4. Key Motion & Interaction Principles
- **Scroll Tectonic Separation**: `ARCHE` translates upward/leftward while `TYPE.` translates downward/rightward on scroll; the specimen ascends dynamically.
- **Coordinate Tracking**: Live canvas inspection HUD displaying active pointer X/Y coordinates in millisecond response.
- **Accessibility**: All kinetic translations and animations honor `prefers-reduced-motion: reduce`.
