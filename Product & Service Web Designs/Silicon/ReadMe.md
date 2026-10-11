# Silion — Human-Grade AI Design Documentation & Visual System

## 1. Project Brief & Overview
**Silion** is an enterprise AI infrastructure platform engineered for multi-step causal reasoning, mathematical grounding, and deterministic verification. 

Unlike conventional consumer AI or playful SaaS tools, Silion’s landing page was designed with a **cinematic, scientifically rigorous, and mysterious** visual aesthetic. The centerpiece is a real-time volumetric human head particle system that visually articulates the concept of "human-grade machine cognition" emerging from raw enterprise telemetry.

---

## 2. Visual Design System

### 2.1 Color Palette
The color system emphasizes deep computational darkness, punctured only by luminous, high-energy telemetry and neural signals:

| Token / Role | Hex Code | Purpose |
| :--- | :--- | :--- |
| **Deep Space Background** | `#03051A` | Global foundation, page canvas base |
| **Midnight Surface** | `#05082A` | Hero canvas and mid-ground atmosphere |
| **Surface Container Lowest**| `#070A2C` | Deep card backings, inset panels |
| **Surface Container Low**   | `#0C1031` | Elevation cards, modules, navigation |
| **Surface Container High**  | `#1E234D` | Hover states, active borders, card highlights |
| **Primary Blue (Core)**     | `#536BFF` | Primary CTA, core particle volume, active indicators |
| **Electric Accent**         | `#7887FF` | Traveling pulse peak, directional arrows, highlights |
| **Violet Neural Accent**    | `#A78BFF` | Secondary particle glow, subtle gradient accents |
| **Cyan-White Luminous**     | `#E0E7FF` | High-energy particle ignition, active terminal status |
| **Text Primary (White)**    | `#F5F7FF` | Primary headlines, critical numerical readouts |
| **Text Secondary (Muted)**  | `#8991B5` | Body copy, section descriptions, secondary labels |
| **Technical Telemetry / HUD**| `#39416D` | Hairline borders, coordinate grids, bracket accents |

---

### 2.2 Typography Hierarchy
The typography relies on clean, modern grotesk letterforms combined with precise, monospace telemetry:

- **Primary Font Family:** `Geist`, `Inter`, `-apple-system`, `sans-serif`
- **Monospace Font Family:** `JetBrains Mono`, `Fira Code`, `ui-monospace`, `monospace`

#### Typographic Scale & Styling:
- **Hero Display Headline:** 
  - Size: `64px – 80px` (`text-5xl` to `text-7xl`)
  - Weight: Light to Medium (`font-normal` / `font-medium`)
  - Tracking: `-0.03em` (`tracking-tight`)
  - Line Height: `1.05`
  - Color: `#F5F7FF`
- **Section Headlines:** 
  - Size: `40px – 48px` (`text-4xl` / `text-5xl`)
  - Tracking: `-0.02em`
  - Color: `#F5F7FF`
- **Eyebrow & Section Categorization:**
  - Monospace uppercase: `// 02. ARCHITECTURE —— TOPOLOGICAL REASONING`
  - Size: `11px – 13px` (`text-xs`)
  - Tracking: `+0.12em` (`tracking-widest`)
  - Color: `#7887FF` or `#8991B5`
- **Body Copy:**
  - Size: `15px – 17px` (`text-sm` / `text-base`)
  - Line Height: `1.6`
  - Weight: Light (`font-light` / `text-slate-400`)
- **HUD & Telemetry Readouts:**
  - Monospace uppercase: `[ MOD_01 ]`, `LATENCY: 4.8ms`, `VECTOR_LAT: 47.6062° N`
  - Size: `10px – 11px` (`text-[10px]` / `text-xs`)
  - Tracking: `+0.08em`
  - Color: `#8991B5` / `#39416D`

---

## 3. UI Components & Layout Composition

### 3.1 Fixed Navigation Bar
- **Dimensions & Backdrop:** Ultra-compact `h-14` header with `rgba(5, 8, 42, 0.75)` backdrop blur (`backdrop-blur-md`) and `1px` border in `#1E234D`.
- **Brand Mark:** Clean monospaced wordmark `SILION` with sub-chip `SYS.AI // V4.2`.
- **Navigation Links:** `Product`, `Intelligence`, `Platform`, `Research`, `Company` with soft hover illumination (`#F5F7FF`) and subtle tracking expansion.
- **CTA:** Compact pill button with high-contrast text and micro-arrow icon.

