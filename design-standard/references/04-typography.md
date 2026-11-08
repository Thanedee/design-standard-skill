# 4. Typography

Type is information architecture: use one or two families, a fixed size scale, comfortable line length and spacing, and sizes that survive the real viewing distance. Most amateur work fails on size and spacing, not font choice.

### 4.1 Anatomy and classification (vocabulary you must share)

- **Anatomy:** baseline, x-height, cap height, ascender, descender, counter, stroke contrast, terminal, serif.
- **Classes:** serif (old-style, transitional, modern/Didone, slab), sans-serif (grotesque, neo-grotesque, humanist, geometric), script, display/decorative, monospace.
- **x-height drives legibility.** Two fonts at the same point size can differ in apparent size by 20% or more; compare x-heights, not point sizes. Legge and Bigelow’s review of vision science and typography found reading is fastest across a fluent range of sizes above a “critical print size”, and that most print and screen text sits near the bottom of that range ([Journal of Vision 11(5), 2011](https://legge.dl8.umn.edu/sites/legge.psych.umn.edu/files/2020-08/Legge%20Bigelow%202011%20Does%20size%20matter%20for%20reading%3F%20A%20review%20of%20findings%20from%20vision%20science%20and%20typography.pdf)). Err larger. **\[Research\]**

### 4.2 Choosing and pairing typefaces

- **SHOULD:** one family for most work, two at most (a display face plus a text face); a third only for a deliberate accent.
- Pair by **contrast in one dimension** (serif with sans, or condensed with regular) and **harmony in others** (similar x-height, era or proportions).
- Choose families with a full weight range (at least regular, medium, bold), true italics, and complete glyph coverage. **MUST** check special characters before committing: ₦ (naira), €, £, –, —, curly quotes, and accented letters for Yoruba, Igbo and Hausa (ẹ, ọ, ṣ, à, á, ǹ, ɓ, ɗ, ƙ).
- Screen text: favour faces with large x-height, open apertures and clear letter differentiation (I, l, 1; O, 0; rn vs m).
- Display faces and scripts are for a few words only, never body copy.

### 4.3 Size: minimums by medium

| Medium | Body / supporting text | Headline | Notes |
| --- | --- | --- | --- |
| Web page | 16 px minimum, 18–20 px preferred | 32–64 px | Never below 12 px for any visible text |
| Mobile app | 16–17 px body | 22–34 px | Respect system text-size settings |
| Social post, 1080 px wide canvas | 28–36 px minimum (about 2.6–3.3% of width) | 72–140 px | Seen at roughly a third of its size on a phone |
| Presentation (16:9, 1920 px) | 24 pt / 32 px minimum | 40–60 pt | One idea per slide |
| Print document (A4) | 9–12 pt | 18–36 pt | 8 pt absolute floor for legal small print |
| Flyer (A5/A4) | 10–14 pt | 36–72 pt | Read at arm’s length |
| Poster / signage | 2.5 cm cap height per 7–10 m of viewing distance | — | Rule of thumb for distance legibility |

**Rule (MUST):** if text must shrink below these minimums to fit, cut the copy (section 8), never the size.

### 4.4 Type scale

- Define 4–6 levels: display, headline, subhead, body, caption, label. Each level differs from its neighbour by a clear ratio.
- Common ratios: 1.25 (major third, dense UIs), 1.333 (perfect fourth, general), 1.5 (perfect fifth, editorial), 1.618 (golden, posters). Example at 1.333 from 16 px: 16 / 21 / 28 / 38 / 50 / 67.
- For social graphics a steep scale works best: headline at least 2.5× body size.

### 4.5 Line length (measure)

- **SHOULD:** 45–75 characters per line for body text (66 ideal for print); 30–50 on mobile and in social graphics.
- Dyson’s reviews found people read on-screen text slightly faster at long lines (around 100 characters) but **prefer** 45–72 characters ([summary, O’Reilly](https://oreilly.com/library/view/100-things-every/9780132658638/ch18.html)). Design for comfort and comprehension, not raw speed. **\[Research\]**

### 4.6 Leading (line spacing)

- Body text: 1.4–1.6 × font size (WCAG 2.2 requires layouts to survive 1.5×; section 10).
- Headlines and display: 1.0–1.2 ×. Tight, but ascenders and descenders must never touch.
- Longer lines need more leading; all-caps needs less.
- Paragraph spacing: about 0.75–1.0 × the font size, or first-line indents, never both.

### 4.7 Tracking and kerning

- All-caps and small labels: +5% to +12% tracking (50–120 units).
- Large display type: –1% to –3% (tighter); body text: 0.
- Check kerning on display type manually: AV, To, Wa, LT, Ty and number pairs.
- **MUST NOT** stretch, squash, skew or fake bold/italic type.

### 4.8 Case and capitalisation

- Lowercase text is read about 5–10% faster than ALL CAPS, mainly because readers practise it more ([Larson, Microsoft Research, 2005](https://microsoft.com/en-us/research/uploads/prod/2021/06/Larson-2005-the-science-of-word-recognition.pdf?lang=fr_ca)). Use caps for short labels and headings only, never paragraphs. **\[Research\]**
- Pick one system per level (sentence case for headlines, caps for labels, for example) and never mix within a level.
- UK English house style (Crea8Hub and Nigerian professional clients): sentence case headlines, single quotation marks, -ise spellings, dates as 9 November 2026.

### 4.9 Alignment of text

- **Flush left / ragged right** is the default for body text in left-to-right languages.
- Centred text: 1–3 lines only (titles, invitations, quotes).
- Justified text: only with hyphenation and good word-spacing control; never on narrow columns (rivers of white).
- Right-aligned text: for short captions or numbers in tables only.

### 4.10 Line breaks, widows and orphans

- Break display lines by meaning (“5 things I check / during a rent review”), not by width.
- No single word alone on the last line of a headline or short paragraph; no single line of a paragraph alone at the top or bottom of a column.
- Avoid ragged edges with strong steps (long-short-long); rebalance.
- Never break a name, a number and its unit (₦12 m), or a date across lines.

### 4.11 Typographic details that signal professionalism

- Curly quotes (‘ ’ “ ”) and apostrophes, not straight ones; primes (′ ″) only for feet and inches.
- En dash for ranges (₦12–18 m, 9–15 Nov); em dash or spaced en dash for breaks; hyphen only inside words.
- Proper multiplication sign (×), ellipsis (…), and non-breaking spaces between numbers and units.
- **Numerals:** tabular (fixed-width) figures in tables and prices; proportional figures in running text; old-style figures only in literary settings.
- Bold and italic for emphasis, never underline (reserved for links), never several at once.
- Text over images needs a scrim, overlay or solid panel to guarantee contrast (section 5.6).
