# KRONOS 01 — Visual Design System, Tokens & Project Brief

---

## 1. Project Brief & Concept

### Executive Summary
**KRONOS 01** is a speculative, high-precision industrial landing page for a reference-grade laboratory kinematic audio monitor and planar electromagnetic transducer. The design embodies raw mechanical engineering, laboratory metrology, aerospace-grade machining, and verifiable acoustic physics.

### Core Design Philosophy
- **Anti-Decorative / Utilitarian**: Depth is conveyed through real machined subject photography, hairline technical line work, and CAD orthographic projections—never through blurred gradient cards, neon drop shadows, or generic glassmorphism.
- **Data as Proof**: Claims are not marketing copy; they are mathematically generated traces (summed sine waves), ISO 2768-mK tolerances, and calibrated goniometric positions.
- **Scroll as Mechanics**: Scrolling controls mechanical kinematics (360° rotor turn, counter-travel typography, and phase metrics) rather than arbitrary CSS parallax.
- **Complete Before Motion**: The interface maintains total visual integrity and complete typography even if JavaScript is disabled or prefers-reduced-motion is active.

---

## 2. Color Palette & Tokens

The interface adheres strictly to an **achromatic ground system with exactly one chromatic signal accent**:

| Token Name | Hex / CSS Value | Role & Usage Guidelines |
|---|---|---|
| `--ground-primary` | `#EFEFEE` | Cool achromatic primary background for body and sections. |
| `--ground-stage` | `#E4E4E2` | Dimmer stage ground for the sticky hero and kinematic track. |
| `--ground-inverted` | `#0D0D0F` | Full-bleed ink ground for dark audit and distortion proof stages. |
| `--ink-primary` | `#0D0D0F` | Near-black ink for high-priority headlines and poster typography. |
| `--ink-secondary` | `#43444A` | Secondary text for ledes, parameter descriptions, and subheaders. |
| `--ink-muted` | `#6E6F76` | Muted ink for technical indexes, metadata labels, and datum notes. |
| `--signal-accent` | `#2F5BFF` | **The single signal accent.** Used *only* for active laser reticles, data traces, active telemetry text, and hairline status indicators. Never used as a large background fill. |
| `--signal-accent-lift` | `#7C97FF` | High-contrast lift of the signal accent when rendered on dark ink grounds (`#0D0D0F`). |
| `--hairline-rule` | `rgba(13, 13, 15, 0.12)` | Hairline dividers, audit table borders, and CAD projection grids. |
| `--hairline-rule-dark` | `rgba(255, 255, 255, 0.10)` | Hairline dividers on inverted dark sections. |

---

## 3. Typography & Typesetting Hierarchy

The typography pairs an industrial Swiss/Neo-Grotesk display typeface with an aerospace-grade monospace font:

### Typefaces
1. **Display Headline**: `'Archivo', sans-serif` (Google Fonts: weights 700, 800, 900)
2. **Technical & Telemetry**: `'IBM Plex Mono', monospace` (Google Fonts: weights 400, 500, 600)

### Typographic Scales & Properties

| Element | Font Family | Weight | Size / Clamp | Line Height | Tracking | Transform |
|---|---|---|---|---|---|---|
| **Poster Wordmark** | Archivo | 900 | `clamp(84px, 20vw, 304px)` | `0.74` | `-0.055em` | Uppercase |
| **Hero Headline** | Archivo | 800 | `clamp(34px, 5.1vw, 74px)` | `0.88` | `-0.045em` | Uppercase |
| **Section Headlines** | Archivo | 800 | `clamp(28px, 4vw, 56px)` | `0.92` | `-0.04em` | Uppercase |
| **Giant Tabular Metric** | IBM Plex Mono / Archivo | 800 | `clamp(56px, 9vw, 132px)` | `0.90` | `-0.03em` | Tabular |
| **Lede Copy** | Archivo / Inter | 400–500 | `14px – 16px` | `1.45` | `-0.01em` | Normal sentence |
| **Header Nav Links** | IBM Plex Mono | 500 | `11px` | `1.0` | `+0.14em` | Uppercase |
| **Corner Metadata** | IBM Plex Mono | 400–500 | `10px – 11px` | `1.2` | `+0.16em` | Uppercase |
| **Audit Table Values** | IBM Plex Mono | 500 | `11px – 12px` | `1.2` | `+0.08em` | Tabular |

---

## 4. UI Components & Architectural Styling

### 1. Header Navigation Bar
- **Height**: `64px` fixed height, sticky top.
- **Glass / Ground**: `#EFEFEE` at 82% opacity with `backdrop-filter: blur(14px)`.
- **Border**: `1px solid rgba(13, 13, 15, 0.12)` bottom border.
- **Navigation Items**: Pill badge button containers with `padding: 6px 14px`, `border-radius: 9999px`, micro font `11px IBM Plex Mono`, and subtle background tint on hover.
- **CTA Button**: Pill shaped, high-contrast dark fill (`#0D0D0F`), white monospace text with trailing glyph.

### 2. Type & Subject Occlusion Weave (Hero)
- **Layer 1 (z-index: 1)**: Base poster wordmark `KRONOS` full width with letter `O` hidden (`visibility: hidden`).
- **Layer 2 (z-index: 2)**: 3D photorealistic studio rotor cut-out positioned at bottom right, bleeding `4vw` past the frame edge. Includes laser reticle ring overlay.
- **Layer 3 (z-index: 3)**: Front poster wordmark with all letters hidden *except* the overlapping letter `O`, perfectly registering with Layer 1.

### 3. Stage 04: Pinned Scroll-Locked Kinematic Stage
- **Container**: `min-height: 400vh` scroll track.
- **Stage**: `position: sticky; top: 0; height: 100vh; overflow: hidden`.
- **Central Element**: 4-vane counter-travel rotor with goniometer degree ticks, cardinal markers (`000°`, `090°`, `180°`, `270°`), and live radial readouts.
- **Background Typography**: `clamp(78px, 17vw, 250px)` marquee counter-translating horizontally in exact sync with scroll velocity.
- **Telemetry Readouts**: Instantaneous calculation of `Radial Position (000.0° - 360.0°)`, `Angular Velocity (rad/s)`, and `Vector [X / Y]`.

### 4. Interactive Field-Swap Matrix (Stage 05)
- **Transition**: `background-color 0.7s cubic-bezier(0.16, 1, 0.3, 1)`, `color 0.7s ease`.
- **Dividers**: Styled using `border: 1px solid color-mix(in srgb, currentColor 24%, transparent)` to prevent solid fill color collapses during dynamic palette shifts.

### 5. Audit Tables & Orthographic CAD Diagrams
- **Table Styling**: Zero outer card borders; rows separated by `1px solid rgba(13, 13, 15, 0.12)` hairlines; left column title, right column tabular mono metric.
- **CAD Diagram**: Vector SVG rendered to exact metric scale with center datum rings, ISO 2768-mK tolerance notes, and hairline leader lines terminating in accent dots.
