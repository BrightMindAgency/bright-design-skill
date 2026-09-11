# 💎 Bright Design Skill

> **The Unified Taste, UI/UX Engineering, and Anti-AI-Slop System for Autonomous AI Agents & Digital Products**

Created and maintained by **Stay Bright** & **Bright Mind Agency AB**.

---

## 🌟 Overview

**Bright Design Skill** (`bright-design`) is the official design engineering standard and aesthetic operating system used across all Stay Bright, Bright Mind Agency, and Oriiion applications, agents, kiosks, and customer interfaces.

It enforces uncompromising craftsmanship, human aesthetic taste, mathematical typography scales, luminous dark-glassmorphism, and anti-AI-slop heuristics across every digital deliverable.

---

## 🚫 The Anti-AI-Slop Directives

Every standard AI model produces bland "AI slop" by default unless bounded by strict architectural constraints. Bright Design enforces:

1. **Zero Generic 3D Blobs & Pastel Soup:** Prohibits uninspired floating gradient balls, flat corporate vectors, and washed-out pastel fills.
2. **Zero Unconstrained Typography Soups:** Never mix competing font families without deliberate hierarchy. Enforces Poppins 900 heavy uppercase headings (`-0.05em` tracking), Inter/Geist body, and JetBrains Mono system chips.
3. **Zero Arbitrary Spacing & Layout Drift:** Strictly requires structured CSS grids and flexbox systems aligned to standard 4px/8px rhythm units.
4. **Strict Contrast & Legibility:** Eliminates low-contrast grey-on-black text. Enforces APCA/WCAG AAA compliance with luminous accent highlights.
5. **Zero Fullscreen Scroll Wobble:** Presentation decks and kiosk interfaces are strictly constrained to `100vh` / `max-h-[calc(100vh-140px)]` with zero accidental scrollbars.

---

## 🎨 The Bright Visual Language

### 1. Typography & Hierarchy
* **Hero Titles & Primary Headers:** `Poppins 900 Black` or `Plus Jakarta Sans 800 ExtraBold`, uppercase, negative tracking (`-0.04em` to `-0.05em`), tight line-height (`0.95` to `1.05`).
* **Body & Editorial Copy:** `Inter` or `Geist Sans` (`400 Regular` / `500 Medium`), crisp line-height (`1.5` to `1.6`), max width 65 characters (`max-w-2xl`).
* **Tech Badges, Timestamps & Metrics:** `JetBrains Mono` or `Geist Mono` (`10px` to `12px`), uppercase with wide tracking (`0.1em` / `tracking-widest`), encased in subtle 1px translucent capsules.

### 2. Surface Elevation & Glassmorphism
* **Canvas Void:** Deep space dark background (`#030508` or `#05070A`).
* **Frosted Glass Panels:**
  ```css
  background: rgba(14, 18, 27, 0.72);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
  border: 1px solid rgba(255, 255, 255, 0.07);
  box-shadow: 0 20px 50px -10px rgba(0, 0, 0, 0.8);
  ```
* **Dividers:** Razor-sharp hairlines (`rgba(255, 255, 255, 0.06)`).

### 3. Cyber-Luminous CMY Accent Palette
* **Neon Cyan (`#00F0FF`):** Core interactive focus, validated traction badges, primary CTAs (`shadow: 0 0 30px rgba(0, 240, 255, 0.35)`).
* **Neon Magenta (`#FF007A`):** Critical callouts, market problems, secondary highlights (`shadow: 0 0 30px rgba(255, 0, 122, 0.35)`).
* **Neon Yellow (`#FFD700`):** Revenue metrics, cash flow, % rev-share highlights (`shadow: 0 0 30px rgba(255, 215, 0, 0.35)`).
* **Electric Blue (`#0066FF`):** Enterprise infrastructure nodes and secondary glow fields.

---

## 🛠️ The 7 Core Craft Disciplines

When building any interface, document, or visual artifact, execute these 7 quality disciplines:

1. **`typeset` (Typography Craft):** Optical kerning, viewport-scaled heading ratios, and strict micro-hierarchy (Eyebrow $\rightarrow$ Heavy Title $\rightarrow$ Summary $\rightarrow$ Data Chips).
2. **`colorize` (Chromatic Hierarchy):** 1 dominant neutral surface, 1 high-contrast readable text tier, and max 2 vibrant neon accents.
3. **`layout` (Spatial Geometry):** Asymmetric grid systems with strong alignment lines and generous negative breathing room (`p-8 md:p-14`).
4. **`animate` (Physics-based Motion):** Spring curves over linear transitions (`cubic-bezier(0.16, 1, 0.3, 1)`) for snappy, weightless UI responsiveness.
5. **`delight` (Sensory Polish):** Ambient radial backgrounds, subtle button hover glows, pulsing live status dots, and crisp FontAwesome / Lucide icon sets.
6. **`critique` (Truth & Quality Audit):** Pre-flight validation ensuring 100% real verified metrics, zero placeholder text, and high signal-to-noise ratio.
7. **`harden` (Cross-device Resilience):** Responsive viewport constraints, touch-friendly targets ($\ge 44\text{px}$), and keyboard presenter shortcuts.

---

## 🏢 50+ Curated Enterprise Design Blueprints

Included in `design-systems/`:
* **Linear Style:** Dark keyboard-first UI, subtle borders, high contrast, monochrome base with electric accent.
* **Stripe Style:** Fluid mesh gradients, micro-typography, robust multi-column data tables.
* **Vercel / Geist Style:** Geometric monochrome, razor-sharp grid lines, high-density developer consoles.
* **Apple Style:** Cinematic typography, large imagery, subtle frosted glass overlays.
* **Supabase / Raycast / Cursor Style:** High-velocity developer dashboards with command palettes and status indicators.

---

## 📦 Installation & Setup

### For Hermes Agent
Clone directly into your Hermes skills directory:
```bash
git clone https://github.com/BrightMindAgency/bright-design-skill.git ~/.hermes/skills/creative/bright-design
```

### For Claude Code, Cursor, Codex & OpenCode
Add to your project's `AGENTS.md` or `CLAUDE.md`:
```markdown
# Design System
Always load and adhere to the Bright Design Skill (`bright-design`).
- Ultra-heavy Poppins 900 headings with -0.05em tracking
- Inter body & JetBrains Mono badges
- Dark glassmorphism (#05070A canvas, backdrop blur 24px)
- Cyan (#00F0FF), Magenta (#FF007A), Yellow (#FFD700) glows
- Zero AI-slop: clean, rigid grids and validated real data
```

---

## 🛡️ License
MIT © 2026 Stay Bright & Bright Mind Agency AB.
