# RAYMOND — Abstract Artist Editorial Portfolio

## 1. Project Brief & Overview

**Subject / Identity:** Raymond — Contemporary Abstract Painter & Visual Researcher  
**Concept:** A museum-grade, physical editorial broadsheet newspaper digital portfolio.  
**Core Thesis:** Moving away from standard SaaS or agency portfolio grids toward an authentic, physical print publication experience. The website behaves as a single continuous art gazette / archival monograph being traversed through the viewport, featuring oversized Didot/Bodoni mastheads, hairline ink rules, delicate micro-metadata, and museum gallery photography.

---

## 2. Visual Design & Aesthetic System

### Design Philosophy
- **Physical Broadsheet Materiality:** The viewport acts as an archival viewing desk inspecting high-grade unbleached cotton rag paper (`#FFF8F0` / `#E7DFD0` / `#EFE8DC`).
- **Editorial Newspaper Architecture:** Strict 12-column journalistic grid, visible 1px ink rule boundaries (`#26221F`), folio headers, dispatch volumes, price stamps, and colophon blocks.
- **Asymmetrical Art Spreads:** Eliminates generic floating card boxes, rounded corners, drop shadows, and pill buttons. Artworks are presented directly on the paper canvas with archival catalogue codes, dimensions, and medium specifications.
- **Extreme Contrast Hierarchy:** Juxtaposition of monumental display headlines (8vw–14vw) against ultra-compact, high-density micro-metadata (8px–11px, tracked out).

---

## 3. Color Palette & Ink Specifications

| Role | Color Hex | CSS / Token | Description & Usage |
| :--- | :--- | :--- | :--- |
| **Primary Paper Surface** | `#FFF8F0` / `#E7DFD0` | `surface` / `paper-base` | Warm unbleached rag paper canvas |
| **Secondary Paper Layer** | `#EFE8DC` / `#FBF3E3` | `surface-container-low` | Archival tinted inset panels & essays |
| **Deep Ink / Typography** | `#111111` | `on-surface` | Primary typographic ink for headlines and masthead |
| **Editorial Body Ink** | `#35312D` | `on-surface-variant` | High-legibility editorial dispatch and critique text |
| **Muted Metadata** | `#746E66` | `outline` | Catalogue serials, dimensions, timestamps, folio data |
| **Warm Editorial Accent** | `#A55F49` / `#9A604C` | `terracotta` / `rust` | Pigment callouts, alert ribbons, new acquisition tags |
| **Hairline Ink Divider** | `rgba(38, 34, 31, 0.25)` | `border-ink` | 1px newspaper column and row separator rules |
| **Charcoal Monolith** | `#1A1817` | `inverse-surface` | Used in the "FORM. COLOR. EMOTION." full-bleed poster block |

---

## 4. Typography & Font Hierarchy

### 1. Primary Display & Mastheads
- **Typeface:** `Bodoni Moda` / `Didot` (Editorial Serif)
- **Weights:** Regular (400), Medium (500), Bold (700, 900)
- **Styling:** High vertical contrast, razor-thin hairlines, dramatic uppercase tracking (`letter-spacing: -0.02em` to `-0.04em`), ultra-tight line height (`leading-none` / `0.85–0.95`).
- **Scale:**
  - Giant Masthead (`RAYMOND`): `11vw` – `13.5vw`
  - Statement Headlines (`ABSTRACT ARTIST!`, `ALL PAINTINGS!`): `4.5rem` – `7rem`
  - Section Banners (`FORM. COLOR. EMOTION.`): `5vw` – `8vw`

### 2. Editorial Essay & Critic Body
- **Typeface:** `Newsreader` / `Cormorant Garamond` / `Bodoni Moda` (Italic & Roman)
- **Weights:** Regular (400), Italic (400i)
- **Usage:** Long-form curatorial critiques, drop caps, testimonial citations, and artist manifesto copy.

### 3. Micro-Metadata, Navigation & Archival Labels
- **Typeface:** `Inter` / `Helvetica Neue` / `General Sans` (Technical Sans)
- **Weights:** Regular (400), Medium (500), Bold (700)
- **Styling:** All-caps, wide letter spacing (`letter-spacing: 0.12em` to `0.2em`), micro size (`0.65rem` – `0.75rem` / `10px`–`11px`).
- **Usage:** Folio coordinates, dimension readouts (`310 × 220 CM`), catalogue numbers (`RM-2026-04`), exhibition indices.

---

## 5. Layout & Structural Anatomy

1. **Physical Broadsheet Header & Utility Bar:**
   - Edition metadata stamp (`EDITION NO. 07 — 2026`, `BROADSHEET FOLIO 576 × 825 MM`).
   - View mode toggle: Desk Perspective (tilted physical broadsheet) vs Broadsheet Flat View.
   - Minimal quiet navigation: `PAINTINGS`, `ABOUT`, `RECOGNITIONS`, `CONTACT`.
2. **The Front Page Masthead:**
   - Giant `RAYMOND` newspaper banner.
   - Dual-column curatorial dispatch ("Tactile Gesture & The Chromatic Void") flanking the lead cover monograph artwork.
3. **Statement of Purpose:**
   - "ABSTRACT ARTIST!" architectural spread pairing technical materiality manifestos with museum installation plate `UNTITLED I (TECTONIC HORIZON)`.
4. **Full-Bleed Typographic Poster Block:**
   - Deep carbon black banner (`#1A1817`) with monumental serif text: `FORM. COLOR. EMOTION.`, defining silence, matter, and resonance axioms.
5. **Catalogue Raisonné ("ALL PAINTINGS!"):**
   - Asymmetric multi-column spread featuring `UNTITLED II`, `UNTITLED IV`, `UNTITLED III`, and `UNTITLED I`.
   - Subtle hover zoom (`1.025×`), exact dimensional labels, medium recipes (raw flax, cold wax, burnt sienna, iron oxide).
6. **Curatorial Bulletin ("LATEST PAINTINGS!"):**
   - Asymmetric trio examining impasto density (14mm relief), Provence mineral extraction, and scale architecture.
7. **Monograph Feature Essay ("PERFECT ARTISAN"):**
   - Classic French gazette layout with 2-line drop cap, critique by Claude Lemaire, and full-bleed study plate.
8. **Archival Metrics & Provenance:**
   - Large numeric typographic statistics (`07` Solo Exhibitions, `14` Public Collections, `05` Honors, `12` Monograph Volumes) followed by institutional audit tables.
9. **Curatorial Testimonials:**
   - Dual quotes set in raw paper columns from Palais des Arts Paris and The Bresweth Collection NY.
10. **Final Contact & Studio Colophon:**
    - Monumental headline: `LET'S TALK ABOUT ART.`
    - Direct acquisition dispatch: `STUDIO@RAYMOND-ATELIER.COM`
    - Archival colophon with Paris and New York studio registry.
