---

# Welcome 👋

In this ReadMe you’ll find **all the important colors, fonts, and design rules** that define the landing page / frontend style system.  
Everything from typography scales to spacing tokens and component guidelines is documented here for easy reference.

---

## How to Use

The entire design system is written in **HTML‑ready code snippets**.  
That means you can simply **copy any section and paste it into your `.html` file** to bring the styles directly into your project.  
No complex setup required — just plug and play.

---

IMPORTANT - If u are opening folder in VSC MAKE SURE TO Install Live Server 

---

# Project Brief & Product Requirements Document (PRD)

**Project Name:** FURY — CRT Terminal Developer Portfolio  
**Status:** In Development / Baseline Delivered (`{{DATA:SCREEN:SCREEN_1}}`)  
**Target Viewport:** Desktop (1440px wide canvas, max-w-1120px terminal window)   

---

## 1. Executive Summary & Product Vision

### 1.1 Objective
Design and implement an immersive, retro-futuristic CRT phosphor-green terminal developer portfolio website for "FURY". The portfolio moves away from standard marketing-page conventions and generic SaaS layouts, presenting the developer's experience, selected open-source/systems projects, proficiencies, and contact channels through the metaphor of an active UNIX command-line session and VT100/CRT monitor display.

### 1.2 Target Audience
- **Founding Teams & Tech Leads:** Seeking high-caliber systems, DevTools, or full-stack engineers with deep autonomy.
- **Open-Source Collaborators & Engineering Peers:** Exploring repositories, architecture choices, and terminal UI design.
- **Contract & Advisory Clients:** Looking for specialized CLI/TUI design and high-throughput systems consulting.

### 1.3 Core Metaphor & Theme
- **Theme:** Monochromatic phosphor green (`#39ff7a`) CRT monitor on a deep void-black (`#000000`) canvas.
- **Interaction Style:** Command prompts (`$`, `>`), UNIX command invocations (`whoami`, `neofetch`, `ls -la`, `cat`, `./contact`), file permission annotations, ASCII metadata tags, and blinking block carets.
- **Discipline:** No stock photography, zero purple/indigo generic gradients, strictly monospace typefaces, with disciplined amber (`#ffd24a`) accents reserved for live statuses and notable repository badges.

---

## 2. Design System & Visual Specification

### 2.1 Color Architecture
| Token | Hex / Value | Semantic Role |
| :--- | :--- | :--- |
| **Canvas Background** | `#000000` | Viewport outer background |
| **Window Background** | `#050805` / `#070b07` | Terminal console pane fill |
| **Border / Hairlines** | `#143614` / `#1f4d1f` | Inset borders, grid lines, separators |
| **Primary Phosphor Accent**| `#39ff7a` | Active glow headers, active links, primary CTA, carets |
| **Dim Phosphor Green** | `#2bbf5c` / `#1c7a3c` | Skill meter gradients, secondary links, subtle commands |
| **Muted Sage** | `#5f8d68` | Body copy, descriptions, terminal comments (`//`) |
| **High-Contrast Text** | `#eafff1` | Hero name banner, primary headings, prompt text |
| **Warning / Status Amber** | `#ffd24a` | Availability indicators, featured tags, GitHub stars |
| **Prompt Cyan** | `#5cf6ff` | Specific directory / hostname path markers |

### 2.2 Typography
- **Primary Typeface:** `JetBrains Mono`, monospace (weights: 400, 500, 700, 800)
- **Secondary Typeface:** `IBM Plex Mono`, monospace (used for data tables and system specs)
- **Scale:**
  - Hero Name: `~60px - 64px` font-weight 800 with multi-layer text-shadow glow (`0 0 8px rgba(57,255,122,0.45)`, `0 0 24px rgba(57,255,122,0.18)`)
  - Section Headings: `~18px - 20px` bold monospace with command comments
  - Body & Descriptions: `13px - 14.5px` monospace, line-height 1.6
  - Captions, Meta, & Permissions: `11px - 12px` monospace

### 2.3 Environmental FX & Texture
1. **CRT Scanlines:** Fixed pointer-events-none viewport overlay using a repeating linear gradient at 3–4px pitch with faint dark lines, `mix-blend-mode: multiply`, `opacity: ~0.45-0.5`.
2. **Radial Ambient Glow:** Two subtle radial gradients positioned at top-right (`rgba(57,255,122,0.08)`) and mid-left (`rgba(57,255,122,0.05)`).
3. **Phosphor Glow:** Text-shadow utilities (`.glow`, `.glow-soft`) applied to primary headings, buttons, and status blips.
4. **Blinking Carets:** Keyframe-animated green block cursor (`1.1s steps(2, start) infinite`).

---

## 3. Information Architecture & Key Modules

### Module 1: Window Chrome & Global Navigation
- **Chrome Header:**
  - Traffic light controls: Red (`#ff5f56`), Amber (`#ffbd2e`), Green (`#27c93f`).
  - Terminal session path label: `fury@portfolio: ~/dev zsh (tty1)`.
  - Right-hand navigation anchors: `~/work`, `~/stack`, `~/contact`.
  - Real-time status blip: Pulsing amber dot + `available for work`.

