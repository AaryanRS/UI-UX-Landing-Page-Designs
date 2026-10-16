# Architectural Type System — Landing Page

Architectural Type System is a minimalist, monochrome design exploration focusing on rigid grid structures, hairline borders, and extreme typographic hierarchy. It blends the structural precision of an IDE with the boldness of Swiss-editorial brutalism.

---

## 1. Visual & Aesthetic Architecture

- **Visual Theme:** Swiss-Brutalist Architectural Grid Matrix
- **Color Philosophy:** Strict binary monochrome foundation with a single high-impact functional indigo accent.
  - **Background:** `#000000` (Pure Black)
  - **Foreground / Text:** `#FFFFFF` (Pure White)
  - **Structural Hairlines:** `rgba(255, 255, 255, 0.15)` at `0.5px` border thickness
  - **Functional Accent:** `#6366f1` (Indigo — reserved for primary key actions, focal data points, and active states)
  - **Surface Dim / Hover Fill:** `rgba(255, 255, 255, 0.03)` to `rgba(255, 255, 255, 0.05)`
- **Atmospheric Layer:**
  - A subtle 5% opacity procedural fractal noise overlay (`feTurbulence`) positioned globally with `pointer-events-none` to evoke tactile print grain on digital displays.

---

## 2. Typography System

| Role | Font Family | Weight | Tracking / Letter Spacing | Case | Usage |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Display / Headlines** | `Inter Tight` | 900 (Black) | `-0.06em` (Extreme Tight) | Uppercase | 2x2 Hero Quadrants, Section Headers |
| **Technical Metadata** | `JetBrains Mono` | 500 (Medium) | `0.2em` to `0.4em` (Wide) | Uppercase (Underscores) | Tags (`SYSTEM_01`), Labels, Versioning, Coordinates |
| **System Timer** | `JetBrains Mono` | 700 (Bold) | `0.1em` (Tabular Nums) | Normal | Countdown Clock (`HH : MM : SS`) |
| **Editorial Body** | `Inter` | 300 / 400 | Normal | Sentence Case | Card descriptions, body explanations (40% opacity) |

---

## 3. Structural Components

1. **Top Navigation Chrome:**
   - Height: `72px`, fixed full-width.
   - Background: `#000000` with `80%` opacity and backdrop-blur.
   - 0.5px hairline bottom border.
   - Left: Brand mark `ARCHITECTURAL` in `Inter Tight` 900, a 6px solid white dot, and version tag `BETA_V.01`.
   - Right: Circular hairline social buttons (40px) and a pill-shaped `GET ACCESS` CTA in 10px bold mono.

2. **Hero Section (The 2x2 Grid Matrix):**
   - 4 quadrants separated by 0.5px hairlines dividing viewport height.
   - Monumental word segments (`SU`, `PER`, `DE`, `SIGN`) scaled at `clamp(5rem, 16vw, 22vw)` pinned to quadrant boundaries with intentional architectural clipping.
   - Each quadrant is tagged with precise geographic/spatial coordinates in JetBrains Mono.

3. **Command Bar:**
   - 4-column horizontal strip bounded by hairline borders:
     - **Cell 1:** Raw email input field with `JetBrains Mono` placeholder (`ENTER_WORK_EMAIL...`).
     - **Cell 2:** High-contrast `JOIN` action button in `#FFFFFF` with `#000000` text and 0.3em letter-spacing.
     - **Cell 3:** Fixed-width status countdown timer (`14 : 08 : 39`) with 20% opacity colon separators.
     - **Cell 4:** Vertical stack of system verification tags (`FREE_ACCESS_PASS`, `NO_CREDIT_CARD`, `DEPLOY_IMMEDIATE`).

4. **Bento Feature Grid:**
   - 3-column equal-height cards (420px height) divided by 0.5px hairlines.
   - **Interactive Geometric Card:** Nested hairline diamond rotated 45 degrees, accelerating to 90 degrees on hover via `cubic-bezier(0.4, 0, 0.2, 1)`.
   - Low opacity icons (20%) transitioning to 100% optical clarity on hover.
   - Background hover shifts to `rgba(255, 255, 255, 0.03)` over a 300ms transition.

---

## 4. Design Rules & Invariants

- **0px Border Radius:** Applied universally to all grid cells, containers, and inputs (only pill-shaped buttons are permitted rounding).
- **Zero Drop-Shadows & Gradients:** Depth and hierarchy are achieved exclusively through pure line-work, contrast ratios, and whitespace rhythm.
- **Strict Underscores:** All mono-spaced metadata labels use underscores instead of spaces (`FREE_ACCESS`, `SYSTEM_READY`).
