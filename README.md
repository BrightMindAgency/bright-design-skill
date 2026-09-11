# 💎 Bright Design Skill

> **The Unified Taste, UI/UX Engineering, and Anti-AI-Slop System for Autonomous AI Agents & Digital Products**

Created and maintained by **Stay Bright** & **Bright Mind Agency AB**.

---

## 🌟 Overview

**Bright Design Skill** (`bright-design`) is the official design engineering standard and aesthetic operating system used across all Stay Bright, Bright Mind Agency, and Oriiion applications, agents, kiosks, and customer interfaces.

It enforces uncompromising craftsmanship, human aesthetic taste, mathematical typography scales, solid dark surfaces, expansive breathing room, and anti-AI-slop heuristics across every digital deliverable.

---

## 🚫 The Anti-AI-Slop Directives

Every standard AI model produces bland "AI slop" by default unless bounded by strict architectural constraints. Bright Design enforces:

1. **Zero Eyebrow Pills or Micro-Notes Above Headlines:** Never place floating pill chips with pulsing dots (`● CATEGORY · STATUS`) hovering right above main titles. A strong headline commands the space on its own.
2. **Zero Colored Left-Border Accent Cards:** Never use `border-l-2` or `border-l-4` colored indicator lines on cards (the classic Jira / Bootstrap / AI-generated alert card tell). Use uniform hairline borders (`1px solid #1E222D`) or pure typographic hierarchy.
3. **Zero Cramped or Low Spacing:** AI models constantly cram elements together with tight margins. Enforce generous, deliberate padding and whitespace (`py-12`, `gap-8 md:gap-12`, `space-y-8`). Let elements breathe.
4. **Zero Glassmorphism & Frosted Blur:** No milky translucent cards with `backdrop-filter: blur()`. Enforces solid, opaque dark surfaces (`#050608`, `#0D0E12`, `#13151B`) with razor-sharp 1px hairlines.
5. **Zero Generic 3D Blobs & Pastel Soup:** Prohibits uninspired floating gradient balls, flat corporate vectors, and washed-out pastel fills.
6. **Zero Unconstrained Typography Soups:** Never mix competing font families without deliberate hierarchy. Enforces Poppins 900 heavy uppercase headings (`-0.05em` tracking), Inter body, and JetBrains Mono system chips.
7. **Zero Fullscreen Scroll Wobble:** Presentation decks and kiosk interfaces are strictly constrained to `100vh` with zero accidental scrollbars.

---

## 🎨 The Bright Visual Language

### 1. Typography & Hierarchy
* **Hero Titles & Primary Headers:** `Poppins 900 Black`, uppercase, negative tracking (`-0.04em` to `-0.05em`), tight line-height (`0.95` to `1.02`). Generous breathing room above and below.
* **Body Copy:** `Inter` (`400 Regular` / `500 Medium`), crisp line-height (`1.6`), max width 65 characters (`max-w-2xl`).
* **System Metrics:** `JetBrains Mono` (`10px` to `12px`), uppercase with wide tracking (`0.1em`).

### 2. Solid Surface Elevation (Zero Glassmorphism)
* **Canvas:** Deep solid black canvas (`#050608` or `#08090C`).
* **Solid Surfaces:** Opaque, high-density cards (`#0D0E12`, `#13151B`, `#1A1D26`) with razor-sharp 1px border strokes (`#1E222D` / `#282D3B`).
* **Dividers:** Razor-sharp hairlines (`rgba(255, 255, 255, 0.06)`).

### 3. Cyber-Luminous & Brand Accent Palette
* **Neon Teal (`#3BD194`):** Primary action, verified metrics, live indicators.
* **Berry Magenta (`#9B3793`):** Critical callouts, secondary highlights.
* **Royal Purple (`#783797`) & Slate Blue (`#556D97`):** Structural gradient and infrastructure nodes.
* **Luminous Cyan (`#00F0FF`) & Yellow (`#FFD700`):** Revenue highlights and transactional badges.

---

## 📦 Installation & Setup

### For Hermes Agent
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
- Solid opaque dark surfaces (#050608 canvas, #0D0E12 cards, razor-sharp hairlines)
- Zero eyebrow pills/notes above titles
- Zero colored left-border cards
- Generous, deliberate whitespace (no cramped/low spacing)
- Zero glassmorphism / zero frosted blur
```

---

## 🛡️ License
MIT © 2026 Stay Bright & Bright Mind Agency AB.
