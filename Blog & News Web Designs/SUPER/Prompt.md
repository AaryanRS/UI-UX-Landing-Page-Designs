{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "project": {
    "name": "SUPER",
    "type": "Digital Editorial Publication & Cultural Magazine",
    "device_target": "desktop",
    "aesthetic": "Cinematic Editorial Noir + Dark Luxury Publication + Experimental Typographic Brutalism"
  },
  "design_system": {
    "theme_mode": "dark",
    "color_palette": {
      "surface_background": "#181818",
      "text_primary": "#EBDCC4",
      "text_secondary": "#B6A596",
      "accent_terracotta": "#DC9F85",
      "border_structural": "#66473B",
      "divider_dark": "#35211A"
    },
    "typography": {
      "display": {
        "family": "Clash Grotesk, Syne, sans-serif",
        "scale_desktop": "11.5vw",
        "scale_mobile": "16vw",
        "line_height": "0.85",
        "letter_spacing": "-0.04em",
        "transform": "uppercase",
        "weight": "800"
      },
      "body": {
        "family": "General Sans, Inter, sans-serif",
        "weights": [300, 400],
        "line_height": "1.65"
      },
      "metadata": {
        "family": "General Sans, JetBrains Mono, monospace",
        "scale": "0.6875rem to 0.75rem",
        "transform": "uppercase",
        "letter_spacing": "0.15em",
        "weight": "600"
      },
      "special_effects": {
        "dual_layer_headlines": {
          "front_layer": {
            "color": "#EBDCC4"
          },
          "back_layer": {
            "fill": "transparent",
            "text_stroke": "1px #66473B",
            "offset": "4px 4px"
          }
        }
      }
    },
    "surface_treatment": {
      "corner_radius_max": "4px",
      "borders": "1px solid #66473B",
      "shadows": "none",
      "glassmorphism": "disabled",
      "gradients": "disabled",
      "texture_overlay": "3% opacity SVG fractal-noise film grain filter across entire viewport"
    }
  },
  "layout_and_sections": {
    "grid": "12-column asymmetric editorial layout with 5-7vw outer margins",
    "sections": [
      {
        "id": "01_header",
        "component": "Minimal Editorial Masthead",
        "elements": [
          "SUPER bold typographic wordmark",
          "Clean section links: JOURNAL, CULTURE, DESIGN, TECH, ARCHITECTURE, IDEAS",
          "Minimal text search trigger",
          "Hairline border CTA: GET THE ISSUE"
        ],
        "constraints": "Strictly no cluttered timestamps, ticker noise, or rounded pill shapes"
      },
      {
        "id": "02_hero",
        "component": "Asymmetrical Lead Story",
        "headline": "THE SILENT PROJECT OF MONOLITH",
        "imagery": "Cinematic brutalist concrete structure in desert twilight",
        "metadata": ["Coordinates", "Curatorial Notes", "Reading Time"]
      },
      {
        "id": "03_category_strip",
        "component": "1px Hairline Filter Ledger",
        "items": ["ALL", "CULTURE", "DESIGN", "TECH", "ARCHITECTURE", "FASHION", "IDEAS"],
        "active_indicator": "#DC9F85 underline"
      },
      {
        "id": "04_dispatches",
        "component": "Asymmetric 12-Column Editorial Grid",
        "modules": [
          {"span": "5 cols", "type": "High-fashion sculptured silhouette"},
          {"span": "3 cols", "type": "Obsidian & titanium acoustic artifact"},
          {"span": "4 cols", "type": "Raw concrete & cedar alpine library"}
        ]
      },
      {
        "id": "05_typographic_break",
        "component": "Full-bleed Manifesto Spread",
        "statement": "WE ARE LIVING THROUGH THE NEXT VERSION.",
        "treatment": "Oversized dual-layer text with minimal editorial telemetry"
      },
      {
        "id": "06_most_read",
        "component": "Vertical Numbered Archive Ledger",
        "style": "Numbered 01-04 list separated by 1px dark dividers with terracotta hover shifts"
      },
      {
        "id": "07_featured_issue",
        "component": "Print Edition Showcase",
        "issue_title": "SUPER / THE NEW HUMAN MACHINE",
        "specifications": ["284 Pages", "140 GSM", "Berlin Offsets", "€18.00 EUR"]
      },
      {
        "id": "08_dossiers",
        "component": "Disciplinary Dossiers",
        "topics": ["Culture Quotes", "Material Studies", "Post-Web Networks Telemetry", "Desert Fortress Elevation"]
      },
      {
        "id": "09_dispatch_terminal",
        "component": "The Super Letter Newsletter Dispatch",
        "headline": "THE WEEK'S BEST IDEAS, DELIVERED.",
        "badge": "64x64px rotating circular SVG seal (SUPER • NEW ISSUE •)"
      },
      {
        "id": "10_colophon",
        "component": "Editorial Footer",
        "elements": ["Massive watermarked SUPER typography", "Directory links", "Legal colophon"]
      }
    ]
  }
}
