```json
{
  "project_name": "REFLECT",
  "archetype": "Industrial Disruptor Landing Page",
  "theme": {
    "style": "Neo-Brutalist Industrial Architecture",
    "color_palette": {
      "primary_canvas": "#121212",
      "contrast_surface": "#FFFFFF",
      "signature_accent": "#CCFF00",
      "border_and_shadow": "#000000",
      "muted_text": "#475569"
    },
    "typography": {
      "headline_font": "Ranchers",
      "headline_specs": "All-caps, tight leading (0.85), font-size 80px to 180px, hard text shadow",
      "monospace_font": "Space Mono",
      "monospace_specs": "Uppercase, tracking 0.1em, bold technical labels and status codes",
      "numeric_font": "Archivo",
      "numeric_specs": "Bold numbers 40px+ for counters and timer units",
      "body_font": "Plus Jakarta Sans",
      "body_specs": "Legible sans-serif for body descriptions and subheadlines"
    },
    "borders_and_shadows": {
      "borders": "Solid 4px or 8px black (#000000), strictly no rounded corners > 8px",
      "shadows": "Hard neo-shadows, strictly solid offset 4px-8px x 4px-8px (#000000 or #FFFFFF), zero blur/spread",
      "prohibitions": "No gradients, no pastel colors, no soft blurred shadows, no glassmorphism"
    }
  },
  "layout_structure": {
    "sidebar": {
      "type": "Fixed right vertical rail",
      "width": "200px",
      "strips": [
        { "id": "01", "label": "DESIGN", "bg": "#FFFFFF", "text_color": "#000000", "mode": "vertical-rl" },
        { "id": "02", "label": "BUILD", "bg": "#CCFF00", "text_color": "#000000", "mode": "vertical-rl" },
        { "id": "03", "label": "SHIP", "bg": "#000000", "text_color": "#CCFF00", "mode": "vertical-rl" }
      ]
    },
    "navigation_header": {
      "sticky": true,
      "background": "#FFFFFF",
      "border_bottom": "4px solid #000000",
      "elements": [
        "Rotated 3-degree black square logo mark with white icon",
        "Brand wordmark 'REFLECT SYS' in Plus Jakarta Sans ExtraBold 30px",
        "Telemetry status badge 'SYS_ONLINE v2.4' in Space Mono with neo-shadow",
        "Brutalist 'JOIN BETA' button with 4px border and hover offset"
      ]
    },
    "hero_section": {
      "background": "#121212 with subtle technical grid overlay",
      "badge": "Tilted sticker container (rotate -2deg) 'INDUSTRIAL DISRUPTOR PROTOCOL // SPEED X HIGH-OUTPUT'",
      "headline": "SHIP AT VOLT SPEED.",
      "headline_font": "Ranchers, 150px-180px, Volt Green #CCFF00 with solid 6px black shadow",
      "subheadline": "2xl italicized manifesto copy in Plus Jakarta Sans",
      "form": {
        "style": "Fused Brutalist input and button",
        "border": "4px solid #000000",
        "shadow": "8px 8px 0px #000000",
        "input": "White surface, Space Mono placeholder",
        "button": "Black surface with Ranchers/Space Mono label, hover inversion"
      },
      "countdown_timer": {
        "units": ["DAYS", "HOURS", "MINS", "SECS"],
        "style": "Modular high-contrast boxes with Archivo 40px numbers, Space Mono labels, 4px border, 8px neo-shadow"
      }
    },
    "social_proof_bar": {
      "background": "#FFFFFF",
      "border": "4px solid #000000",
      "cards": [
        {
          "rotation": "-1.5deg",
          "avatar": "AX",
          "operator": "ALEX V. // ARCHITECT",
          "quote": "DEPLOY TIME CUT FROM 45 MINUTES TO 8 SECONDS FLAT."
        },
        {
          "rotation": "1.8deg",
          "avatar": "MK",
          "operator": "MIRA K. // FOUNDER",
          "quote": "NO SOFT PASTEL FLUFF, JUST BRUTAL RAW POWER AND INSTANT RELIABILITY."
        },
        {
          "rotation": "-0.8deg",
          "avatar": "DR",
          "operator": "DAN R. // LEAD SRE",
          "quote": "THE NEO-BRUTALIST ARCHITECTURE ELIMINATES UNNECESSARY DOM OVERHEAD."
        }
      ]
    },
    "comparison_section": {
      "title": "OLD DECAY VS INDUSTRIAL VELOCITY",
      "rows": [
        {
          "left_deprecated": { "status": "DEPRECATED", "title": "SLUGGISH BLOAT", "bg": "#000000", "text": "#475569" },
          "right_accelerated": { "status": "ACCELERATED", "title": "INSTANT SHIP", "bg": "#CCFF00", "text": "#000000" }
        },
        {
          "left_deprecated": { "status": "FRAGILE", "title": "FRAGILE CHAOS", "bg": "#000000", "text": "#475569" },
          "right_accelerated": { "status": "IMMUTABLE", "title": "HARDENED CORE", "bg": "#CCFF00", "text": "#000000" }
        },
        {
          "left_deprecated": { "status": "STALLED", "title": "DESIGN DEBT", "bg": "#000000", "text": "#475569" },
          "right_accelerated": { "status": "DOMINANT", "title": "MAX OUTPUT", "bg": "#CCFF00", "text": "#000000" }
        }
      ]
    },
    "process_blueprint": {
      "background": "#121212",
      "title": "THE 3-STAGE BLUEPRINT",
      "spec_tag": "[ ARCHITECTURE SPEC V4.00 ]",
      "columns": [
        { "step": "01", "name": "EXTRACT & DECONSTRUCT", "bg_watermark": "01", "shadow": "8px 8px 0px #FFFFFF" },
        { "step": "02", "name": "FORGE NEO-SYSTEMS", "bg_watermark": "02", "shadow": "8px 8px 0px #FFFFFF" },
        { "step": "03", "name": "SHIP WITHOUT FRICTION", "bg_watermark": "03", "shadow": "8px 8px 0px #FFFFFF" }
      ]
    },
    "waitlist_terminal": {
      "container": "Volt green #CCFF00 outer badge wrapper with black 4px border",
      "headline": "COMMENCE DISRUPTION.",
      "cli_output": "Terminal preview displaying initialized neo-brutalist spec verification logs",
      "form_cta": "High-precision input with REQUEST KEYS button trigger"
    }
  }
}
```