# Kai Rennard Portfolio Recreation — Exact Prompt Specification

Below is the complete prompt and specification schema used to generate the **Kai Rennard — Portfolio Experience** landing page.

```json
{
  "project": {
    "name": "Exact Portfolio Reference Recreation",
    "type": "pixel_accurate_website_recreation",
    "primary_source_of_truth": "attached_portfolio_reference_video",
    "objective": "Reproduce the same visual experience, composition, transitions, motion language, and interaction behavior shown in the reference video.",
    "important_instruction": "Do not reinterpret, redesign, modernize, simplify, or create a website merely inspired by the reference."
  },
  "recreation_rules": {
    "visual_fidelity": "maximum",
    "design_interpretation": "none",
    "reference_video_priority": "absolute",
    "content_substitution": "Allowed only when exact content is unavailable. Preserve the same dimensions, hierarchy, placement, and animation behavior.",
    "conflict_rule": "When standard web-design conventions conflict with the reference video, follow the reference video."
  },
  "overall_experience": {
    "style": [
      "cinematic",
      "editorial",
      "experimental",
      "premium",
      "minimal",
      "motorsport-inspired",
      "photographic",
      "highly_art-directed",
      "asymmetric",
      "immersive"
    ],
    "design_philosophy": "The website must feel like one continuous art-directed composition rather than a collection of conventional web components.",
    "avoid": [
      "generic portfolio layouts",
      "SaaS styling",
      "glassmorphism",
      "unnecessary gradients",
      "colorful cards",
      "excessive shadows",
      "generic component patterns"
    ]
  },
  "outer_environment": {
    "importance": "critical",
    "description": "The portfolio exists as a large floating rounded website surface inside an atmospheric full-screen environment.",
    "viewport": {
      "background": [
        "vivid turquoise/cyan atmospheric environment",
        "soft cloudy or photographic texture",
        "dark black-green diagonal racing/speed streaks",
        "subtle cinematic depth",
        "cinematic lighting"
      ]
    },
    "website_surface": {
      "position": "centered",
      "shape": "large rounded rectangle",
      "characteristics": [
        "rounded corners",
        "subtle depth",
        "dark outer edge",
        "clean editorial surface"
      ],
      "fullscreen": false,
      "desktop_behavior": "Maintain visible space around the website so the outer cyan/black environment remains visible."
    }
  },
  "header": {
    "structure": {
      "left": {
        "content": [
          "KAI",
          "RENNARD"
        ],
        "style": [
          "very small",
          "uppercase",
          "editorial labeling"
        ]
      },
      "center": {
        "content": "KR",
        "style": [
          "very small",
          "precisely centered"
        ]
      },
      "right": {
        "store_button": {
          "label": "STORE",
          "style": [
            "bright turquoise",
            "compact",
            "rounded",
            "minimal"
          ],
          "icon": "small shopping-bag/store icon"
        },
        "menu_button": {
          "style": [
            "small",
            "rounded-square",
            "light/white"
          ]
        }
      }
    },
    "behavior": {
      "minimal": true,
      "edge_spacing": "Match the reference video precisely."
    }
  },
  "hero": {
    "background": "warm off-white/cream",
    "visual_elements": [
      "subtle contour/topographic lines",
      "faint grey organic shapes",
      "large centered portrait",
      "editorial image treatment"
    ],
    "portrait": {
      "position": "centered",
      "crop": "similar to reference",
      "treatment": "photographic editorial cutout",
      "avoid": "generic card/container treatment"
    },
    "metadata": {
      "style": [
        "tiny",
        "uppercase",
        "editorial",
        "low visual emphasis"
      ],
      "example_content": [
        "NEXT RACE",
        "LISBOA GP"
      ]
    }
  },
  "hero_helmet_animation": {
    "importance": "critical",
    "description": "A turquoise/black racing helmet behaves as an independent foreground visual layer and moves across the subject's face.",
    "behavior": [
      "appears over the portrait",
      "moves horizontally across the face",
      "shifts between left, center, and right",
      "subtly rotates",
      "partially covers the face",
      "moves away",
      "disappears",
      "returns later"
    ],
    "motion_character": "physical, editorial, cinematic",
    "motion_properties": [
      "smooth interpolation",
      "subtle rotation",
      "slight scaling",
      "slight vertical movement",
      "natural easing",
      "layered depth"
    ],
    "depth_rule": "The helmet must visually sit in front of the portrait.",
    "timing": {
      "first_sequence": "early hero section",
      "second_sequence": "before hero transition",
      "motion_pattern": [
        "pause",
        "appearance",
        "movement",
        "pause",
        "disappearance",
        "reappearance"
      ],
      "do_not": [
        "make the movement continuously loop",
        "replace motion with simple fade"
      ]
    }
  },
  "hero_to_dark_transition": {
    "importance": "critical",
    "description": "The cream hero transforms into a dark editorial composition rather than simply scrolling into another section.",
    "target_state": [
      "near-black background",
      "oversized typography",
      "centered portrait"
    ],
    "transition_methods": [
      "clipping",
      "sliding panels",
      "scale changes",
      "layered movement",
      "opacity changes"
    ],
    "avoid": "simple fade"
  },
  "dark_editorial_portrait": {
    "background": "very dark blue/black",
    "visual_structure": [
      "oversized typography",
      "centered portrait",
      "muted grey image rectangle",
      "desaturated/monochrome photography"
    ],
    "style": "fashion/editorial magazine spread"
  },
  "signature": {
    "color": "bright turquoise",
    "position": "over the portrait and typography",
    "animation": {
      "type": "SVG stroke drawing",
      "behavior": "Progressively reveal the handwriting from beginning to end.",
      "initial_state": "hidden",
      "final_state": "fully visible and persistent"
    },
    "avoid": "instant appearance"
  },
  "large_editorial_typography": {
    "description": "Extremely large racing/editorial statements occupy a major portion of the viewport.",
    "example_content": [
      "CHASING THE APEX...",
      "FOR RESPECT...",
      "EVERYTHING IN EVERY LAP...",
      "BUILDING A STORY...",
      "TELLING ON MOTORSPORT..."
    ],
    "content_rule": "Actual copy may change to user content, but the visual typography treatment must remain equivalent.",
    "properties": [
      "large uppercase text",
      "tight line spacing",
      "strong horizontal scale",
      "editorial serif/sans combination where appropriate",
      "turquoise highlighted words",
      "viewport-dominant sizing"
    ],
    "overflow_behavior": "Some lines may approach or extend beyond visible boundaries.",
    "avoid": "normal paragraph styling"
  },
  "turquoise_bar_transition": {
    "importance": "high",
    "elements": [
      "horizontal turquoise bars",
      "stacked transition blocks"
    ],
    "animation": [
      "horizontal sliding",
      "expansion",
      "reveal",
      "stacking"
    ],
    "purpose": "Reveal or frame the oversized editorial typography.",
    "avoid": "generic fade-up animation"
  },
  "photography_collage": {
    "layout_type": "asymmetric editorial composition",
    "avoid": [
      "standard CSS grid",
      "equal cards",
      "uniform image sizing",
      "generic three-column layouts"
    ],
    "elements": [
      "large central photograph",
      "smaller supporting photographs",
      "portrait photography",
      "motorsport photography",
      "helmet photography",
      "lifestyle photography"
    ],
    "composition": [
      "different image sizes",
      "irregular spacing",
      "intentional alignment",
      "overlap where appropriate",
      "large areas of negative space"
    ],
    "visual_reference": "physical magazine/editorial spread"
  },
  "collage_animation": {
    "entrance": [
      "slight positional offset",
      "fade in",
      "subtle scale",
      "settling into final composition"
    ],
    "character": "restrained and premium",
    "goal": "Make the photographs feel like they are being assembled into the editorial composition."
  },
  "cream_photography_section": {
    "background": "warm off-white/cream",
    "layout": "asymmetric editorial composition",
    "elements": [
      "prominent portrait/photo near right-center",
      "smaller surrounding images",
      "generous negative space",
      "small labels",
      "thin editorial lines",
      "tiny turquoise details"
    ],
    "avoid": "standard image grid"
  },
  "photo_interaction": {
    "interaction_style": "subtle",
    "effects": [
      "slight cursor-based movement",
      "very subtle hover scale",
      "smooth depth/parallax",
      "small turquoise indicators"
    ],
    "avoid": [
      "large zoom effects",
      "flashy hover animations"
    ]
  },
  "on_off_track": {
    "importance": "critical",
    "background": "cream/off-white with subtle contour lines",
    "labels": [
      "ON TRACK",
      "OFF TRACK"
    ],
    "composition": "Large centered editorial labels with turquoise geometric markers.",
    "interaction_model": "Interactive destination rather than conventional tabs."
  },
  "on_off_track_interaction": {
    "on_hover_or_selection": [
      "typography responds subtly",
      "turquoise indicator responds",
      "associated visual content becomes active",
      "background/image composition transitions"
    ],
    "transition_character": "The entire composition appears to change category.",
    "on_track_content": [
      "racing",
      "helmets",
      "cars",
      "tracks",
      "paddock",
      "race photography"
    ],
    "off_track_content": [
      "portrait",
      "lifestyle",
      "photography",
      "behind-the-scenes",
      "personal content"
    ],
    "avoid": "conventional tab UI"
  },
  "large_feature_image": {
    "position": "after ON TRACK / OFF TRACK section",
    "composition": [
      "large motorsport-related photograph",
      "minimal surrounding UI",
      "dark/cream transition",
      "small editorial metadata"
    ],
    "reference_visual": "subject seated in a garage/workshop environment with a turquoise helmet nearby"
  },
  "helmet_gallery": {
    "section_style": "dark editorial archive",
    "background": "deep black/navy",
    "title": [
      "HELMETS",
      "HALL OF FAME"
    ],
    "layout": "asymmetric editorial archival composition",
    "avoid": [
      "ecommerce cards",
      "standard product grid"
    ],
    "helmet_elements": {
      "each_item": [
        "isolated photographic cutout",
        "dark environment",
        "tiny label",
        "subtle border/line details",
        "irregular sizing"
      ],
      "placement": [
        "large items",
        "small items",
        "centered items",
        "edge-positioned items"
      ]
    }
  },
  "helmet_gallery_animation": {
    "entrance_variation": [
      "different positional offsets",
      "fade-in",
      "slide-in",
      "scale-in"
    ],
    "rule": "Do not animate every helmet identically.",
    "character": "organic and editorial"
  },
  "global_animation_language": {
    "required": [
      "smooth cinematic easing",
      "slow/medium transitions",
      "subtle inertia",
      "layered movement",
      "image displacement",
      "clip-path reveals",
      "transform-based motion",
      "opacity reveals",
      "SVG line drawing",
      "horizontal text movement"
    ],
    "avoid": [
      "bounce",
      "cartoon easing",
      "aggressive spring effects",
      "excessive blur",
      "generic fade-up-on-scroll everywhere",
      "excessive parallax",
      "modern SaaS animation patterns"
    ],
    "overall_goal": "The animation system must feel like an art-directed motion-design piece."
  },
  "scroll_behavior": {
    "description": "The page should feel like one continuous cinematic journey.",
    "behavior": [
      "progressively transform the visual composition",
      "smooth section transitions",
      "scroll-linked movement"
    ],
    "scroll_linked_elements": [
      "typography",
      "photography",
      "helmet",
      "contour lines",
      "image positions",
      "section transitions",
      "editorial overlays"
    ],
    "depth": "Use subtle differences in movement speed to create layered depth.",
    "avoid": "abrupt section snapping"
  },
  "topographic_line_system": {
    "appearance": [
      "extremely thin",
      "low contrast",
      "organic",
      "irregular",
      "subtle"
    ],
    "behavior": "Some lines may move subtly with scroll/parallax.",
    "priority": "supporting visual detail, never dominant"
  },
  "typography": {
    "primary_sans": [
      "Helvetica Neue",
      "Inter",
      "Neue Haas Grotesk",
      "Geist"
    ],
    "editorial_serif": [
      "Canela",
      "Cormorant",
      "Playfair Display"
    ],
    "properties": [
      "uppercase where appropriate",
      "tight tracking",
      "oversized major statements",
      "tiny metadata"
    ],
    "avoid": "generic oversized website headings with excessive padding"
  },
  "color_system": {
    "cream": "#F1EFE9",
    "dark": "#071116",
    "near_black": "#04090C",
    "turquoise": "#19E5D0",
    "secondary_grey": "#858585",
    "rule": "Do not introduce additional accent colors unless required by photography."
  },
  "microinteractions": {
    "required": [
      "menu button state change",
      "subtle store button hover",
      "cursor influence on selected imagery",
      "subtle photography movement",
      "subtle typography response",
      "turquoise indicator animation",
      "image information reveal",
      "animated editorial menu overlay"
    ],
    "character": "precise, restrained, premium"
  },
  "menu": {
    "trigger": "top-right menu button",
    "presentation": "full-screen editorial navigation layer",
    "visual_language": [
      "cream/dark palette",
      "tiny labels",
      "giant editorial typography",
      "turquoise accents",
      "asymmetric composition"
    ],
    "animation": {
      "open": "animated",
      "close": "animated"
    },
    "avoid": "generic hamburger dropdown"
  },
  "store": {
    "label": "STORE",
    "style": [
      "compact",
      "bright turquoise",
      "rounded",
      "minimal",
      "highly visible"
    ],
    "icon": "small store/bag icon",
    "hover": "subtle"
  },
  "desktop": {
    "priority": "highest",
    "reference_target": "desktop composition shown in video",
    "requirements": [
      "preserve approximate proportions",
      "preserve outer cyan/black environment",
      "preserve floating website frame",
      "preserve margins and negative space"
    ],
    "avoid": "generic full-width webpage"
  },
  "responsive": {
    "mobile_strategy": "Recompose rather than simply scale down.",
    "preserve": [
      "cream/dark transitions",
      "typography hierarchy",
      "asymmetric image composition",
      "helmet animation",
      "turquoise accents",
      "ON/OFF TRACK concept",
      "editorial gallery behavior"
    ],
    "priority": "Desktop receives the highest visual-fidelity priority."
  },
  "critical_restrictions": {
    "do_not": [
      "redesign the website",
      "make it look like a normal portfolio",
      "use generic cards",
      "use generic three-column layouts",
      "turn the photo collage into a standard grid",
      "replace oversized typography with normal headings",
      "remove floating website frame",
      "remove cyan/black outer environment",
      "simplify helmet animation",
      "replace transitions with generic fades",
      "add unnecessary UI",
      "add gradients everywhere",
      "use glassmorphism",
      "use excessive shadows",
      "add random decorative elements",
      "invent a different color scheme",
      "create a completely different hero"
    ]
  },
  "reference_priority": {
    "primary_rule": "The reference video is the design specification.",
    "secondary_rule": "Do not normalize unusual layouts.",
    "secondary_rule_2": "Do not simplify asymmetric compositions.",
    "secondary_rule_3": "Do not simplify or replace the motion design.",
    "secondary_rule_4": "Do not convert editorial compositions into standard responsive cards.",
    "success_definition": "The resulting website should be recognizable as the same website shown in the reference video."
  },
  "content": {
    "initial_labels": [
      "KAI RENNARD",
      "KR",
      "STORE",
      "NEXT RACE",
      "LISBOA GP",
      "ON TRACK",
      "OFF TRACK",
      "HELMETS",
      "HALL OF FAME"
    ],
    "content_strategy": "Use the same visible content structure and equivalent placeholder imagery where necessary.",
    "replacement_rule": "User photographs/content may later replace placeholders without changing layout or animation architecture."
  },
  "quality_control": {
    "before_completion": "Visually compare the rendered website against the reference video.",
    "checklist": [
      "overall composition",
      "website frame size",
      "margins",
      "section proportions",
      "image positions",
      "typography scale",
      "turquoise placement",
      "helmet movement",
      "signature animation",
      "turquoise bar animations",
      "photography transitions",
      "ON/OFF TRACK section",
      "helmet gallery",
      "outer cyan/black environment",
      "section-to-section transitions"
    ],
    "final_priority": "Prioritize visual fidelity over conventional web-development simplicity."
  },
  "final_instruction": "Reproduce the same visual experience, composition, transitions, motion language, and interaction behavior as the attached reference video. Do not create a portfolio inspired by it. Recreate it."
}
```
