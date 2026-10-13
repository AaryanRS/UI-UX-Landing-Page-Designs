# Prompt.md

```json
{
  "project": {
    "name": "Flora",
    "trading_name": "Fallow Row Seed House",
    "type": "e-commerce landing page",
    "theme": "Warm print editorial heirloom seed house"
  },
  "aesthetic": {
    "register": "Warm print editorial",
    "inspiration": [
      "Vintage horticultural ledgers",
      "Swiss modernist typesetting",
      "Agrarian taxonomy records"
    ],
    "principles": {
      "border_radius": "0px everywhere (zero radii)",
      "borders": "1.5px solid ink on paper substrates, 1px hairlines elsewhere",
      "shadows": "none",
      "gradients": "none",
      "imagery": "Programmatic HTML5 Canvas graphics only (no external photos, no icon fonts)"
    }
  },
  "design_system": {
    "colors": {
      "cream_ground": "#E7E2D8",
      "dark_loam": "#241A12",
      "deep_ink": "#171717",
      "hot_red": "#EF493C",
      "deep_red": "#B92725",
      "paper_stock": "#FFFDF8",
      "hairline_primary": "rgba(23, 23, 23, 0.16)",
      "hairline_subtle": "rgba(23, 23, 23, 0.08)",
      "muted_ink_56": "rgba(23, 23, 23, 0.56)",
      "muted_ink_34": "rgba(23, 23, 23, 0.34)"
    },
    "typography": {
      "display": {
        "family": "Anton, sans-serif",
        "case": "uppercase",
        "letter_spacing": "-0.02em to -0.045em",
        "line_height": "0.86",
        "usage": "Poster hero headlines, section headers, specimen titles"
      },
      "body": {
        "family": "Inter, sans-serif",
        "weights": [400, 500, 700],
        "line_height": "1.5",
        "usage": "Editorial prose, manifesto statement ledes, FAQ answers"
      },
      "monospace": {
        "family": "Martian Mono, monospace",
        "size": "10.5px",
        "letter_spacing": "+0.18em",
        "case": "uppercase",
        "usage": "Metadata, tags, prices, assay percentages, lot identifiers, table rows"
      }
    }
  },
  "scroll_architecture": {
    "controller": "Single window scroll listener driving CSS custom properties on :root",
    "pinned_stages": [
      {
        "id": "stage_1_hero_poster",
        "height": "280svh",
        "background": "#241A12",
        "canvas": "Tilled-soil grid strokes drifting on sine harmonics (5%-19% alpha)",
        "lockup": "Two-line Anton title scaled dynamically via min(vw, calc(92vw / (chars * 0.44)))",
        "css_variables": {
          "--hero-type-y": "0px to -90px",
          "--hero-type-scale": "1.0 to 0.74",
          "--hero-type-alpha": "1.0 to 0.0"
        }
      },
      {
        "id": "stage_2_manifesto_clip_wipe",
        "height": "260svh",
        "background": "#E7E2D8",
        "technique": "Two identical layered sentences: bottom in 34% muted ink, top in 100% ink wiped from bottom to top via clip-path: inset(calc(100% - var(--manifesto-wipe)) 0 0)",
        "css_variables": {
          "--manifesto-wipe": "0% to 100%",
          "--manifesto-scale": "1.0 to 1.05"
        }
      },
      {
        "id": "stage_3_horizontal_specimen_rail",
        "height": "340svh",
        "background": "#E7E2D8",
        "components": "6 non-wrapping botanical variety cards (clamp(230px, 26vw, 330px)) with generative canvas seed illustrations",
        "motion": "Translates horizontally by exact track overflow (calc(-1 * progress * overflowWidth)) with active progress indicator",
        "accessibility": "Wraps and centers gracefully under prefers-reduced-motion"
      },
      {
        "id": "stage_4_physical_artifact",
        "height": "420svh",
        "background": "#241A12",
        "layout": "Two-column: sliding narrative notes on left, 3/4 aspect paper packet on right",
        "css_variables": {
          "--packet-alpha": "0.0 to 1.0",
          "--packet-enter": "38px to 0px",
          "--packet-scale": "0.78 to 1.0",
          "--packet-cut": "0.0 to 1.0",
          "--packet-meter": "0% to 100%",
          "--packet-copy-x": "0px to -30px"
        },
        "behavior": "Phase index updates status line, cumulative cue lights, and fills printed lot number, ISTA germination assay, and opens dashed perforation strip"
      },
      {
        "id": "stage_5_parallax_season_band",
        "height": "300svh",
        "background": "#E7E2D8",
        "canvas": "22 stacked contour curves drifting on sine harmonics, every 5th curve in #EF493C",
        "css_variables": {
          "--season-y": "-4% to +4%",
          "--season-scale": "1.10 to 1.055"
        },
        "behavior": "Three propagation chapters sequentially swap opacity based on floor(progress * 3)"
      }
    ]
  },
  "static_sections": [
    {
      "name": "Ruled Commercial Price Sheet",
      "style": "Tabular monospace layout with 1.5px ink hairlines, pack formats, gram weights, and unit pricing"
    },
    {
      "name": "Native FAQ Accordion",
      "style": "Semantic <details> and <summary> items with mono index counters and animated carets"
    },
    {
      "name": "Archival Footer",
      "style": "Dark loam ground (#241A12), newsletter dispatch subscription, certifications, and dual legal columns"
    }
  ],
  "micro_interactions": {
    "word_split_animation": "Every headline and statement split into inline-block spans rising 0.42em with 38ms stagger",
    "atom_motion_budget": "Approximately 200 elements with data-rev attributes staggered 40ms to 100ms via IntersectionObserver"
  }
}
```
