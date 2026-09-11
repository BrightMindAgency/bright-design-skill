---
name: bright-design
description: "Global design, aesthetic taste, and UI/UX engineering system for Stay Bright & BMA agents. Eliminates AI slop, eyebrow badge soup, colored left-border cards, cramped spacing, collision of Nordic diacritics (ÅÄÖ), and presentation overflow across websites, decks, documents, dashboards, and generative media."
version: 1.3.0
author: Stay Bright & Bright Mind Agency
license: MIT
platforms: [linux, macos, windows]
metadata:
  hermes:
    tags: [design, taste, ui-ux, anti-ai-slop, typography, stripe, linear, vercel, minimal, kiosk, slides, documents, swedish-typography]
---

# 💎 Bright Design Skill (The Global Taste & UI/UX Engine)

The **Bright Design Skill** is the unified design foundation across all Stay Bright, Bright Mind Agency, and Oriiion agents. It enforces uncompromising aesthetic taste, human craftsmanship, and high-performance UI engineering across every digital deliverable (web interfaces, presentation decks, PDF reports, marketing collateral, and generative visual prompts).

---

## 🚫 The Anti-AI-Slop Laws (Strictly Enforced)

Every AI agent suffers from default "AI slop" if unconstrained. The Bright Design system strictly prohibits:

1. **No Diacritic Collisions (The Å, Ä, Ö Rule):**
   - **BANNED:** Never use `line-height: 0.9` to `1.0` or `leading-none` on multi-line headings in Swedish or languages with diacritics (`Å`, `Ä`, `Ö`, `å`, `ä`, `ö`). Rings and umlauts smash directly into the text above.
   - **MANDATED:** Multi-line headings with diacritics must always have `line-height: 1.15` to `1.20` (`leading-[1.15]` or `leading-tight`) to ensure clean optical separation between rows.
2. **Strict Viewport Height Budgeting (Zero Presentation Overflow):**
   - **BANNED:** Never allow cards or content to bleed off the bottom of the screen in presentation decks or kiosk displays.
   - **MANDATED:** Always budget inside `100vh`. Constrain viewports to `max-h-[calc(100vh-140px)]`. Use fluid typography clamps (`clamp(2rem, 4vw, 4.5rem)`) so headlines scale gracefully on laptops, iPads, and displays without pushing body cards below the fold.
3. **No Eyebrow Pills or Micro-Notes Above Headlines:**
   - **BANNED:** Never place floating pill chips with pulsing dots (`● CATEGORY · STATUS`) hovering right above main titles. This is one of the most glaring AI-slop tells on the internet. A strong headline commands the space on its own.
4. **No Colored Left-Border Accent Cards:**
   - **BANNED:** Never use `border-l-2` or `border-l-4` colored indicator lines on cards (the classic Jira / Bootstrap / AI-generated alert card pattern). Cards must be solid, cohesive, and framed by uniform hairline borders (`1px solid #1E222D`) or pure typographic hierarchy.
5. **No Cramped or Low Spacing (Enforce Generous Whitespace):**
   - **BANNED:** AI models constantly cram elements together with tight 8px–12px margins, making interfaces look suffocated. Enforce generous, deliberate padding and whitespace (`py-8 md:py-12`, `gap-6 md:gap-8`). Let elements breathe.
6. **Zero Cheesy Glassmorphism & Frosted Blur:**
   - **BANNED:** Do NOT use milky translucent cards with `backdrop-filter: blur()` or blurry floating panels. Use solid, opaque, razor-sharp dark surfaces (`#050608`, `#0D0E12`, `#13151B`) with crisp 1px hairlines.
7. **Zero Fullscreen Scroll Wobble:**
   - Presentation decks and kiosk interfaces are strictly constrained to `100vh` with zero accidental scrollbars.

---

## 🎨 The Bright Visual Language & Brand System

### 1. High-Impact Typography & Diacritic Safety
* **Headlines:** **Poppins** in ultra-heavy weight (`900 Black`). Always uppercase, compressed tracking (`letter-spacing: -0.04em` to `-0.05em`), and diacritic-safe line-height (`1.15` to `1.20`).
* **Fluid Scaling:** Use CSS clamp for headlines in presentations: `clamp(2rem, 4vw, 4.5rem)` so text naturally accommodates screen height.
* **Body Copy:** **Inter** (`400 Regular` / `500 Medium`), crisp line-height (`1.6`), max line width 65 characters (`max-w-2xl`).
* **System Metrics:** **JetBrains Mono** (`10px` to `12px`), uppercase with wide tracking (`0.1em`).

### 2. Solid Surface Elevation (Zero Glassmorphism)
* **Canvas:** Deep solid black canvas (`#050608` or `#08090C`).
* **Solid Panels:** Solid opaque surfaces (`#0D0E12`, `#13151B`, `#1A1D26`) with razor-sharp 1px border strokes (`#1E222D` / `#282D3B`).
* **Dividers:** Razor-sharp hairlines (`rgba(255, 255, 255, 0.06)`).

### 3. Cyber-Luminous & Brand Accent Palette
* **Neon Teal (`#3BD194`):** Primary action, verified metrics, live indicators.
* **Berry Magenta (`#9B3793`):** Critical callouts, secondary highlights.
* **Royal Purple (`#783797`) & Slate Blue (`#556D97`):** Structural gradient and infrastructure nodes.
* **Luminous Cyan (`#00F0FF`) & Yellow (`#FFD700`):** Revenue highlights and transactional badges.

---

## 🛠️ The 7 Core Craft Disciplines

1. **`typeset` (Typography Craft):** Optical kerning, diacritic-safe leading (`1.15+`), zero overlapping ÅÄÖ.
2. **`colorize` (Chromatic Hierarchy):** 1 dominant solid dark surface, 1 high-contrast crisp text tier, and max 2 vibrant accents.
3. **`layout` (Spatial Geometry):** Generous, deliberate whitespace rhythm. Viewport-budgeted vertical height.
4. **`animate` (Physics-based Motion):** Spring curves over linear transitions (`cubic-bezier(0.16, 1, 0.3, 1)`).
5. **`delight` (Sensory Polish):** Clean hairline alignments, subtle hover states, real data.
6. **`critique` (Truth & Quality Audit):** Pre-flight validation ensuring zero placeholder text, verified numbers, and absence of AI card tells.
7. **`harden` (Cross-device Resilience):** Responsive viewport constraints, touch-friendly targets, and zero overflow on 13" screens.
