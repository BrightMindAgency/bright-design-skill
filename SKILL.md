---
name: bright-design
description: "Global design, aesthetic taste, and UI/UX engineering system for Stay Bright & BMA agents. Eliminates AI slop across websites, decks, documents, dashboards, and generative media using strict typography, layout rhythm, dark-glassmorphism, CMY glow, and 50+ enterprise design blueprints."
version: 1.0.0
author: Stay Bright & Bright Mind Agency
license: MIT
platforms: [linux, macos, windows]
metadata:
  hermes:
    tags: [design, taste, ui-ux, anti-ai-slop, typography, stripe, linear, vercel, glassmorphism, kiosk, slides, documents]
---

# 💎 Bright Design Skill (The Global Taste & UI/UX Engine)

The **Bright Design Skill** is the unified design foundation across all Stay Bright, Bright Mind Agency, and Oriiion agents. It enforces uncompromising aesthetic taste, human craftsmanship, and high-performance UI engineering across every digital deliverable (web interfaces, presentation decks, PDF reports, marketing collateral, and generative visual prompts).

---

## 🚫 The Anti-AI-Slop Laws

Every AI agent suffers from default "AI slop" if unconstrained. The Bright Design system strictly prohibits:
1. **No Generic Rounded Pastel Blobs:** Do not use uninspired 3D rendered floating balls, generic flat vector cartoons, or meaningless gradient soup.
2. **No Unconstrained Typography:** Never mix 4+ competing fonts. Never use center-aligned long paragraphs. Never use standard un-tracked headings.
3. **No Brittle Drag-and-Drop Mess:** Avoid overly complex nested div trees with arbitrary margin hacks. Build rigid, clean CSS grids or flexbox layouts with standard rhythm units (4px, 8px, 16px, 24px, 32px, 48px, 64px).
4. **No Low-Contrast Gray Text on Dark Backgrounds:** Enforce APCA/WCAG contrast ratios. Primary text must be crisp (`#FFFFFF` or `#F1F5F9`), secondary text muted but legible (`#94A3B8`), and accents luminous.
5. **No Scrollbar Wobble on Fullscreen Presentations:** Kiosk applications and presentation slides must be constrained strictly to `100vh` / `max-h-[calc(100vh-140px)]` with zero accidental scrollbars.

---

## 🎨 The Bright Visual Language & Brand System

### 1. High-Impact Typography Hierarchy
* **Hero Titles & Captions:** **Poppins** or **Plus Jakarta Sans** in ultra-heavy weight (`900 Black` or `800 ExtraBold`). Always styled uppercase, compressed tracking (`letter-spacing: -0.04em` to `-0.05em`), and tight line-height (`0.9` to `1.05`).
* **Body & Editorial Copy:** **Inter** or **Geist Sans** (`400 Regular` / `500 Medium`), left-aligned, crisp line-height (`1.5` to `1.6`), max line width 65 characters (`max-w-prose` or `max-w-2xl`).
* **Tech Badges, Timestamps & Metrics:** **JetBrains Mono**, **Geist Mono**, or **Space Mono** (`10px` to `12px`), uppercase with wide tracking (`tracking-widest` or `0.1em`), paired with subtle translucent pill borders.

### 2. Dark Glassmorphism & Surface Elevation
* **Base Void:** Deep black canvas (`#030508` or `#05070A`).
* **Translucent Glass Panels:**
  ```css
  background: rgba(14, 18, 27, 0.72);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
  border: 1px solid rgba(255, 255, 255, 0.07);
  box-shadow: 0 20px 50px -10px rgba(0, 0, 0, 0.8);
  ```
* **Dividers & Borders:** Razor-sharp 1px subtle strokes (`rgba(255, 255, 255, 0.06)`).

