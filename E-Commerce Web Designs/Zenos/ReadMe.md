# ZENOS — Y2K Cinematic E-Commerce Experience
*High-Budget 3D Cyber-Fashion & Retro-Futuristic Digital Flagship*

---

## 1. Project Brief & Vision
**ZENOS** is conceived not as a conventional e-commerce storefront, but as a continuous cinematic fashion film and interactive digital universe. Channeling the aesthetics of early-2000s speculative sci-fi interfaces, biomechanical fashion, and luxury cyber-couture, ZENOS reimagines retail as an art-directed 3D experience where the visual spectacle is the primary artifact.

- **Brand Personality**: Rebellious, Experimental, Hyper-Futuristic, Visually Obsessive, Premium Luxury.
- **Concept Core**: *"Built for the year 2000 imagining 2045."*
- **Target Device**: Desktop-first immersive experience with responsive viewport adaptation.

---

## 2. Visual Architecture & Design Language

### A. Materiality & Texture System
- **Liquid Chrome & Metallic Surfaces**: Specular reflections, metallic gradient borders (`linear-gradient(135deg, #fff, #475569, #0f172a)`), and high-gloss finishes simulating electro-plated aerospace alloys.
- **Translucent Glass & Optics**: Multi-layered backdrop blurs (`backdrop-blur-md` to `backdrop-blur-2xl`), frosted acrylic frames, and 0.45-opacity glassmorphic containers.
- **CRT & HUD Overlay**: Scanline overlays via procedural fragment shaders, crosshair cursor trackers, precision coordinate readouts (`[00°24'E // TOKYO // NEO-EARTH]`), and monospace telemetry tags.
- **Iridescent Light Bleed**: Diffuse radial glows in electric cyan (`#00f0ff`), neon ultraviolet (`#a855f7`), and hot magenta (`#ff007f`) with subtle bloom falloffs.

---

## 3. Color Palette & Lighting Tokens

| Role | Color Name | Hex / Value | Usage |
| :--- | :--- | :--- | :--- |
| **Canvas Background** | Deep Void Black | `#030712` / `#000000` | Global ambient depth |
| **Surface Dark** | Graphite Titanium | `#0b0f19` / `#111622` | Card panels, floating modules |
| **Accent Primary** | Hyper Cyan | `#00f5ff` | Status beacons, interactive buttons, HUD data |
| **Accent Secondary** | Electric Magenta | `#ff007f` | Specular highlights, gradient stops |
| **Accent Tertiary** | Ultraviolet Violet | `#8b5cf6` | Ambient light cones, badge accents |
| **Metal Neutral** | Liquid Chrome | `#e2e8f0` to `#ffffff` | Hero typography, specular borders |
| **Muted Telemetry** | Tactical Slate | `#64748b` | Monospace specs, technical readouts |

---

## 4. Typography Hierarchy

### Display Headings
- **Typeface**: `Syne` / `Syncopate` / `Space Grotesk` (Extended Bold/Black, uppercase, tight tracking: `-0.05em`).
- **Hero Headline**: `clamp(3.5rem, 8vw, 7.5rem)`, chrome linear gradient text mask with liquid sheen.
- **Section Titles**: Massive scale with two-tone contrasting fills (e.g., solid chrome + glowing electric gradient).

### Monospace & Telemetry
- **Typeface**: `JetBrains Mono` / `Space Mono` / `Courier New`.
- **Styling**: `0.7rem` to `0.8rem`, uppercase, tracking `0.15em` to `0.25em`, prefixed with technical syntax (e.g., `// SCENE 02`, `FREQ: 144.80 GHz`, `STATUS: READY`).

### Body & Interface Copy
- **Typeface**: `Inter` / `Space Grotesk`.
- **Styling**: Clean, high-legibility geometric sans-serif balancing dense technical specs with crisp luxury readability.

---

## 5. 3D & WebGL Integration Architecture

1. **Procedural WebGL Liquid Chrome Background (`<webgl-shader>`)**:
   - Built on high-performance GLSL fragment pipeline.
   - Dual-octave Simplex noise producing fluid, viscous organic waves.
   - Dynamic Fresnel normal calculations calculating specular chrome highlights based on cursor coordinates (`u_mouse`).
   - Integrated chromatic dispersion and subtle CRT horizontal scanline noise.

2. **Interactive Three.js Cranial Rig (`<threejs-scene>`)**:
   - **Specimen**: *Exopod EXO-01* Biomechanic Wearable Sound System.
   - **Geometry**: Custom compound group consisting of a scaled spheroid chrome core, wireframe pulsating energy nucleus (icosahedron), three independent floating orbital rings (torus geometries) tilting across X/Y/Z axes, and four aerodynamic sensor vanes.
   - **Particles**: 280-node dual-tone holographic particle cloud surrounding the central mesh.
   - **Interactivity**: Inertia mouse-parallax orientation tracking + scroll-driven continuous spin and elevation shifts.

---

## 6. Scene-by-Scene Narrative Flow

- **Header / Telemetry Bar**: Floating translucent capsule with live status indicators, frequency markers, audio toggle, and sliding cart drawer trigger.
- **Scene 01 // Spatial Stage**: Enormous `BEYOND CHROME REALITY` text, live technical metrics (Tensile strength, Refractive index, Mass coefficient), and direct 3D viewport control.
- **Scene 02 // Product Reveal (The Genesis Vault)**: The Exopod EXO-01 centerpiece showcased with spatial latency details, bone-conduction specs, and dynamic add-to-cart controls.
- **Scene 03 // Architectural Deconstruction**: 4-column biometric schematics grid detailing titanium exoskeletons, neo-transducers, and anti-reflective optics.
- **Scene 04 // Spatial Runway**: Non-standard floating cards featuring cyber-wear artifacts (Chromium Puffer, Matrix Cyber-Visor, Biomechanic Strider).
- **Scene 05 // Cinematic Manifesto**: 35mm anamorphic widescreen film frame with animated HUD scanlines and brand philosophy statement.
- **Scene 06 // The Acquisition Vault**: High-speed cyber-commerce checkout matrix with real-time drawer synchronization.
- **Scene 07 // The Nexus**: Movie credit-scale brand typography, cryptographic VIP access form, and operational protocol directory.
