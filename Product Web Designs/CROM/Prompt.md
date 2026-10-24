# CROM Landing Page Generation Prompt

The following prompt was used to engineer the interactive product landing page experience:

```markdown
You are reverse-engineering a premium interactive product landing page from the supplied screen recording.
The screen recording is the PRIMARY SOURCE OF TRUTH.
Do not invent a different design.
Do not redesign the website according to generic landing-page conventions.
Your job is to reproduce the visual language, composition, section order, typography hierarchy, product presentation, transitions, motion, and scroll behavior shown in the recording as closely as technically possible.

IMPORTANT:
The screen recording contains the host application's UI / browser / Stitch interface around the webpage.
IGNORE:
- browser chrome
- browser tabs
- address bar
- Stitch / Artifacts sidebar
- editor controls
- external tool UI
REPRODUCE ONLY THE ACTUAL WEBSITE.

==================================================
OVERALL VISUAL IDENTITY
==================================================
The site is a high-end futuristic fashion / technology product experience.
It should feel like:
luxury fashion campaign
+
technical product presentation
+
digital editorial
+
futuristic product laboratory.

Visual characteristics:
- near-black background (#050505)
- extremely dark charcoal
- subtle black grid / dark blueprint CAD paper texture
- technical typography (condensed bold uppercase + monospaced telemetry)
- small uppercase labels
- thin technical borders (hairlines)
- blueprint-like information architecture
- metallic product imagery
- electric blue highlights (#00f0ff)
- deep violet / purple materials
- occasional neon lime, pink, orange and blue product colors
- very restrained color usage around the primary black environment
- product imagery is the visual hero

The site should NOT feel like:
- generic ecommerce
- ordinary fashion store
- SaaS
- minimal Apple-style landing page
- standard portfolio
- generic 3-column card layout.

==================================================
BACKGROUND
==================================================
The dominant page environment is:
#050505 / near-black.
Use a very subtle technical grid resembling fine engineering paper + dark blueprint + technical CAD environment.
Grid should be subtle enough to disappear into the black background.

==================================================
TYPOGRAPHY
==================================================
Use large uppercase display statements combined with tiny technical labels, metadata, measurements, product specifications, and microcopy:
- Display: Condensed, uppercase, compact, large, tight, architectural.
- Technical text: Small, monospaced or technical sans, widely spaced, low visual weight.

==================================================
SCENE 01 — OPENING / HERO
==================================================
- Suspended weightless futuristic jacket centered and floating in a dark laboratory space.
- Sub-system telemetry markers, CAD reticles, coordinate metadata.
- Clean, minimal, balanced header with brand wordmark and streamlined navigation.

==================================================
SCENE 02 — DETAILS MATTER / ANATOMY
==================================================
- Large architectural statement paired with macro anatomical product inspection.
- Technical specification blocks (operating envelope, tensile rating, ultrasonic welds, Fidlock titanium couplings).

==================================================
SCENE 03 — COLLECTIONS (CHROMATIC BAYS)
==================================================
- Tactical lineup of four distinct colorways:
  1. Acid Tactical (Electric Lime Green)
  2. Hyperion Glow (Neon Magenta)
  3. Thermal Hazard (Safety Orange)
  4. Obsidian Core (Electric Blue Luminescent)
- High-tech bay frames with allocation meters and interactive variant selectors.

==================================================
SCENE 04 — TECHNOLOGY ENGINEERED TO ENDURE
==================================================
- Exploded isometric composite material stack showcasing 4 distinct layers:
  1. Hydrophobic Aerospace Membrane
  2. Hexagonal Micro-Mesh
  3. Technical Aerogel Core
  4. Carbon-Weave Exoskeleton

==================================================
SCENE 05 — NEED TO KNOW
==================================================
- Dense engineering spec columns: climatic envelope (-40°C to +85°C), cryptographic NFC authentication chip, serialized limited allocation batch.

==================================================
SCENE 06 & 07 — RESPONSIVE HARDWARE SIMULATION
==================================================
- Centered titanium laptop workstation displaying a live simulation of the website experience.
- Mobile companion terminal displaying the adapted portrait viewport.
```