### 3.2 3D Volumetric Particle Engine (Three.js)
- **Point Cloud Density:** 14,000 dynamic WebGL particles rendered with additive blending (`THREE.AdditiveBlending`).
- **Anatomy Model:** Procedurally sculpted human cranium, temples, brow, nose bridge, cheekbones, jawline, chin, and neck column.
- **Micro-Physics & Drifts:** Microscopic Perlin noise shimmer and ambient particle suspension.
- **Luminous Energy Sweep:** Periodic vertical sinusoidal wave travelling through facial coordinates, igniting particles into cyan-white and violet highlights.
- **Mouse Parallax:** Responsive camera and mesh rotation reacting smoothly to user cursor coordinates.

### 3.3 HUD Coordinates & Ambient Elements
- **Reticles & Framing:** Hairline crosshairs, axis tickers (`AXIS_Z: 994.12`), bracket tags (`[ AXIOMATIC GUARANTEE ]`).
- **Data Tickers:** Real-time entropy counters, vector latitude/longitude coordinates, and sync statuses (`LIVE_SYNC`).

### 3.4 Spatial Pipeline & Metric Blocks
- **5-Stage Pipeline:** Ingestion → Parsing → Resolution → Core Engine → Action Dispatch, connected with directional node guides.
- **High-Impact Stat Callouts:**
  - `99.98%` Verification Fidelity
  - `0.00` Speculative Hallucination
  - `<18ms` Decision Dispatch
- **Live SAT-Solver Terminal:** Dark interactive console emulating live constraint evaluation cycles, SHA hashes, and formal mathematical proofs.

---

## 4. Key Copy & Messaging Matrix

| Location | Text Content | Strategic Rationale |
| :--- | :--- | :--- |
| **Hero Title** | `"Human-Grade Reasoning."` | Asserts parity with human cognitive reasoning depth over simple next-token completion. |
| **Hero Subtitle** | *"Engineered for multi-step causal reasoning directed directly in enterprise telemetry, unstructured operational records, and sovereign real-time context."* | Defines the technical enterprise scope and grounding mechanisms. |
| **Rotating Tenet 1** | `"Built Into Every Decision."` | Highlights production immersion and operational reliability. |
| **Rotating Tenet 2** | `"Grounded In Your Own Data."` | Eliminates enterprise fears of synthetic hallucination. |
| **Rotating Tenet 3** | `"Verifiable Multi-Step Chains."` | Emphasizes deterministic auditability and formal verification. |
| **Section 02** | `"Reasoning that understands the context."` | Contextual entity extraction, world modeling, and invariant memory. |
| **CTA Bar** | `"Experience Human-Grade Intelligence."` | Confident, direct invitation for enterprise sovereign deployments. |

---
name: Silion Infrastructure
colors:
  surface: '#0c1031'
  surface-dim: '#0c1031'
  surface-bright: '#333659'
  surface-container-lowest: '#070a2c'
  surface-container-low: '#15183a'
  surface-container: '#191d3e'
  surface-container-high: '#232749'
  surface-container-highest: '#2e3255'
  on-surface: '#dfe0ff'
  on-surface-variant: '#c5c5d8'
  inverse-surface: '#dfe0ff'
  inverse-on-surface: '#2a2e50'
  outline: '#8f8fa1'
  outline-variant: '#444655'
  surface-tint: '#bbc3ff'
  primary: '#bbc3ff'
  on-primary: '#001c95'
  primary-container: '#7487ff'
  on-primary-container: '#001883'
  inverse-primary: '#324ce1'
  secondary: '#cebdff'
  on-secondary: '#371089'
  secondary-container: '#4e2fa0'
  on-secondary-container: '#bda8ff'
  tertiary: '#bcc2ff'
  on-tertiary: '#031899'
  tertiary-container: '#7786fe'
  on-tertiary-container: '#00138a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dee0ff'
  primary-fixed-dim: '#bbc3ff'
  on-primary-fixed: '#000e5e'
  on-primary-fixed-variant: '#092dca'
  secondary-fixed: '#e8ddff'
  secondary-fixed-dim: '#cebdff'
  on-secondary-fixed: '#20005e'
  on-secondary-fixed-variant: '#4e2fa0'
  tertiary-fixed: '#dfe0ff'
  tertiary-fixed-dim: '#bcc2ff'
  on-tertiary-fixed: '#000a63'
  on-tertiary-fixed-variant: '#2737ae'
  background: '#0c1031'
  on-background: '#dfe0ff'
  surface-variant: '#2e3255'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
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
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  telemetry-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-mono-xs:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.1em
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the calculated precision of cinematic AI infrastructure and human-grade synthetic intelligence. It rejects cartoonish tech tropes in favor of an elite, sovereign research aesthetic: deep observational space, high-frequency telemetry, razor-thin structural lattices, and luminous photon states.

