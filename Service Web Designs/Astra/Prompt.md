{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "project": {
    "name": "ASTRA",
    "type": "service_landing_page",
    "version": "1.0.0",
    "target_device": "desktop"
  },
  "aesthetic": {
    "theme": "Kinetic Brutalism",
    "mood": ["urgent", "technical", "high-velocity", "monumental", "digital-first"],
    "negative_constraints": [
      "no gradients",
      "no soft drop shadows",
      "no pastel hues",
      "no rounded card corners (pill controls only)",
      "no generic sans-serif display headings"
    ]
  },
  "color_palette": {
    "primary_background": "#FF4D00",
    "solid_black": "#000000",
    "pure_white": "#FFFFFF",
    "selection": {
      "background": "#000000",
      "text": "#FF4D00"
    },
    "borders": {
      "primary": "2px solid #000000",
      "subtle_dark": "1px solid rgba(255, 255, 255, 0.20)"
    }
  },
  "typography": {
    "display": {
      "family": "Archivo Black, sans-serif",
      "transform": "UPPERCASE",
      "letter_spacing": "-0.04em",
      "line_height": "0.85 - 0.90",
      "scales": {
        "hero": "16vw",
        "cta": "14vw",
        "services": "6.5vw - 7vw",
        "marquee_primary": "10vw",
        "marquee_secondary": "9vw"
      }
    },
    "metadata_and_ui": {
      "family": "Space Mono, monospace",
      "letter_spacing": "-0.02em",
      "weights": ["400", "700"],
      "font_sizes": {
        "nav_pill": "12px",
        "scroll_indicator_text": "9px",
        "badge_tags": "11px",
        "telemetry_labels": "12px"
      }
    },
    "body": {
      "family": "Inter, sans-serif",
      "weights": ["400", "500", "600"],
      "font_size": "14px - 16px"
    }
  },
  "components": {
    "floating_navigation": {
      "position": "fixed",
      "top": "0",
      "left": "0",
      "width": "100%",
      "z_index": 50,
      "items": {
        "logo_left": "ASTRA with #FF4D00 accent square and [SYS_2025] badge",
        "center_pill": {
          "background": "#000000",
          "shape": "rounded-full",
          "links": ["Services", "Protocols", "Telemetry", "Contact"],
          "hover_transition": "background: #FFFFFF; color: #000000"
        },
        "status_right": "Live ping indicator, online telemetry status, social icon set"
      }
    },
    "hero_section": {
      "background": "#FF4D00",
      "text_color": "#000000",
      "min_height": "100vh",
      "headline": "ASTRA",
      "size": "16vw",
      "divider": "2px solid #000000",
      "metadata_row": {
        "col_left": "Based in Berlin & Tokyo, coordinates, UTC+1",
        "col_center": {
          "component": "Rotating Scroll Indicator",
          "diameter": "144px",
          "svg_text_path": "SCROLL DOWN • SCROLL DOWN • SCROLL DOWN • SCROLL DOWN •",
          "animation_duration": "12s linear infinite",
          "center_icon": "lucide arrow-down in #FF4D00 on black circle"
        },
        "col_right": "Discipline overview, architecture protocols, contract status"
      }
    },
    "skewed_marquee_section": {
      "background": "#000000",
      "skew_angle": "-2deg",
      "borders": "2px solid #000000",
      "overflow": "hidden",
      "rows": [
        {
          "index": 1,
          "direction": "left",
          "font_size": "10vw",
          "color": "#FF4D00",
          "font": "Archivo Black",
          "text": "URGENCY • TECHNICAL SOPHISTICATION • KINETIC BRUTALISM • HIGH CONTRAST • ZERO NOISE •"
        },
        {
          "index": 2,
          "direction": "right",
          "font_size": "9vw",
          "color": "rgba(255, 255, 255, 0.8)",
          "font": "Archivo Black",
          "text": "FULL-STACK ARCHITECTURE • PERFORMANCE AUDITING • WEBGL INTERFACES • HARDWARE SYNC •"
        }
      ]
    },
    "service_list": {
      "background": "#000000",
      "text_color": "#FFFFFF",
      "divider": "1px solid rgba(255, 255, 255, 0.2)",
      "items": [
        {
          "index": "01/",
          "title": "SYSTEM ARCHITECTURE",
          "tags": ["Distributed Clouds", "Kubernetes", "Sub-10ms Latency"]
        },
        {
          "index": "02/",
          "title": "BRUTALIST WEB INTERFACES",
          "tags": ["Kinetic Typography", "WebGL Shaders", "Zero-Layout Shift"]
        },
        {
          "index": "03/",
          "title": "DATA ENGINEERING & APIS",
          "tags": ["GraphQL Engine", "Event Streaming", "PostgreSQL Tuning"]
        },
        {
          "index": "04/",
          "title": "SECURITY INFRASTRUCTURE",
          "tags": ["Zero-Trust Auth", "Penetration Stress", "SOC2 Type II Ready"]
        }
      ],
      "hover_interactions": {
        "row_bg": "rgba(255, 255, 255, 0.05)",
        "title_transform": "translateX(16px)",
        "title_color": "#FF4D00",
        "arrow_icon": {
          "visibility": "opacity: 1",
          "transform": "rotate(45deg)"
        }
      }
    },
    "giant_cta_and_footer": {
      "cta": {
        "background": "#FF4D00",
        "headline": "LET’S BUILD",
        "headline_size": "14vw",
        "button": {
          "background": "#000000",
          "text": "#FFFFFF",
          "label": "INITIALIZE WORKFLOW",
          "shape": "rounded-full",
          "hover_transform": "scale(1.10)",
          "icon": "arrow-right in #FF4D00"
        }
      },
      "footer": {
        "divider": "2px solid #000000",
        "copyright": "© 2025 ASTRA KINETIC STUDIO. ALL RIGHTS RESERVED.",
        "nav": ["Twitter (X)", "GitHub", "LinkedIn", "Telegram"]
      }
    }
  }
}
