# Production Prompt & Implementation Blueprint: Tactile Neumorphic Landing Page (Robin Replica)

> **Purpose**: Use the prompt and engineering specification below to reproduce the exact visual architecture, tactile physics, component layout, and interactive states of the **Robin — Tactile Landing Page**.

---

## 1. Master Generation Prompt (Copy & Paste)

```markdown
Generate a high-fidelity, ultra-clean single landing page portfolio for an interface architect and industrial software designer named "Robin". 

The entire visual system must be modeled as a continuous, soft-molded ceramic substrate (zero-border paradigm) inspired by high-end tactile hardware, audio synthesizers, and soft-neumorphic physical control surfaces.

### Core Visual Principles:
1. Zero 1px borders or dividers anywhere: All structural volume, separation, and depth must emerge solely through physics-based dual-opposing light refraction and ambient occlusion (135° simulated keylight: NW specular highlight + SE diffused ambient shadow).
2. Monochromatic Cool Ceramic Substrate: The entire document background, card containers, and resting surfaces share the exact same cool slate-grey tone (#EFF3F8 to #E0E5EC). Digital elements must look carved or extruded directly out of this one continuous material.
3. High-Energy Accent: High-contrast Poppy Coral / Warm Vermilion (#FF4338 / #FF5544) used sparingly on key tactile switches, dial reticles, live indicator LEDs, and primary action triggers.
4. Topography:
   - Convex / Extruded (+Z): Cards, buttons, fader caps, resting switches, and elevated dials cast outward dual shadows.
   - Concave / Inset (-Z): Fader tracks, input wells, transport pods, and screen apertures cast deep inward inset shadows.

### Typography & Lettering:
- Display / Headlines: Wide geometric sans-serif (Syne or Plus Jakarta Sans 800) with ultra-tight tracking (-0.035em). Hero headline: "Sculpting UI with continuous light and physical weight." with "continuous light" highlighted in poppy coral.
- Subheaders & Body: DM Sans / Inter (weights 400 & 500, leading-relaxed) in slate navy (#1E2530) for AAA contrast and cool muted grey (#6B7280) for metadata.
- Technical Badging: JetBrains Mono / SF Mono, 10–12px uppercase, tracking-widest, encased in recessed micro-wells.

### Component Structure & Page Layout (Single Page Flow):
1. Floating Tactile Nav: Pillowed capsule bar with debossed studio brand mark ("ROBIN TACTILE STUDIO"), inset navigation links ("Overview", "Works", "Tactile Lab", "Philosophy", "Connect"), an active status indicator pill ("AVAILABLE Q3/Q4"), and an extruded coral "Let's Build →" trigger.
2. Hero & Telemetry Banner:
   - Monumental sculpted headline with coral punchline.
   - Dual tactile CTA row: Extruded coral button ("Touch Interactive Lab →") paired with an extruded ceramic secondary pill ("View Systems").
   - Telemetry strip encased in a debossed slot: Optical Lux: 135° NW Specular | Impedance: 0.28ms Deep Well | Tolerance: ±0.024mm Physical Fidelity.
3. Master Hardware Control Console (Model R-24):
   - A large, pillowed unibody console card featuring:
     a) Tactile Transport Keypad: Recessed well holding 6 extruded square triggers (Rewind, Stop, Play in Coral, Fast Forward, Up, Pause, Down) with debossed icon reliefs.
     b) Master Rotary Encoder: Concentric dual-ring circular dial with degree ticks, central grip with coral detent mark, and live numeric angle readout ("VALUE: 148°").
     c) Resonant Faders & Channel Strips: Inset vertical fader channels with extruded thumb caps, coral indicator spheres, and dual channel buttons (CH+, CH- in coral).
4. Featured Architecture (Case Studies):
   - 3-column continuous molded cards with recessed display screens, monospace tags, project year, and tactile coral "Explore →" triggers:
     - "Kinetix Spatial Synth" (Hardware / Sound UI)
     - "Ceramic Ambient OS" (Operating System)
     - "Aura Bio-Tracker" (Biometric Telemetry)
5. The Tactile Micro-Component Playground:
   - An interactive hardware laboratory displaying tactile primitives:
     - Recessed Screen Socket with debossed mini canvas
     - Depressed circular GPS well with central coral pin
     - Tactile Bistable Rocker Switch (Engaged/Active state in coral)
     - Circular well array with debossed keycaps (Star, Lock, Cloud, Cancel, Active CH, Debossed Pod)
6. Three Laws of Digital Materiality:
   - 3 cards detailing the tactile manifesto: "01 Molded Continuous Surface", "02 Dual-Phase Specular Light", and "03 Calibrated Sensory Friction" with debossed specification footers.
7. Commission a Tactile System:
   - Recessed contact enclosure with inset form inputs (debounced focus states), pill-capsule selection toggles for scope ("Full Design System", "Hardware & Screen", "Spatial Audio App", "Tactile Audit"), and an extruded coral submission button ("Transmit Inquiry →").
8. Footer: Minimalist debossed brand row with copyright, tactile social capsules (X, GH, CV, FG), and "TOP OF SURFACE ↑" smooth return anchor.
```