The visual style unites **Technical Brutalism** and **Atmospheric Sci-Fi Minimalism**:
- **Atmospheric Depths:** Deep midnight navy voids create an infinite canvas where luminous nodes and data arrays emerge without visual clutter.
- **Instrument Precision:** Interfaces resemble mission-critical orbital workstations or photonics research apparatuses. Micro-borders, precision reticles, coordinate badges, and tabular telemetry markers reinforce mechanical certainty.
- **Restrained Brilliance:** High-chroma electric blues and ultraviolet photon accents are deployed strictly as active states, directional vectors, or real-time signals, maintaining total contrast against the quiet structural grid.

## Colors

The palette operates on calibrated contrast, shifting from foundational void layers to high-intensity photon emissions.

### Canvas & Surface Architecture
- **Base Canvas (`#03051A`):** Pure background void; unyielding midnight navy absorbing stray light.
- **Sub-Surface Tier 1 (`#05082A`):** Structural panels, terminal bases, and telemetry decks.
- **Surface Elevation Tier 2 (`#070B35`):** Hover states, elevated command modules, flyout dialogs, and active cards.

### Telemetry & Wireframe Accents
- **HUD Edge Subdued (`#1E2548`):** Baseline structural hairpins, persistent grid dividers, and inactive boundaries.
- **HUD Edge Active (`#39416D`):** Interactive borders, data-table borders, and component containment lines.

### Photonic Emissive Hierarchy
- **Electric Vector (`#536BFF`):** Core interactive primary. Drives system calls, primary executions, and critical vectors.
- **Hyper-Shift Blue (`#7887FF`):** Hover and focal state augmentation.
- **Photon Ultraviolet (`#A78BFF`):** Secondary state indicator for human-grade cognitive benchmarks, model synthesis states, and semantic highlights.

### Readout & Typography Values
- **Optical Crisp White (`#F5F7FF`):** Dominant contrast value for key metrics, headline executions, and direct values.
- **Muted Technical Slate (`#8991B5`):** Monospace telemetry labels, secondary text, metadata readouts, and scale dimensions.
- **Warning/Telemetry Amber (`#FFB347`) & Critical Red (`#FF4B6E`):** Reserved strictly for operational alerts and infrastructure telemetry alarms.

## Typography

The typography couples the razor-sharp density of **Geist** for system commands, navigation, and executive summaries with the microscopic rigor of **JetBrains Mono** for machine telemetries, coordinates, and latency readouts.

- **Monochrome Hierarchy:** Text sizes scale conservatively. Emphasis is gained not by extreme scale variations, but through tactical weight shifts (400 vs 600) and strict contrast switches between `#F5F7FF` and `#8991B5`.
- **Telemetry Readouts:** Labels that index system states or coordinate axes leverage `label-mono` in uppercase tracking (`letter-spacing: 0.06em` or `0.1em`) to mimic instrumentation panels.
- **Tabular Figures:** Monospace metrics must strictly run with tabular alignment enabled (`font-variant-numeric: tabular-nums`) to prevent optical shifts during real-time compute streams.

## Layout & Spacing

The structural layout utilizes a strict **12-column modular grid** framed by surgical boundary borders. The interface relies on architectural alignment rather than loose spatial floating.

### Desktop & Workstation Layout (1440px+)
- Maximum viewport container spans 1600px, flanked by minimum 48px (`margin: 3rem`) canvas boundaries.
- Continuous 1px HUD grid lines subdivide columns using the `#1E2548` edge token.
- Multi-pane research split screens conform to 2-column, 4-column, and 6-column spatial units with fixed 24px (`gutter: 1.5rem`) gutters.

### Mobile & Compact Surfaces (<768px)
- Dynamic single or twin column reflow with compressed 16px (`margin-mobile: 1rem`) side padding.
- Multi-dimensional data tables reflow into stacked telemetry nodes with explicit 1px horizontal separator rules.

### Spatial Rhythm
- **Micro-Gaps (`space-xs`, `space-sm`):** Bound strictly to inline telemetry pairs (e.g., node status dot adjacent to label, parameter to value).
- **Component Padding (`space-md`, `space-lg`):** Encapsulated terminal blocks, compute readouts, and execution trigger pads.
- **Section Breaks (`space-xl`):** Delimiting macro telemetry bays and system infrastructure stacks.