### 3. The Cyber-Luminous CMY Accent Palette
* **Cyan Glow (`#00F0FF`):** Primary action, validated traction badges, interactive active states (`box-shadow: 0 0 30px rgba(0, 240, 255, 0.35)`).
* **Magenta Glow (`#FF007A`):** Critical alerts, market problems, secondary highlights (`box-shadow: 0 0 30px rgba(255, 0, 122, 0.35)`).
* **Yellow Glow (`#FFD700`):** Revenue metrics, cash flow, % rev-share highlights (`box-shadow: 0 0 30px rgba(255, 215, 0, 0.35)`).
* **Electric Blue (`#0066FF`):** Enterprise gradients, structural infrastructure nodes.

---

## 🛠️ The 7 Core Craft Disciplines

When building any interface or document, execute these 7 quality checks:

1. **`typeset` (Typography Craft):**
   - Optical balance: match heading scale to viewport.
   - Micro-hierarchy: Eyebrow label $\rightarrow$ Heavy Title $\rightarrow$ Short Summary $\rightarrow$ Data Chips.
2. **`colorize` (Contrast & Chromatic Hierarchy):**
   - Establish 1 dominant neutral surface, 1 high-contrast text color, and maximum 2 vibrant accent highlights.
3. **`layout` (Spatial Geometry):**
   - Asymmetric grids with strong alignment lines. Give content breathing room (`p-8 md:p-14`).
4. **`animate` (Physics & Micro-interactions):**
   - Spring curves over linear transitions: `cubic-bezier(0.16, 1, 0.3, 1)` for snappy, weightless UI responsiveness.
5. **`delight` (Sensory Details):**
   - Subtle background ambient radials, hover glows, pulsing status dots, and crisp icon pairings (FontAwesome Pro / Lucide).
6. **`critique` (Pre-flight Audit):**
   - Is it immediately obvious what this is? Are numbers verified? Is there any placeholder Latin/lorem ipsum? (Strict truth constraint).
7. **`harden` (Cross-device Resilience):**
   - Responsive breakpoints (`sm`, `md`, `lg`, `xl`), touch-friendly targets ($\ge 44\text{px}$), keyboard navigation bindings.

---

## 🏢 50+ Curated Enterprise Design Blueprints

Available under `design-systems/`:
* **Linear Style (`design-systems/linear/`):** Dark keyboard-first UI, subtle borders, high contrast, monochrome base with electric accent.
* **Stripe Style (`design-systems/stripe/`):** Fluid mesh gradients, micro-typography, robust multi-column data tables.
* **Vercel / Geist Style (`design-systems/vercel/`):** Geometric monochrome, razor-sharp grid lines, high-density developer consoles.
* **Apple Style (`design-systems/apple/`):** Cinematic typography, large imagery, subtle frosted glass overlays.
* **Supabase / Raycast / Cursor Style:** High-velocity developer dashboards with command palettes and status indicators.

---

## 📦 Deliverables & File Generation Protocols

### 1. Interactive Single-File HTML Presentation / Kiosk Decks
* Self-contained HTML with Tailwind CSS CDN, Google Fonts, and embedded JavaScript slide router.
* Keyboard binds: `ArrowRight`/`Space` (Next), `ArrowLeft` (Prev), `F` (Fullscreen), `N` (Speaker Notes), `O` (Overview Grid).
* Deploy to public static folder (`public-share`) and deliver via Tailscale Funnel HTTPS links.

### 2. PDF & Graphical Document Generation
* Use Matplotlib or Typst with high DPI (`dpi=300`), dark background `#0A0C10`, Poppins/Inter font rendering, and CMY colored bar/line charts.

### 3. Generative Media & Image Prompts (Midjourney / FLUX)
* Avoid generic keywords ("high quality 8k").
* Use architectural, lighting, and medium-specific descriptors: *"Cinematic wide-angle shot, 35mm lens, Hasselblad H6D-100c, dark minimalist Scandinavian architectural studio, neon cyan accent illumination, volumetric lighting, photorealistic material textures, ray-traced shadows, hyper-detailed --ar 16:9 --v 6.0"*.
