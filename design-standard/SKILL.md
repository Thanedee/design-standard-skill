---
name: design-standard
description: "Professional design standard for any visual: social posts, carousels, flyers, logos, slides, video, print, web and AI-generated images. Use when creating, editing or reviewing a design."
---

# Design Standard

Use this skill whenever you create, edit, brief or review a visual: a social media post or carousel, flyer, poster, invitation, logo or brand system, presentation, infographic or chart, video or motion piece, print file, web or app screen, or an image made with an AI image generator (ChatGPT, Gemini, Midjourney, Flux, Firefly and others).

The full guide, with research sources, lives in `references/`. Read this file first, then open only the reference files the task needs (index below).

## Core standard

Clarity first, hierarchy second, consistency third. Aesthetics serve the message and never hide it.

When rules conflict, decide in this order:

1. Truth and legality
2. Legibility and accessibility
3. Hierarchy and message
4. Brand consistency
5. Aesthetic preference

Where a client's brand guideline conflicts with this standard, the brand guideline wins on identity (colour, type, logo) and this standard wins on legibility, accuracy and accessibility.

## Workflow for every design task

1. **Restate the brief** in one sentence: objective, audience, format and size, single message, call to action. If you cannot, ask before designing.
2. **Get the exact copy.** Use only the text supplied, spelt exactly. Use the audience's own terms (for Nigerian property work: "tenancy agreement", not "lease").
3. **Choose the format and canvas** from `references/11-platform-specs.md`. Default social feed post: 1080 x 1350 px (4:5). Vertical video: 1080 x 1920 px, with all key content inside a centred 900 x 1400 px safe area.
4. **Build on a grid** with an 8 px spacing scale and margins of at least 64 px on a 1080 px canvas.
5. **Set one focal point** and a clear first, second and third read.
6. **Apply type and colour rules** (minimums below).
7. **If using an AI image generator**, follow the AI guardrails below and `references/17-ai-guardrails.md`.
8. **Run the quality check** below, plus `references/20-quality-control.md`, on the exported file before presenting it.

## Non-negotiable minimums (MUST)

- **Contrast:** body text at least 4.5:1 against its background; large text (24 px or more, or 18.5 px bold) at least 3:1; icons and chart parts at least 3:1 (WCAG 2.2 AA).
- **Text size on a 1080 px wide social graphic:** headline 60 px or more, body 32 px or more, footnote 24 px or more, about 30 to 40 words per graphic at most. Web body text 16 px or more. Print body 9 to 12 pt.
- **If the text does not fit, cut the copy, never the size.**
- **One primary message and one primary call to action.**
- **Never carry meaning by colour alone** (about 1 in 20 men has a colour-vision deficiency).
- **Safe areas:** nothing important in the outer 5% of the canvas or under platform overlays.
- **Accuracy:** every word, number, name, date, price and contact detail checked letter by letter against the source.
- **Rights:** only licensed images, fonts and music; consent from identifiable people; no national emblems (such as a coat of arms) in commercial work without authority.
- **Carousels and multi-page pieces:** one identical layout on every page. Vary the layout between posts, not within a set.
- **Alt text** on every informative image and **captions** on every video.

## Typography defaults

- One or two type families. A fixed type scale with a clear ratio between levels (headline at least 2.5 times the body size on social graphics).
- Body leading 1.4 to 1.6; headline leading 1.0 to 1.2.
- Line length: 45 to 75 characters for body text, 30 to 50 on mobile and social.
- All caps only for short labels, tracked +5% to +12%.
- No single word alone on the last line of a headline. Break display lines by meaning.
- Curly quotes, en dashes for ranges (₦12–18m), and check that the font contains every glyph needed (₦, Yoruba, Igbo and Hausa letters).

## Colour defaults

- Roughly 60% dominant, 30% secondary, 10% or less accent. One saturated accent; neutralise the rest.
- Choose harmonies from the colour wheel: monochromatic, analogous, complementary, split-complementary, triadic or tetradic. See `references/05-colour.md` and the images in `assets/`.
- Bright warm accents (coral, gold, lime, yellow) work on dark backgrounds or as large shapes, not as small text on white.
- Design for screens in sRGB. Print in the printer's CMYK profile, with Pantone for exact brand colours.