### Module 2: `whoami --full` (Hero Section)
- **Command:** `fury~/dev $ whoami --full // exec timestamp: 2026.04.17`
- **Elements:**
  - Oversized glowing title: `FURY` + animated cursor.
  - Role definition: `> Full-stack engineer & indie hacker, building developer tools`.
  - Bio statement: Focus on high-performance runtime architectures, local-first apps, and terminal interfaces.
  - ASCII metadata pills: `[x] location: Lisbon, PT`, `[x] experience: 9+ yrs`, `[x] status: freelance / contract Q2-Q3`.
  - Dual CTAs: Primary solid green `$ ls ~/projects →` and ghost console button `./contact --hire`.

### Module 3: `neofetch --stdout` (Identity Card)
- **Command:** `fury~/dev $ neofetch --stdout`
- **Layout:** Two-column split panel:
  - Left: Green glowing ASCII pixel avatar mascot with `fury@dev` tag and UID details.
  - Right: System specification list:
    - OS: `Human v10.4 (engineer build, x86_64)`
    - Host: `Remote, Lisbon PT (38.7223° N, 9.1393° W)`
    - Role: `Full-stack + DevTools Specialist`
    - Uptime: `9 yrs, 4 startups, 182k lines committed`
    - Shell: `zsh 5.9, neovim (custom lua), tmux 3.4`
    - Stack: `TypeScript, Rust, Go, Node.js, Postgres`
    - Focus: `Agent tooling, local-first data, reactive TUI`
    - Status: `● available for contract / tech lead advisory`
  - Inline 8-swatch terminal palette strip.

### Module 4: `ls -la ~/projects` (Work Grid)
- **Command:** `fury~/dev $ ls -la ~/projects # 4 selected targets`
- **Structure:** 2x2 grid of bordered directory cards with hover lift and green glow.
- **Projects Highlighted:**
  1. `portmux/` (★ 4.2k, `-rwxr-xr-x`): Distributed terminal workspace multiplexer (`open source`, `Rust`, `Tokio`, `eBPF`).
  2. `agentd/` (★ 2.8k, `-rwxr-xr-x`): Headless daemon orchestrator for autonomous coding agents (`SaaS engine`, `Go`, `gRPC`, `Docker`).
  3. `glow-notes/` (★ 1.9k, `-rwxr-xr-x`): Local-first CRDT personal knowledge base (`open source`, `TypeScript`, `WASM`, `Yjs`).
  4. `phosphor-ui/` (★ 3.4k, `-rwxr-xr-x`): Headless component library for browser-based terminals (`open source`, `React`, `Tailwind`, `WebGL`).
- **Actions:** Individual `→ live demo` and `→ source` links per card.

### Module 5: `cat stack.txt | sort -r` (Proficiency Meters)
- **Command:** `fury~/dev $ cat stack.txt | sort -r`
- **Structure:** Dual columns with 8 assessed engineering proficiencies:
  - TypeScript (95%), React / Next.js (92%), Postgres / SQL (90%), Go (88%), System Design (86%), Rust (82%), Docker / K8s (78%), Design / UI / TUI (74%).
  - Visual: Track background (`#070b07`), green gradient meter fill with phosphor glow, and right-aligned percentages.

### Module 6: `./contact --hire` & Session Footer
- **Command:** `fury~/dev $ ./contact --hire`
- **Elements:**
  - Heading: `Let's build something resilient together.`
  - Copyable terminal input box: `$ mail fury@reyes.dev` with interactive copy-to-clipboard action and feedback indicator.
  - External links: `→ github`, `→ x.com`, `→ blog.txt`, `→ CV.pdf`.
  - Shell footer echo line: `$ echo "(c) 2026 Fury, built in the terminal, shipped fast" █`.
  - Fake Git metadata status: `last commit: 2h ago • main@a1f9e2c • uptime 99.98%`.

---

## 4. Technical Non-Functional Requirements

1. **Performance & Lightweight Footprint:**
   - Pure CSS/SVG raster overlays without heavy 3D WebGL runtimes unless explicitly toggled.
   - Fast first contentful paint (FCP < 800ms) with zero image asset blocking.
2. **Accessibility (a11y):**
   - High contrast green-on-black text matching WCAG AAA ratio (>7:1) for primary text.
   - Screen-reader accessible landmark roles (`main`, `nav`, `section`, `footer`) despite terminal appearance.
   - Reduced-motion support (`prefers-reduced-motion: reduce`) disabling continuous cursor blinking and scanline animation.
3. **Responsive Adaptation:**
   - Single-column fallback on mobile/tablet viewports (< 768px): neofetch card stacks vertically, work grid collapses to 1x4, skill meters display as single column.

---

## 5. Potential Roadmap & Future Iterations
- [ ] **Interactive Command Input (CLI Shell Mode):** Allow typing arbitrary commands (`help`, `clear`, `cat resume.txt`, `theme amber`) into the terminal.
- [ ] **Mobile Companion Screen:** Dedicated mobile layout (~390px viewport) optimized for touch-based terminal navigation.
- [ ] **Project Case Study Drilldowns:** Inner screens or modals for `portmux/` and `agentd/` featuring architecture diagrams and benchmarks.
