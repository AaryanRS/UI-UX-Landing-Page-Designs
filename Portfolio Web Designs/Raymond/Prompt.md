{
  "project": {
    "name": "RAYMOND — Abstract Artist Editorial Portfolio",
    "version": "1.0.0",
    "target_archetype": "digital_newspaper_editorial_broadsheet",
    "device_type": "desktop",
    "design_system_ref": "{{DATA:DESIGN_SYSTEM:DESIGN_SYSTEM_1}}",
    "shell_ref": "{{DATA:SHELL:SHELL_3}}"
  },
  "prompt_configuration": {
    "subject": {
      "name": "RAYMOND",
      "profession": "ABSTRACT ARTIST / PAINTER",
      "personality_attributes": [
        "artistic",
        "expressive",
        "contemporary",
        "intelligent",
        "experimental",
        "refined",
        "visually obsessive",
        "slightly mysterious"
      ],
      "studio_locations": [
        "Paris Atelier — Rue de Turenne, Marais",
        "New York Archive — Chelsea Annex"
      ]
    },
    "art_direction": {
      "concept": "Physical digital newspaper / archival art editorial publication. Single continuous editorial broadsheet being explored across the viewport.",
      "forbidden_elements": [
        "generic SaaS cards",
        "rounded pill containers",
        "floating box shadows",
        "glassmorphism",
        "neon gradients",
        "modern crowded navbars",
        "excessive icons",
        "lengthy biography paragraphs"
      ],
      "mandatory_elements": [
        "desk perspective mode / physical paper broadsheet opening",
        "monumental Didot/Bodoni masthead (8vw–14vw)",
        "warm paper parchment background palette (#FFF8F0 / #E7DFD0 / #EFE8DC)",
        "crisp 1px ink rule boundaries (#26221F)",
        "high-density technical micro-metadata",
        "asymmetrical multi-column newspaper grid",
        "archival awards and institutional provenance table",
        "monograph feature article with drop cap",
        "large contact headline ('LET\\'S TALK ABOUT ART.')"
      ]
    },
    "color_palette": {
      "surface_base": "#FFF8F0",
      "surface_secondary": "#EFE8DC",
      "ink_primary": "#111111",
      "ink_secondary": "#35312D",
      "ink_muted": "#746E66",
      "accent_terracotta": "#A55F49",
      "divider_ink": "rgba(38, 34, 31, 0.25)",
      "poster_charcoal": "#1A1817"
    },
    "typography": {
      "display_headline_font": "Bodoni Moda, Didot, serif",
      "editorial_body_font": "Newsreader, Cormorant Garamond, serif",
      "ui_metadata_font": "Inter, Helvetica Neue, sans-serif",
      "contrast_ratio": "extreme contrast between massive headlines (8vw-14vw) and micro-metadata (9px-11px uppercase)"
    },
    "artwork_assets": [
      {
        "placeholder": "{{DATA:IMAGE:IMAGE_7}}",
        "title": "UNTITLED I (TECTONIC HORIZON)",
        "medium": "Raw Terracotta, Carbon Ink, and Cold Wax on Belgian Linen",
        "dimensions": "310 × 220 CM",
        "year": "2026",
        "provenance": "Permanent Repository, Foundation Monograph"
      },
      {
        "placeholder": "{{DATA:IMAGE:IMAGE_5}}",
        "title": "UNTITLED II (CROSS FORMATION)",
        "medium": "Oil, Soot & Raw Ash on Raw French Linen",
        "dimensions": "280 × 190 CM",
        "year": "2026",
        "provenance": "Fondation Louis Vuitton Special Loan"
      },
      {
        "placeholder": "{{DATA:IMAGE:IMAGE_6}}",
        "title": "UNTITLED III (CHARCOAL WASH & RUST)",
        "medium": "Oxidized Copper Grounds, Bone Glue & Charcoal Wash",
        "dimensions": "195 × 145 CM",
        "year": "2025",
        "provenance": "Atelier Registration #902"
      },
      {
        "placeholder": "{{DATA:IMAGE:IMAGE_4}}",
        "title": "UNTITLED IV (MONOCHROME TECTONICS)",
        "medium": "Powdered Graphite, Unground Chalk & Singular Rust Accent",
        "dimensions": "210 × 160 CM",
        "year": "2026",
        "provenance": "Studio Dossier, Paris"
      }
    ],
    "sections_sequence": [
      "folio_meta_header_and_view_mode_toggle",
      "monumental_masthead_with_front_page_dispatch",
      "abstract_artist_statement_and_gallery_hero_plate",
      "form_color_emotion_full_bleed_poster_break",
      "catalogue_raisonne_all_paintings_asymmetric_grid",
      "latest_paintings_bulletin_three_panel_study",
      "perfect_artisan_monograph_critique_with_drop_cap",
      "archival_metrics_and_institutional_exhibition_records",
      "curatorial_testimonials_dual_column",
      "monumental_closing_contact_and_newspaper_colophon"
    ]
  }
}