# COMPRINT // Design System

> **The System Core.** A tech-forward, minimal, engineered brand. Linear / Vercel / Anthropic, lit by a single blue spotlight.

[**↗ View live previews**](https://vansh-comprint.github.io/comprint-design/) · [**↗ Open the deck**](https://vansh-comprint.github.io/comprint-design/slides/)

<p align="center">
  <img src="assets/previews/brand-signature.png" alt="Signature visual — grid + spotlight" width="720">
</p>

---

## Preview

### Brand

| Logo | Signature visual |
| :--- | :--- |
| <img src="assets/previews/brand-logo.png" width="420" alt="Brand logo"> | <img src="assets/previews/brand-signature.png" width="420" alt="Signature visual"> |
| **Ghost type** | **Corner metadata** |
| <img src="assets/previews/brand-ghost-type.png" width="420" alt="Ghost type"> | <img src="assets/previews/brand-metadata.png" width="420" alt="Corner metadata"> |

### Color

| | |
| :--- | :--- |
| <img src="assets/previews/color-black.png" width="420" alt="Black family"> | <img src="assets/previews/color-white.png" width="420" alt="White family"> |
| <img src="assets/previews/color-greys.png" width="420" alt="Slate greys"> | <img src="assets/previews/color-blue.png" width="420" alt="Signature blue"> |

<p align="center">
  <img src="assets/previews/color-gradients.png" alt="Gradients — spotlight, beam, surface, panel" width="720">
</p>

### Typography

| | |
| :--- | :--- |
| <img src="assets/previews/type-display.png" width="420" alt="Display — Chakra Petch 900"> | <img src="assets/previews/type-body.png" width="420" alt="Body type"> |
| <img src="assets/previews/type-mono.png" width="420" alt="Mono — TWK Everett Mono"> | <img src="assets/previews/type-eyebrow.png" width="420" alt="Eyebrow labels"> |

<p align="center">
  <img src="assets/previews/type-scale.png" alt="Type scale" width="720">
</p>

### Spacing & elevation

| Scale | Radii | Elevation |
| :--- | :--- | :--- |
| <img src="assets/previews/spacing-scale.png" width="280" alt="Spacing scale"> | <img src="assets/previews/spacing-radii.png" width="280" alt="Radii"> | <img src="assets/previews/spacing-elevation.png" width="280" alt="Elevation / shadows"> |

### Components

| | |
| :--- | :--- |
| <img src="assets/previews/comp-buttons.png" width="420" alt="Buttons"> | <img src="assets/previews/comp-cards.png" width="420" alt="Cards"> |
| <img src="assets/previews/comp-inputs.png" width="420" alt="Inputs"> | <img src="assets/previews/comp-stats.png" width="420" alt="Stat tiles"> |

### Sample deck (16:9)

<p align="center">
  <img src="assets/previews/slides/slide-01.png" alt="Slide 1 — Title" width="720"><br>
  <img src="assets/previews/slides/slide-02.png" alt="Slide 2 — Section divider" width="720"><br>
  <img src="assets/previews/slides/slide-03.png" alt="Slide 3 — Content" width="720"><br>
  <img src="assets/previews/slides/slide-04.png" alt="Slide 4 — Stats grid" width="720"><br>
  <img src="assets/previews/slides/slide-05.png" alt="Slide 5 — Closing" width="720">
</p>

---

## Brand DNA

| | |
|---|---|
| **Name** | COMPRINT |
| **Tagline** | The System Core |
| **Personality** | Precise · Intelligent · Restrained · Engineered |
| **Vibe** | Swiss-engineered terminal. Satellite display at 3am. Well-lit server room. |
| **Not** | Playful · warm · retro · generic-SaaS · maximalist |

---

## Sources

- **Brand brief & spec** — pasted into the project start prompt (full system doc, paste-ready AI prompt, templates).
- **Logo artwork** — `uploads/Screenshot 2026-04-21 190919.png` (dark-on-light) and `uploads/Screenshot 2026-04-21 190941.png` (light-on-dark), copied into `assets/`.

No codebase or Figma file was provided. The system is authored from the brand brief directly.

---

## Content Fundamentals

**Voice:** confident, technical, spare. Sentences are short. Data speaks. No hype.
**Pronouns:** neutral / third-person product voice ("COMPRINT looks like…"). Avoid "we"/"you" marketing tone.
**Casing:** Display text is UPPERCASE. Headlines sentence case. Eyebrow labels ALL CAPS with 0.3em tracking.
**Punctuation:** em dashes for asides. The `|` pipe divider separates action + context ("+ Create | Brand Intelligence"). Terminal-style `//` for section markers ("// BEAM").
**Numbers:** tabular, confident. "99.2%" over "about 99%". Stats set in Chakra Petch 900.
**Forbidden:** emoji, exclamation marks, hype adjectives ("revolutionary", "game-changing"), generic SaaS phrases.

**Examples on-brand:**
> THE SYSTEM CORE
> Q1 2026 // Product Vision
> Precise. Intelligent. Engineered.
> + Create | Brand Intelligence

**Examples off-brand:**
> ✨ Revolutionize your workflow!
> Unleash the power of AI to transform your business
> Join thousands of happy customers 🚀

---

## Visual Foundations

- **Palette (4 families, strict):** Black `#000/#020617/#0F172A` · White `#FFFFFF` + dim/faint overlays · Slate greys `#F8FAFC → #0F172A` · Signature blue `#2563EB` (+ light `#93C5FD`, deep `#1D4ED8`). **No other hues, ever.**
- **Type:** **TWK Everett Mono** is the system face — every label, eyebrow, heading, button, caption and metadata block. **Chakra Petch 900** is reserved exclusively for the COMPRINT wordmark (logo + tagline lockup). **Inter** is allowed for long-form prose paragraphs only — descriptions, body copy beyond a sentence — where mono becomes hard to read.
- **Backgrounds:** Dark deep `#020617` with the **Signature Visual** (8% white grid, 80px cells, single blue-white spotlight from top-left). Light surfaces use the panel gradient `#FFF → #F8FAFC`. No photography. No illustrations. No mesh gradients.
- **Gradients:** Only four allowed — Spotlight (radial), Beam (linear 135deg), Surface (dark), Panel (light). Never pink/purple mesh.
- **Borders:** `1px solid` on dividers. On dark surfaces, `rgba(255,255,255,.08)` (white-faint). On light, `--grey-100`.
- **Shadows:** Soft, never > 20% opacity. `sm / md / lg / xl` tiers. A special `blue-glow` `0 0 24px rgba(37,99,235,.25)` reserved for primary CTAs on dark.
- **Corners:** **No radii anywhere.** Every surface is a sharp rectangle. The brand interaction motif is the **chamfer** — a 10–14px diagonal cut on the top-left + bottom-right corner — applied via `clip-path` to primary CTAs (`.btn.cut`) and the occasional hero card (`.card.cut`). Use sparingly: one chamfered surface per layout, not every element.
- **Layout:** 12-column grid, 32px gutters, **64px minimum slide margin**. Off-center, directional. One focal point per slide. Metadata in all four corners (eyebrow type).
- **Ghost type:** Oversized faded words (30–40% opacity, same weight as headline) sit behind hero elements for depth.
- **Animation:** Logo dot pulses 1.5s. Spotlight drifts 8s. Slide transitions: fade + 20px upward slide, 400ms ease-out. Never wipe, spin, zoom. Hover: `scale(1.02)` in 200ms ease. No color change unless state-driven.
- **Press states:** Slight darken toward `--blue-deep` + `scale(.98)`. No hue shift.
- **Transparency & blur:** Transparency only in white-faint borders and ghost type. **No glassmorphism** — it has aged poorly.
- **Imagery temperature:** Cool, blue, high-contrast. No warm tones. No sunsets. No people unless a hand-holding-device mockup lit in blue.
- **Cards:** Sharp 0px corners by default — 1px border in palette grey, `shadow-md` on light or `white-faint` border on dark. No colored left-border accent. Add `.cut` to apply a 14px chamfer for the single hero card per layout.
- **The `|` divider motif** separates action + context in UI: `+ Create | Brand Intelligence`.

---

## Iconography

The brand brief does not ship an icon set. **No icons were found in the provided assets** — only the wordmark. Guidance:

- **Preferred system:** `lucide-react` / Lucide SVG via CDN (`https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/`). Stroke weight 1.5–2px, line style, square terminals — fits the Chakra Petch engineered aesthetic.
- **Substitute flag ⚠️:** Lucide is a *substitute choice*, not a confirmed system. If COMPRINT adopts a specific icon set (e.g. a custom kit or Phosphor), replace `assets/icons/` and update this section.
- **Emoji:** **Never in deliverables.** (Allowed in internal notes/Slack.)
- **Unicode:** The `|` pipe is the only non-ASCII character used as a visual element. Square dot in the logo is drawn with a 0.25em CSS block, not a Unicode character.
- **Logo assets:** `assets/logo-dark.png` (wordmark for light backgrounds), `assets/logo-light.png` (wordmark for dark backgrounds). Favicon / icon lockup is `C·` — render via CSS at any size (see `preview/brand-logo.html`).

---

## ⚠️ Font Status

**Chakra Petch (display):** ✅ Local TTFs wired in (`fonts/ChakraPetch-*.ttf`), weights 300–700. The brief asks for **weight 900** — not shipped in this set. The stack maps `900`/`800` → `Bold (700)`, so everything renders, but it'll read slightly lighter than the spec intends. If you want true 900, export a heavier master or license the Black weight.

**TWK Everett Mono:** ✅ Local OTFs wired in (`fonts/TWKEverettMono-*.otf`), weights 100–950. This is the *monospaced* cut — not the proportional TWK Everett the brief originally called for. **The system has been pivoted to lean into the mono.** `--font-body` now resolves to TWK Everett Mono — every label, eyebrow, heading, button and caption sits on the monospaced grid, which doubles down on the engineered terminal aesthetic. Inter is held in reserve as `--font-prose` for the rare paragraph of long-form copy.

**Decide:** (a) keep Inter for body + use Mono for data/tech UI (current setup), or (b) ship proportional TWK Everett files and I'll swap `--font-body` over.

---

## File Index

```
/                         ← this README
index.html                ← live landing page (GitHub Pages root) — gallery + deck link
colors_and_type.css       ← all CSS vars (color, type, spacing, shadow, motion)
SKILL.md                  ← agent-skill manifest (Claude Code compatible)
assets/
  logo-dark.png             wordmark on light
  logo-light.png            wordmark on dark
  previews/                 ← rendered PNG snapshots of every preview card + slide (used by README)
preview/                  ← Design System tab cards (700px wide)
  color-*.html              palette cards (black / white / greys / blue / gradients)
  type-*.html               display / body / scale / eyebrow specimens
  spacing-*.html            scale / radii / elevation
  comp-*.html               buttons / cards / inputs / stat tiles
  brand-*.html              logo / signature visual / ghost type / corner metadata
slides/                   ← UI kit: sample 16:9 deck
  index.html                 5-slide deck (Title / Section / Content / Stats / Closing)
  deck-stage.js              deck shell component (keyboard nav, scaling, print)
```

---

## Quick Use

```html
<link rel="stylesheet" href="colors_and_type.css">

<!-- Signature visual background -->
<section class="comprint-stage" style="height: 100vh;">
  <div class="logo" style="color:#fff; font-size: 80px;">COMPRINT</div>
</section>

<!-- Primary CTA -->
<button class="btn btn-primary">+ Create <span class="pill-divider">|</span> Brand Intelligence</button>
```

---

*COMPRINT · The System Core*
