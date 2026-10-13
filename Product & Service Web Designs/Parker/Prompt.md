{
  "project": "Parker — Precision Drafting Instrument Landing Page",
  "client": "Parker Drafting Instruments",
  "archetype": "Maker Landing Page",
  "design_direction": {
    "aesthetic": "Artisan Stationery & Drafting Instruments",
    "background_palette": {
      "ground": "#EFE9DD",
      "secondary_ground": "#E5DED0",
      "surface_container": "#FFFFFF"
    },
    "ink_palette": {
      "primary_ink": "#141C2B",
      "secondary_ink": "#4A5364",
      "muted_ink": "#767E8C",
      "accent_blue": "#2C4A8F",
      "hairline_border": "rgba(20, 28, 43, 0.16)"
    },
    "typography": {
      "display_and_headings": {
        "family": "Newsreader",
        "weights": [400, 500, 600],
        "letter_spacing": "-0.02em",
        "emphasis_rule": "Newsreader Italic in Accent Ink Blue (#2C4A8F)"
      },
      "technical_labels_and_body": {
        "family": "Courier Prime",
        "weights": [400, 700],
        "font_size": "11px - 12px",
        "letter_spacing": "0.07em - 0.10em",
        "line_height": 1.9,
        "text_transform": "uppercase"
      }
    },
    "constraints": {
      "border_radius": "0px everywhere including buttons and panels",
      "accent_usage": "Accent blue strictly applied to type emphasis, rules, or drawn line; never as a solid background fill",
      "forbidden_elements": ["gradients", "glows", "bento_grids", "rounded_cards", "drop_shadows_on_ui"]
    }
  },
  "sections": [
    {
      "id": "nav",
      "name": "Fixed Technical Header",
      "height": "58px",
      "backdrop_blur": "12px",
      "elements": ["Serif wordmark with blue trailing period", "Monospaced navigation links with accent hover", "Square button"]
    },
    {
      "id": "hero",
      "name": "Opening Lede & Full-Width Wordmark",
      "copy_max_width": "46vw",
      "headline_size": "clamp(32px, 4.6vw, 68px)",
      "elements": [
        "Monospaced kicker",
        "Newsreader headline with italic accent phrase",
        "Technical lede and twin action buttons",
        "Hairline specification footer strip",
        "Spread wordmark (P A R K E R) cropped at baseline"
      ]
    },
    {
      "id": "mechanics",
      "name": "01 / The Mechanics of Capillary Balance",
      "layout": "Two-column grid",
      "elements": ["Heading & monospaced copy", "Hairline-ruled table with tabular figures"]
    },
    {
      "id": "demonstration",
      "name": "02 / Autonomous Line Demonstration",
      "elements": [
        "Heading & nib variant buttons (EF / 0.32, F / 0.50, M / 0.75, 1.1 Stub) with aria-pressed",
        "Calibrated plotting panel with self-drawing SVG sine path",
        "Synchronized live measurement metrics"
      ]
    },
    {
      "id": "metallurgy",
      "name": "03 / Metallurgy & Substrates",
      "layout": "Two-column material breakdown",
      "elements": ["Grade 5 Titanium, C36000 Brass, Nikko Grade A Ebonite, Ruthenium-Tipped Nib"]
    },
    {
      "id": "tolerances",
      "name": "04 / Physical Caliber & Benchmarks",
      "layout": "Tabular measurement matrix",
      "elements": ["Capped/uncapped lengths, mass tolerances, bore capacity"]
    },
    {
      "id": "commissioning",
      "name": "05 / Commissioning & Close",
      "elements": ["Headline with accent italic phrase", "Order CTA", "Full-width baseline-cropped wordmark"]
    }
  ],
  "motion_specifications": {
    "travelling_product": {
      "element_id": "#travelling-product",
      "position": "fixed",
      "asset": "Titanium and blackened brass drafting fountain pen cutout with multiply blend",
      "interpolation": "Proportional scroll coordinates (vw, vh), rotation easing, scale adjustment",
      "dismissal": "Fade out to opacity 0 and visibility: hidden past section 03",
      "accessibility": "display: none under @media (prefers-reduced-motion: reduce)"
    },
    "self_drawing_demonstration": {
      "technique": "SVG getTotalLength() strokeDasharray / strokeDashoffset transition",
      "trigger": "IntersectionObserver or scroll reveal",
      "interactive": "Morph stroke-width and amplitude upon nib button click"
    },
    "spread_wordmark": {
      "container": "display: flex; justify-content: space-between;",
      "behavior": "Letters spread laterally and descend on scroll departure from hero"
    }
  }
}
