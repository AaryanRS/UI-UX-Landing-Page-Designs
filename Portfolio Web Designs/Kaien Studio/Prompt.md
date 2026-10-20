# System Generation Prompt: Experimental Editorial Product Designer Portfolio

The following master prompt was utilized to construct the design system, brand assets, app shell, and assembled portfolio landing page:

```json
{
  "project": {
    "name": "Experimental Editorial Product Designer Portfolio",
    "type": "portfolio_landing_page",
    "goal": "Create a visually exceptional portfolio landing page for a UI/UX and Product Designer. The experience should feel editorial, art-directed, experimental, typography-heavy, image-led, and highly intentional. Avoid the visual language of generic SaaS websites, template portfolios, startup landing pages, or overly futuristic dashboards.",
    "design_direction": [
      "editorial art direction",
      "experimental composition",
      "gallery-inspired portfolio",
      "typography as a visual object",
      "asymmetric layouts",
      "layered imagery",
      "large negative space",
      "strong geometric framing",
      "cinematic scroll storytelling",
      "camera-like zoom transitions",
      "high visual polish"
    ],
    "visual_priority": "Extremely high. Every element should feel deliberately designed. Do not leave default-looking cards, buttons, typography, spacing, icons, or image placements.",
    "content_priority": "Showcase design thinking, product design quality, visual taste, and selected work rather than filling the page with unnecessary copy."
  },
  "canvas": {
    "desktop_reference_width": "1440px",
    "desktop_reference_height": "900px",
    "background": "#F7F5EF",
    "text": "#111111",
    "primary_palette": {
      "lavender": "#BFA7FF",
      "chartreuse": "#D8FF3E",
      "tomato_red": "#FF5B4D",
      "black": "#111111",
      "warm_white": "#F7F5EF"
    },
    "palette_usage": {
      "lavender": "Large visual fields, selected work sections, image backplates, oversized decorative shapes, hover states",
      "chartreuse": "Primary accents, labels, active indicators, buttons, highlights, small graphic interventions",
      "tomato_red": "Attention moments, selected work accents, editorial markers, CTA accents, image overlays",
      "black": "All primary text, major lines, navigation, borders, icons, typography, and structural details",
      "warm_white": "Main page background and breathing space"
    },
    "color_behavior": "Use the colors in confident blocks rather than tiny decorative accents. The palette should feel curated and editorial, not playful or childish."
  },
  "typography": {
    "display_font": {
      "family": "Syne",
      "role": "Large headlines, hero typography, section titles, project names, oversized editorial statements",
      "weights": ["600", "700", "800"],
      "character": "expressive, artistic, slightly unconventional, geometric"
    },
    "body_font": {
      "family": "Inter",
      "role": "Body copy, navigation, metadata, project descriptions, buttons, labels",
      "weights": ["400", "500", "600"],
      "character": "clean, modern, highly readable"
    },
    "optional_editorial_accent": {
      "family": "Instrument Serif",
      "role": "Use extremely selectively for one or two editorial phrases, image captions, or oversized accent words",
      "rule": "Never use the serif font for navigation, buttons, long paragraphs, or dense UI."
    },
    "typographic_rules": {
      "hero_title": "Use very large responsive typography between 96px and 180px on desktop depending on viewport width.",
      "section_titles": "56px–110px depending on section importance.",
      "project_titles": "48px–86px.",
      "body": "16px–20px with generous line-height.",
      "metadata": "11px–13px with increased letter-spacing.",
      "labels": "10px–12px uppercase with 0.08em–0.14em tracking.",
      "line_height": "Headlines should feel compact and intentional. Body copy should remain comfortable and highly readable.",
      "letter_spacing": "Use slightly negative tracking for giant display typography and slightly increased tracking for metadata."
    },
    "font_behavior": "Typography must be treated as part of the composition, not merely content placed inside boxes."
  },
  "global_visual_rules": {
    "composition": [
      "Prefer asymmetric layouts over centered template layouts.",
      "Allow typography and imagery to partially overlap.",
      "Use intentional empty space.",
      "Create visual tension with extreme size differences.",
      "Mix full-width elements with narrow editorial columns.",
      "Use thin black rules to establish rhythm.",
      "Use occasional oversized geometric color fields.",
      "Allow some elements to sit slightly outside conventional grid boundaries.",
      "Maintain strong alignment underneath the apparent visual chaos."
    ],
    "borders": "Use 1px or 2px black rules where structural separation is needed.",
    "corner_radius": "Mostly 0px–8px. Avoid excessive rounded cards.",
    "shadows": "Minimal. Prefer composition, borders, scale, overlap, and color blocks instead of generic drop shadows.",
    "gradients": "Avoid default gradients. Use flat color fields and carefully composed image treatments.",
    "icons": "Use minimal line icons or custom geometric symbols. Avoid generic icon libraries becoming visually dominant.",
    "visual_language": "A sophisticated design magazine mixed with an experimental digital gallery."
  },
  "header": {
    "position": "fixed",
    "height": "72px",
    "background": "transparent initially, subtly opaque warm-white after scrolling",
    "layout": {
      "left": {
        "content": "KAIEN.studio",
        "style": "small but confident wordmark, Syne 600, 18px–22px"
      },
      "center": {
        "content": "PRODUCT / UI / UX DESIGN",
        "style": "small uppercase metadata, Inter 500, 11px–12px, generous letter spacing"
      },
      "right": {
        "items": ["WORK", "ABOUT", "CONTACT"],
        "style": "uppercase editorial navigation, 11px–13px"
      }
    },
    "details": {
      "separator": "thin black line extending across the header",
      "active_state": "Chartreuse underline or tiny chartreuse square indicator",
      "hover": "Text shifts by 2px and underline grows horizontally"
    }
  },
  "hero": {
    "height": "100svh",
    "composition": "Full-screen editorial composition with oversized typography and layered graphic elements.",
    "background": "Lavender-dominant field with warm-white areas and small Chartreuse/Tomato Red interventions.",
    "top_metadata": {
      "left": "[PORTFOLIO / 2026]",
      "right": "BASED IN BERLIN & SAN FRANCISCO · AVAILABLE WORLDWIDE"
    },
    "main_text": {
      "eyebrow": "UI / UX / PRODUCT DESIGNER",
      "headline": ["I DESIGN", "DIGITAL", "EXPERIENCES"],
      "headline_style": {
        "font": "Syne 800",
        "desktop_size": "clamp(86px, 11vw, 170px)",
        "line_height": "0.82–0.92",
        "letter_spacing": "-0.055em",
        "color": "black"
      },
      "accent_treatment": "Place one oversized Chartreuse word fragment or underline crossing behind one line of the headline."
    },
    "supporting_copy": {
      "text": "Kaien Chen is a Principal Product & Systems Designer crafting deliberate digital interfaces, software OS architectures, and sculptural visual systems for world-class teams.",
      "width": "360px–460px"
    },
    "hero_cta": {
      "label": "EXPLORE SELECTED WORK",
      "style": "Chartreuse filled rectangular button with black border",
      "height": "52px"
    }
  },
  "section_01_selected_work": {
    "id": "work",
    "background": "#F7F5EF",
    "intro": {
      "index": "01",
      "eyebrow": "SELECTED WORK",
      "title": "A SMALL SELECTION OF THINGS I HAVE DESIGNED."
    },
    "projects": [
      {
        "number": "01",
        "name": "AURA OS · SYNTHETIC INTELLIGENCE",
        "category": "PRODUCT / UX",
        "year": "2026",
        "accent": "Lavender",
        "geometry": "Large black frame with Lavender offset layer."
      },
      {
        "number": "02",
        "name": "FLUENT · AURAL ARCHIVES",
        "category": "UI / VISUAL SYSTEM",
        "year": "2025",
        "accent": "Chartreuse",
        "geometry": "Chartreuse frame with black typography floating beside image."
      },
      {
        "number": "03",
        "name": "CHRONO · SPATIAL AUDIO CONSOLE",
        "category": "HARDWARE / INTERACTION",
        "year": "2025",
        "accent": "Tomato Red",
        "geometry": "Tomato Red editorial marker and black structural lines."
      }
    ]
  },
  "section_02_featured_case_study": {
    "index": "02",
    "eyebrow": "FEATURED CASE STUDY",
    "title": "AURA OS: THE ZERO-LATENCY SPATIAL WORKSPACE",
    "background": "Lavender",
    "accent": "Black + Chartreuse",
    "button": {
      "label": "VIEW CASE STUDY",
      "style": "black rectangular button with warm-white text"
    }
  },
  "section_03_design_philosophy": {
    "background": "Black",
    "text": "Warm White",
    "index": "03",
    "eyebrow": "HOW I THINK",
    "headline": "GOOD DESIGN SHOULD FEEL OBVIOUS — EVEN WHEN THE PROCESS IS NOT.",
    "visual_detail": {
      "accent_word": "DESIGN",
      "accent_color": "Chartreuse"
    }
  },
  "section_04_capabilities": {
    "index": "04",
    "eyebrow": "CAPABILITIES",
    "title": "WHAT I BRING TO THE TABLE",
    "background": "#F7F5EF"
  },
  "section_05_about": {
    "index": "05",
    "eyebrow": "A LITTLE ABOUT ME",
    "right": {
      "headline": "I LIKE MAKING DIGITAL THINGS FEEL HUMAN."
    }
  },
  "section_06_statement": {
    "background": "Chartreuse",
    "eyebrow": "ONE MORE THING",
    "headline": "LET'S MAKE SOMETHING PEOPLE REMEMBER.",
    "cta": {
      "label": "START A CONVERSATION"
    }
  },
  "footer": {
    "background": "Black",
    "text": "Warm White"
  }
}
```