## AI image guardrails (summary)

- Treat every AI image as a draft that may contain invented facts, misspelt or malformed characters, phantom logos, seals or crests, layout drift, or a changed face.
- Brief with a full prompt: purpose, size, layout, palette (HEX), type style, the exact text in quotes, image subject, and constraints ("no logos, no coats of arms, no watermarks, no extra text or numbers").
- **Change one thing per edit request**, and say "keep everything else exactly the same". Repeat the preserve list every time.
- Prefer generating the image without text and setting the type in a design tool, HTML or SVG, so the words are exact.
- Before presenting AI output, verify: text, facts, marks, consistency with the approved master, the guide minimums, people, rights and disclosure (`references/17-ai-guardrails.md`, section 17.6). Report any mismatch instead of presenting the image as final.
- Do not strip Content Credentials (C2PA) metadata. Disclose AI use where a viewer would care, especially realistic people, places and products.

## Quality check before presenting

Revise if any of these fail, whatever else is good:

1. A wrong word, number, name, date, price or contact detail.
2. An invented fact, logo, seal, coat of arms or watermark.
3. Text below the minimum size, or contrast below 4.5:1 (3:1 for large text).
4. No clear focal point or reading order.
5. Essential content outside the safe area or cut by a platform crop.
6. Meaning carried by colour alone.
7. Rights not cleared.
8. Off-brand palette, type or logo misuse.
9. Missing disclosure or regulatory approval (paid partnership, AI realism, ARCON approval for Nigerian adverts).
10. Inconsistent layout within a carousel or multi-page piece.

Then score each category in `references/20-quality-control.md` from 0 to 10; every category must reach at least 8.

## Reference index

| File | Open when |
| --- | --- |
| `references/00-how-to-use.md` | Rule grades (MUST, SHOULD, MAY), evidence levels, order of judgement |
| `references/01-perception-cognition.md` | Explaining why a design works: first impressions, fluency, Gestalt, scanning patterns |
| `references/02-core-principles.md` | Hierarchy, contrast, alignment, proximity, balance, whitespace |
| `references/03-composition-layout-grids.md` | Grids, spacing scale, safe areas, ratios, cropping, tangencies |
| `references/04-typography.md` | Choosing fonts, sizes by medium, type scales, leading, line breaks |
| `references/05-colour.md` | Palettes, the colour wheel, harmonies, what goes with what, sector palettes, contrast pairs, colour meaning in Nigeria |
| `references/06-imagery-icons.md` | Choosing, cropping and treating photos, illustration, icon systems |
| `references/07-information-design-dataviz.md` | Charts, honest axes, infographics |
| `references/08-copy-content.md` | Headlines, word budgets, calls to action, terminology, proofreading |
| `references/09-brand-identity-logos.md` | Identity systems, logo design and usage, series consistency |
| `references/10-accessibility.md` | WCAG 2.2 numbers, alt text, motion safety, inclusive representation |
| `references/11-platform-specs.md` | Canvas sizes and safe zones for Instagram, LinkedIn, TikTok, Reels, Shorts, YouTube, slides, email |
| `references/12-motion-video.md` | Short-form video structure, captions, animation timing, audio |
| `references/13-print-production.md` | Bleed, resolution, CMYK, ink limits, paper, PDF/X |
| `references/14-ui-ux-web.md` | Usability heuristics, touch targets, component states, deceptive patterns |
| `references/15-cultural-context-nigeria.md` | Localisation, Nigerian terms, currency, calendar, symbols |
| `references/16-legal-ethics.md` | Copyright, AI ownership, likeness and privacy, ARCON, advertising claims |
| `references/17-ai-guardrails.md` | Prompt template, edit discipline, failure modes, verification protocol, disclosure |
| `references/18-design-process.md` | Briefs, concepts, critique, versioning, testing |
| `references/19-file-delivery.md` | Export formats, compression, naming, handover |
| `references/20-quality-control.md` | Scoring rubric and pre-flight checklists by format |
| `references/21-glossary-sources.md` | Definitions and the research sources behind each rule |
| `assets/colour_wheel.png` | The 12-hue colour wheel with tints, tones and shades |
| `assets/colour_harmonies.png` | Six colour harmonies with example swatches |
