{
  "project": "Architectural Type System",
  "version": "1.0.0",
  "design_language": "Swiss-Brutalist Architectural Grid",
  "palette": {
    "background": "#000000",
    "foreground": "#FFFFFF",
    "accent": "#6366f1",
    "borders": "rgba(255, 255, 255, 0.15)",
    "hairline_width": "0.5px",
    "surface_hover": "rgba(255, 255, 255, 0.03)"
  },
  "typography": {
    "headlines": {
      "family": "Inter Tight",
      "weight": 900,
      "tracking": "-0.06em",
      "transform": "uppercase",
      "leading": "none"
    },
    "technical_metadata": {
      "family": "JetBrains Mono",
      "weight": 500,
      "tracking": "0.2em - 0.4em",
      "transform": "uppercase",
      "formatting": "underscores_instead_of_spaces"
    },
    "body": {
      "family": "Inter",
      "weight": "300 - 400",
      "opacity": "0.4"
    }
  },
  "visual_effects": {
    "noise_grain": {
      "type": "svg_fractal_noise",
      "opacity": 0.05,
      "pointer_events": "none"
    },
    "radii": "0px_strict_except_pill_buttons",
    "shadows": "none",
    "gradients": "none",
    "transitions": "300ms ease, 700ms cubic-bezier(0.4, 0, 0.2, 1) for rotational geometry"
  },
  "layout_sections": [
    {
      "name": "Navigation Chrome",
      "height": "72px",
      "border_bottom": "0.5px hairline",
      "elements": [
        "Brand mark with 6px white dot and BETA_V.01 versioning tag",
        "Circular 40px hairline social icons",
        "Pill-shaped GET ACCESS CTA with 10px bold mono font"
      ]
    },
    {
      "name": "Hero Section (2x2 Grid Matrix)",
      "height": "100vh_fold",
      "quadrants": [
        {"position": "top-left", "word_segment": "SU", "tag": "[01/04] // LAT_52.5200°_N"},
        {"position": "top-right", "word_segment": "PER", "tag": "[02/04] // GRID_AXIS_01"},
        {"position": "bottom-left", "word_segment": "DE", "tag": "[03/04] // KERNING_TIGHT"},
        {"position": "bottom-right", "word_segment": "SIGN", "tag": "[04/04] // TYPE_SYSTEM_BRUTAL"}
      ]
    },
    {
      "name": "Command Bar",
      "columns": 4,
      "cells": [
        {"type": "input", "label": "email", "placeholder": "ENTER_WORK_EMAIL..."},
        {"type": "button", "label": "JOIN", "tracking": "0.3em"},
        {"type": "status_timer", "format": "HH : MM : SS", "font": "JetBrains Mono 24px"},
        {"type": "system_stack", "tags": ["FREE_ACCESS_PASS", "NO_CREDIT_CARD", "DEPLOY_IMMEDIATE"]}
      ]
    },
    {
      "name": "Bento Feature Grid",
      "columns": 3,
      "card_height": "420px",
      "cards": [
        {
          "tag": "SYSTEM_01 // VECTOR_TOPOLOGY",
          "interactive_element": "45_deg_square_rotating_to_90_deg_on_hover",
          "title": "MONOLITHIC MATRIX"
        },
        {
          "tag": "SYSTEM_02 // GLYPH_ENGINE",
          "interactive_element": "wireframe_crosshair_glyph_opacity_shift",
          "title": "SUB-PIXEL HAILINE"
        },
        {
          "tag": "SYSTEM_03 // KINETIC_DISPATCH",
          "interactive_element": "concentric_radar_rings_pulse",
          "title": "IDE PRECISION"
        }
      ]
    }
  ]
}