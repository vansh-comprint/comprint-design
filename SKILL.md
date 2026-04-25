---
name: comprint-design
description: Use this skill to generate well-branded interfaces and assets for COMPRINT, either for production or throwaway prototypes/mocks/etc. Contains essential design guidelines, colors, type, fonts, assets, and UI kit components for prototyping.
user-invocable: true
---

Read the `README.md` file within this skill, and explore the other available files.

Key files:
- `README.md` — brand DNA, content fundamentals, visual foundations, iconography, file index
- `colors_and_type.css` — all tokens: color, type, spacing, radii, shadow, motion, plus `.comprint-stage` (grid + spotlight) and `.logo` (pulsing square dot)
- `preview/*.html` — individual design-system specimens (colors, type, spacing, components, brand)
- `slides/index.html` + `slides/deck-stage.js` — 5-slide 16:9 deck template (Title / Section / Content / Stats / Closing)
- `assets/logo-dark.png`, `assets/logo-light.png` — official wordmark

If creating visual artifacts (slides, mocks, throwaway prototypes), copy the relevant assets out and create static HTML files for the user to view. If working on production code, copy the tokens from `colors_and_type.css` and read the rules in `README.md` to become an expert in designing with this brand.

**Non-negotiables:**
- Strict 4-color palette (black / white / slate greys / signature blue `#2563EB`). No pink, purple, green, orange, warm tones.
- Chakra Petch 900 UPPERCASE (-0.03em tracking) for display; Inter for body.
- Signature Visual (dark grid + single blue-white spotlight) on title / hero / section slides.
- Pulsing square dot is always part of the logo — never separate it.
- Pill buttons (999px), 24–32px card radius, 64px minimum slide margin.
- Eyebrow labels (11px 500 weight, 0.3em tracking, UPPERCASE, grey-500) above every section.
- Never: emoji, stock photography of people, glassmorphism, drop shadows > 20% opacity, center-aligned body copy, Chakra Petch for body.

If the user invokes this skill without any other guidance, ask them what they want to build or design, ask some questions, and act as an expert designer who outputs HTML artifacts _or_ production code, depending on the need.
