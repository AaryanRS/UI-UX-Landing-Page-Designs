# KRONOS 01 — Master Generation & Implementation Prompt

Use the prompt below to recreate this precision technical audio and kinematic landing page design:

```markdown
# Summary
A poster-scale wordmark interlocked with a photographic product subject on a two-colour achromatic ground, with monospaced technical metadata pinned to every edge. Scroll drives the product's own mechanic rather than decorative motion, and the page is complete and readable before any of it runs.

# Style
Cool achromatic ground with near-black ink and exactly one saturated signal accent used for emphasis and never as a fill. Display type is a heavy grotesk at poster scale with tight negative tracking; everything that is not the headline is small monospaced metadata with wide positive tracking. Depth comes from real photography and hairlines, never from shadows, gradient glows or cards.

## Spec
Apply an achromatic technical-product style.
- Palette:
  - Ground: #EFEFEE
  - Dimmer stage ground: #E4E4E2
  - Dark ink: #0D0D0F
  - Secondary ink: #43444A
  - Muted ink: #6E6F76
  - Signal accent: #2F5BFF (with #7C97FF as its lift on dark grounds)
  - Hairlines: rgba(13, 13, 15, 0.12)
- Typography:
  - Display: 'Archivo', weights 700–900, letter-spacing -0.04em to -0.055em, line-height 0.74 to 0.98
  - Metadata & labels: 'IBM Plex Mono', weights 400–500, font-size 10–12px, letter-spacing +0.14em to +0.16em, uppercase
- Animation easing: cubic-bezier(0.16, 1, 0.3, 1) at 0.85s–1.25s
- Border radius: 0px everywhere except pill buttons and chip badges.
- Rules:
  - Commit to exactly two colours plus one accent.
  - Accent only appears as small type, a status dot, a rule, or a single trace — never as a solid container fill or large block.
  - Constant layer of small monospaced metadata pinned to corners and edges.
  - DO NOT use hero gradient banners, decorative glows, dot/line grid backdrops, bento grids, card rows, or drop shadows on anything except the cut-out subject.

# Layout & Structure
Seven full-width sections that alternate ground colour with true scrolling:

1. Navigation Bar (Fixed 64px):
   - Background #EFEFEE at 82% opacity with 14px backdrop-blur and 1px bottom hairline.
   - Left: Brand mark "KRONOS." in Archivo 800 at 16px, tracking -0.035em, followed by an accent dot #2F5BFF.
   - Right: Five mono navigation links at 11px, tracking 0.14em, uppercase, with rounded pill background chips and padding, hover state transitioning border/accent, followed by a high-contrast pill CTA "SPEC ORDER".

2. Hero Stage (Full viewport minus nav, #E4E4E2 ground, overflow: clip, isolation: isolate):
   - Left column: Mono eyebrow, display headline at clamp(34px, 5.1vw, 74px) with final phrase in accent blue, 38ch lede description, dual pill buttons ("CONFIGURE UNIT", "VIEW METROLOGY"), and a hairline-topped block of three mono telemetry lines.
   - Right column: Precision acoustic transducer cut-out placed low and wide, overlapping the bottom wordmark. Integrated optical reticle ring with blue laser index marks and ambient hover/drift float.
   - Occlusion Weave: Giant poster wordmark "KRONOS" rendered across two exact flex layers (back layer z-index: 1, front layer z-index: 3 rendering only the overlapping letter "O", subject at z-index: 2).

3. Inverted Proof Section (Full-bleed ink ground #0D0D0F):
   - Left: Display headline "HARMONIC DISTORTION DISPLACEMENT.", lede, huge tabular figure "0.008 % THD+N" at clamp(56px, 9vw, 132px), mono legend.
   - Right: Real-time dynamic SVG graph of two line traces: faint reference wave wandering up to 4.2% THD vs. flat blue signal accent trace (#7C97FF) holding strictly under 0.008%, generated with summed sine terms.

4. Structural Milling & Air-Gap Diagram:
   - Left: Display headline, engineering notes, and hairline-ruled definition list (01 / GAP TOLERANCE, 02 / CHUCK TORQUE, 03 / THERMAL FLUX, 04 / SHIELD DAMP).
   - Right: To-scale orthographic CAD projection with millimeter hairline construction geometry, datum markers, and accent callout indicators.

5. Stage 04 — Scroll-Locked 360° Dual Kinematic Rotor:
   - 400vh tall scroll track containing a position:sticky 100svh viewport stage.
   - Locks scroll progression until the 360° mechanical rotation sequence completes.
   - Central 4-vane kinematic rotor with goniometer dial (000°, 090°, 180°, 270°), crosshairs, and synchronized rotation.
   - Background display text counter-translates horizontally across the canvas in exact ratio to the scroll velocity.
   - Real-time live telemetry readouts at bottom-left and bottom-right displaying Radial Position (000.0° to 360.0°), Angular Velocity, and Vector (X / Y) offsets.

6. Runtime Field-Swap Metallurgy Matrix:
   - Dynamic variant selector with pill buttons (Ti-6Al-4V Raw Titanium, Deep Graphite, Ceramic Bead).
   - Repaints the entire section field dynamically (background and ink) over 0.7s using color-mix to prevent border collapse.

7. Technical Audit Table & Bookend Close:
   - 12-row dual-column technical specification table ruled by hairlines.
   - Final CTA module ("DEPLOY KRONOS TO LAB WORKBENCH.") with CAD download button and order button.
   - Cropped brand wordmark "KRONOS" at clamp(84px, 19.5vw, 300px) translated down 0.19em at the bottom edge.
```
