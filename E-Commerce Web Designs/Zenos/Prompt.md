{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "project": {
    "name": "ZENOS",
    "edition": "2000-2045 Genesis",
    "classification": "Y2K Cinematic E-Commerce & Interactive Digital Flagship",
    "device_target": "desktop"
  },
  "visual_direction": {
    "theme": "Y2K Retro-Futurism + Biomechanical Cyber-Wear + 3D Luxury CGI",
    "moodboard": [
      "Liquid chrome and high-specular reflective metals",
      "Translucent frosted glass and optics",
      "Early-2000s tactical HUD and sci-fi computer interfaces",
      "CRT scanlines and subtle optical chromatic aberration",
      "Weightless floating geometry in deep void space",
      "Cinematic fashion commercial pacing"
    ],
    "anti_patterns": [
      "Generic flat SaaS cards and repetitive 3-column grids",
      "Muted corporate pastel palettes",
      "Static non-interactive product thumbnails",
      "Standard cookie-cutter e-commerce headers"
    ]
  },
  "color_palette": {
    "background": {
      "primary": "#030712",
      "secondary": "#0b0f19",
      "surface_elevated": "rgba(17, 24, 39, 0.75)"
    },
    "metallic": {
      "chrome_white": "#ffffff",
      "chrome_specular": "#e2e8f0",
      "graphite_dark": "#1e293b",
      "metallic_border": "linear-gradient(135deg, rgba(255,255,255,0.4), rgba(71,85,105,0.2), rgba(15,23,42,0.8))"
    },
    "accents": {
      "cyan_glow": "#00f5ff",
      "ultraviolet_purple": "#8b5cf6",
      "hot_magenta": "#ff007f",
      "acid_green_indicator": "#10b981"
    }
  },
  "typography": {
    "display": {
      "font_family": "Syne, Syncopate, Space Grotesk, sans-serif",
      "letter_spacing": "-0.04em",
      "text_transform": "uppercase",
      "treatment": "Oversized bold display with chrome specular gradients and drop-glows"
    },
    "interface_and_body": {
      "font_family": "Space Grotesk, Inter, sans-serif",
      "weights": ["400", "500", "600"],
      "treatment": "Clean geometric sans with high contrast against dark backdrops"
    },
    "technical_metadata": {
      "font_family": "JetBrains Mono, Space Mono, monospace",
      "size": "0.75rem",
      "letter_spacing": "0.15em",
      "text_transform": "uppercase",
      "prefix_convention": "// SPEC // FREQ // STATUS"
    }
  },
  "interactive_components": {
    "webgl_shader_backdrop": {
      "type": "custom_glsl",
      "features": [
        "Simplex noise-based multi-octave liquid chrome fluid simulation",
        "Mouse-coordinate parallax normal displacement",
        "Fresnel specular highlights in iridescent cyan and magenta",
        "CRT scanline overlay and soft vignette"
      ]
    },
    "threejs_hero_artifact": {
      "specimen": "Exopod EXO-01 Biomechanical Sound Receptor",
      "components": [
        "Scalable chrome central core mesh with high shininess",
        "Pulsing wireframe internal energy nucleus",
        "3 dynamic orbital concentric rings with independent axis rotation",
        "4 aerodynamic metallic directional vanes",
        "280-node dual-color ambient particle cloud",
        "Inertia-smoothed cursor tracking and scroll-reactive tumble"
      ]
    },
    "ui_systems": [
      {
        "name": "Floating Chrome Pill Header",
        "features": ["Status beacon", "Spatial coordinates readout", "Sound simulator toggle", "Interactive slide-over cart counter"]
      },
      {
        "name": "Custom Crosshair Cursor",
        "features": ["Targeting outer reticle with mix-blend-difference", "High-precision glowing core tracking pointer"]
      },
      {
        "name": "Cyber-Bag Slide Drawer",
        "features": ["Real-time subtotal calculator", "Instant item removal", "Biometric checkout CTA"]
      }
    ]
  },
  "scene_breakdown": [
    {
      "scene_index": 1,
      "title": "Intro // Spatial Stage",
      "composition": "Hero headline 'BEYOND CHROME REALITY' overlaid on Three.js specimen with tactical telemetry meters"
    },
    {
      "scene_index": 2,
      "title": "Product Reveal // The Genesis Vault",
      "composition": "Exopod EXO-01 spotlight showcase with liquid chrome pill indicators and dual ambient rim glow"
    },
    {
      "scene_index": 3,
      "title": "Architectural Deconstruction",
      "composition": "4-part technical specifications matrix with glowing cyan and magenta wireframe badges"
    },
    {
      "scene_index": 4,
      "title": "Spatial Runway // Cyber-Wear Collection",
      "composition": "Non-standard asymmetric product cards featuring floating apparel with badge tags and quick-add actions"
    },
    {
      "scene_index": 5,
      "title": "The Manifesto // Film Still 04",
      "composition": "35mm anamorphic widescreen cinematic frame with scanlines and 'BUILT FOR THE YEAR 2000 IMAGINING 2045' statement"
    },
    {
      "scene_index": 6,
      "title": "Acquisition Vault // Commerce Grid",
      "composition": "High-density cyber-catalog with direct cart synchronization, fiat/crypto indicator, and instant procurement buttons"
    },
    {
      "scene_index": 7,
      "title": "The Nexus // Monumental Finale",
      "composition": "Gigantic branded wordmark backdrop, cryptographic drop notification terminal, and technical security footer"
    }
  ]
}