## Elevation & Depth

Visual hierarchy does not use soft natural shadows. Depth is achieved entirely through **Tonal Laminations**, **Low-Contrast Outlines**, and **Photon Backglows**.

### Tonal Tiers
1. **Deep Void (0dp):** `#03051A` — The infinite computational vacuum.
2. **Structural Bay (1dp):** `#05082A` bordered with a 1px solid stroke of `#1E2548`.
3. **Active Telemetry Unit (2dp):** `#070B35` bordered with a 1px solid stroke of `#39416D`.

### Photonic Glow & Focus
Elevated focal elements (active compute nodes, live inference channels, primary CTAs) produce zero drop-shadow offset. Instead, they emit an ambient, diffuse photonic halo:
- `box-shadow: 0 0 24px -4px rgba(83, 107, 255, 0.25), inset 0 1px 0 0 rgba(167, 139, 255, 0.35)`
- Micro-glass backdrop filtering (`backdrop-filter: blur(12px)`) is reserved for floating HUD command bars and coordinate overlays, layered over a 75% alpha fill of `#05082A`.

## Shapes

The geometric architecture is built on absolute angularity: **Zero-radius sharpness (`roundedness: 0`)**.

- **90-Degree Discipline:** Panels, buttons, inputs, chips, and modals terminate in exact 90-degree corners (`border-radius: 0px`).
- **Telemetry Notching & Chamfers:** For rare priority cards or modal shells, components utilize a precise 45-degree corner notch (`clip-path: polygon(...)`) cut to 6px, reinforcing physical computational hardware aesthetics.
- **Hairline Uniformity:** All structural boundaries, dividers, and framing rings maintain a calibrated 1px stroke thickness. Heavy strokes are forbidden to preserve optical delicacy.

## Components

### Buttons & Execution Controls
- **Primary Trigger:** Solid `#536BFF` background with `#F5F7FF` typography, zero radius, 1px top highlight border of `#A78BFF`. Hover triggers an immediate scale of luminosity to `#7887FF` with a subtle photonic edge bloom.
- **Secondary Telemetry Trigger:** Dark background (`#05082A`), 1px outline of `#39416D`, `#F5F7FF` typography. Hover shifts the border to `#536BFF` and background to `#070B35`.
- **Terminal Micro-Action:** Transparent fill, 1px `#1E2548` outline, monospace uppercase label, bracketed delimiters (e.g., `[ RUN_DIAGNOSTIC ]`).

### Chips, Badges & Status Tags
- **Telemetry Chip:** `#03051A` background, 1px border (`#1E2548`), `label-mono-xs` typography in `#8991B5`.
- **Photon State Indicators:** Inlined 6px square indicator (0px radius). Solid `#536BFF` or `#A78BFF` with an animated ambient pulse for running cluster states; static `#8991B5` for idle states.

### Cards & Telemetry Bays
- Built with `#05082A` fill and structural 1px border (`#1E2548`).
- Header bays feature segmented metadata strips showing localized timestamp, grid coordinate (e.g., `LOC://38.90.01`), and machine status.
- Card intersections feature crosshair corner ticks (`+`) rendered in `#39416D` overlapping the 1px boundary.

### Input Fields & Terminal Consoles
- **Input Housing:** Rigid `#03051A` fill, 1px border (`#1E2548`), height 40px, padding `0.5rem 1rem`.
- **Text State:** Values display in `#F5F7FF` (`body-md`), while placeholder text sits in `#8991B5`.
- **Active Focus:** Instant border shift to `#536BFF`, accented by a 1px inner inset glow `rgba(83, 107, 255, 0.2)`. No rounded corners.

### Lists & Data Grids
- Full-bleed rows enclosed by horizontal 1px lines (`#1E2548`).
- Header rows utilize `label-mono` in `#8991B5` with uppercase tracking.
- Row hover produces an immediate background shift to `#070B35` across the entire row width, highlighting corresponding latency metrics in `#A78BFF`.

### Checkboxes & Segmented Toggles
- **Checkboxes:** 14px sharp squares (`#03051A` base with 1px `#39416D` edge). Selected state fills the square with `#536BFF` containing a sharp, non-rounded vector check in `#F5F7FF`.
- **Segmented Arrays:** Bordered container holding sharp rectangular segments; active segment is elevated with `#070B35` fill and a persistent 1px outline in `#536BFF`.