---

## 2. Technical CSS Specification & Physics Tokens

If implementing in vanilla CSS or Tailwind, configure the exact shadow physics below:

### Precise Box-Shadow Tokens
```css
:root {
  /* Substrate Color Baseline */
  --bg-ceramic: #EFF3F8;
  --bg-surface: #E0E5EC;
  --text-primary: #1E2530;
  --text-muted: #6B7280;
  --accent-coral: #FF4338;
  --accent-coral-gradient: linear-gradient(135deg, #FF5C50, #E03025);

  /* Light Source: 135 deg Keylight (Top-Left Specular, Bottom-Right Occlusion) */
  /* 1. Standard Extruded Element (Cards, Rest Triggers, Floating Enclosures) */
  --shadow-extruded: 12px 12px 24px rgba(163, 177, 198, 0.65), 
                     -12px -12px 24px rgba(255, 255, 255, 0.9);

  /* 2. Elevated / Hover Extrusion */
  --shadow-extruded-hover: 16px 16px 32px rgba(163, 177, 198, 0.75), 
                           -16px -16px 32px rgba(255, 255, 255, 1.0);

  /* 3. Deep Inset Well (Sockets, Sliders, Screen Wells, Inputs) */
  --shadow-inset-deep: inset 8px 8px 16px rgba(163, 177, 198, 0.7), 
                       inset -8px -8px 16px rgba(255, 255, 255, 0.9);

  /* 4. Shallow / Micro Inset (Pills, Detents, Small Wells) */
  --shadow-inset-micro: inset 3px 3px 6px rgba(163, 177, 198, 0.6), 
                        inset -3px -3px 6px rgba(255, 255, 255, 0.85);

  /* 5. Coral Button Extrusion */
  --shadow-coral-button: 8px 8px 20px rgba(255, 67, 56, 0.35), 
                         -4px -4px 12px rgba(255, 255, 255, 0.8);
}
```

---

## 3. Tailwind CSS Preset Configuration

Add these extended utilities to `tailwind.config.js` to match the exact look:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        substrate: '#EFF3F8',
        'substrate-dim': '#E0E5EC',
        'slate-charcoal': '#1E2530',
        'poppy-coral': '#FF4338',
      },
      fontFamily: {
        display: ['"Plus Jakarta Sans"', '"Syne"', 'sans-serif'],
        mono: ['"JetBrains Mono"', 'monospace'],
        body: ['"DM Sans"', 'sans-serif'],
      },
      borderRadius: {
        '3xl': '28px',
        '4xl': '36px',
        '5xl': '44px',
      },
      boxShadow: {
        'tactile-extrude': '12px 12px 24px rgba(163, 177, 198, 0.65), -12px -12px 24px rgba(255, 255, 255, 0.9)',
        'tactile-lift': '16px 16px 32px rgba(163, 177, 198, 0.75), -16px -16px 32px rgba(255, 255, 255, 1.0)',
        'tactile-inset': 'inset 8px 8px 16px rgba(163, 177, 198, 0.7), inset -8px -8px 16px rgba(255, 255, 255, 0.9)',
        'tactile-inset-sm': 'inset 3px 3px 6px rgba(163, 177, 198, 0.6), inset -3px -3px 6px rgba(255, 255, 255, 0.85)',
      }
    }
  }
}
```

---

## 4. Key Interactive States & Ergonomics

1. **Button Depression**: When any tactile button is pressed (`:active`), switch its shadow from `--shadow-extruded` to `--shadow-inset-micro` and add `transform: translateY(1.5px) scale(0.985)` to simulate physical displacement into the substrate.
2. **Rotary Encoder**: Rotates smoothly with mouse drag or click detents, updating a companion monospace degree indicator in real time.
3. **Fader Tracks**: Inset grooves where thumb-caps glide along the Y-axis with a poppy coral detent dot that illuminates as level rises.
4. **Form Inputs**: Rest in a soft debossed state (`--shadow-inset-deep`); on focus, keep the deep inset while applying a subtle poppy coral rim or outer halo without adding a solid 1px border.
