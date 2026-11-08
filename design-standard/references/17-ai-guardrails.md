# 17. AI-generated design: guardrails

Treat every AI image as a fast junior designer’s draft: brief it precisely, change one thing at a time, assume it has invented something, and verify every word, number, logo and face before it ships. The person who publishes is accountable, not the model.

### 17.1 What AI should and should not do

| Use AI for | Do not use AI (alone) for |
| --- | --- |
| Photographic scenes, backgrounds, textures, mood boards, concept options | Final logos and trademarks (not ownable, see 16.2) |
| Illustrations and visual metaphors | Charts and data graphics (values get invented; build them from data) |
| Layout explorations and variations | Legal, financial or medical documents and certificates |
| Retouching and extending your own photos (with care) | Images of real, identifiable people without consent |
| Short display headlines when checked | Long text, small print, tables, prices you cannot verify letter by letter |
| Generating options to choose from | Property, product or “before and after” images presented as real |

### 17.2 The prompt brief (use for every generation)

OpenAI’s own guidance recommends ordering prompts as scene, subject, details, then constraints; putting literal text in quotes; spelling unusual words letter by letter; and stating exclusions and invariants explicitly ([OpenAI image prompting guide](https://developers.openai.com/cookbook/examples/multimodal/image-gen-models-prompting-guide.md)). **\[Standard/vendor\]** Use this template:

```markdown
PURPOSE: LinkedIn feed post for [brand], audience [who], goal [one message]
FORMAT: 1080 x 1350 px (4:5), sRGB
LAYOUT: [e.g. navy panel left 50%, photo right 50%; margins 64 px]
PALETTE: dominant #14213D, background #F7F3EE, accent #F25C54 (accent only on label and icons)
TYPE: bold geometric sans headline, regular sans body; sentence case; no more than 2 weights
TEXT (exact, nothing else):
  Label: "LAGOS LAND FEES"
  Headline: "Your land fees may have tripled."
  Lines: "..." / "..." / "..."
  Footnote: "..."
IMAGE: [subject, setting, light, camera angle, local details]
CONSTRAINTS: no logos, no coats of arms or seals, no watermarks, no faces, no extra text or numbers, no invented facts
CHECK: every word spelt exactly as given; all text inside a 64 px margin
```

### 17.3 Editing and iteration discipline

- **Change one thing per request** and say “change only X; keep layout, photo, colours, fonts, sizes and all other text exactly the same”. Repeat the preserve list every time; models drift.
- **Say what is approved** (“slide 3 is approved; do not regenerate it”) to stop silent re-generation.
- **Series:** generate one master, approve it, then ask for the others “in exactly the same layout, type sizes and margins as the approved image”. If one drifts, either fix it back or move the whole series to the new layout so all match.
- **When an edit changes facts or layout you did not ask for, reject it** and resend the exact text; never accept “close enough”.

### 17.4 Text in AI images

- An industry benchmark of 26 image models found that the best now render required text exactly, but weaker models drop words, add stray characters and invent punctuation; it recommends treating rendered text as a draft and keeping headlines as editable text layers where possible ([IMG.LY benchmark](https://img.ly/ai-benchmarks/findings/text-reliability/)). **\[Research, vendor benchmark\]**
- **Preferred workflow:** generate the image without text, then set the type in a design tool (Figma, Canva, Photoshop, Affinity) or as HTML/SVG. Text is then exact, editable, on-brand and translatable.
- **If text must be generated:** keep it short; quote it exactly; specify font style, size and position; zoom to 200% and check every character, especially digits, currency symbols (₦), apostrophes, dashes and tone-marked letters.
- **Small fixes:** correct a single malformed glyph by hand (clone a correct character from the same image) rather than regenerating and risking new errors.

### 17.5 Known failure modes and checks

| Failure | Example | Check |
| --- | --- | --- |
| Invented facts or numbers | Edit replaced “new property values took effect 1 May 2026” with made-up ground-rent figures | Compare every line against the approved copy |
| Malformed characters | “1” drawn as a reversed glyph; ₦ missing its bars | Zoom 200% on digits and symbols |
| Phantom emblems | Coat of arms, seals, crests, watermarks, fake app logos appear on documents and phones | Search the image for any mark you did not ask for |
| Layout drift | One carousel slide switches from angled panel to soft fade | Compare side by side with the master |
| Extra or missing text | A label repeated, a footnote dropped | Count text elements against the brief |
| Local inaccuracy | Western houses for a Lagos estate; wrong currency; wrong professional term | Check against the audience’s real context (section 15) |
| Identity change | Headshot “improvement” alters the person’s face | Side-by-side with the original; the person approves |
| Anatomy and physics | Extra fingers, warped hands, impossible reflections, melted text on signs | Inspect hands, faces, edges and backgrounds |
| Style imitation | Output resembles a known artist, character or brand | Reject and re-prompt without references to them |
| Misleading realism | A “photo” of a property that does not exist used to sell it | Never present AI scenes as the real asset |

### 17.6 Verification protocol (MUST, before anything AI-made is published)

1. **Text audit:** every word, number and symbol matches the approved copy, letter by letter.
2. **Fact audit:** no claim, figure, date or name that is not in the brief.
3. **Mark audit:** no logos, seals, crests, watermarks, signatures or brand names that were not supplied.
4. **Consistency audit:** matches the approved master and the rest of the series.
5. **Guide audit:** passes section 20 (hierarchy, safe areas, contrast, type sizes).
6. **People audit:** no identifiable real person without consent; faces unchanged where they must be.
7. **Rights audit:** no imitation of protected styles, characters or brands.
8. **Disclosure audit:** labels and provenance in place where required (17.7).
9. **Second pair of eyes:** a human or separate AI review that has not seen the generation process.

### 17.7 Disclosure and provenance

- **Content Credentials (C2PA):** many AI tools embed provenance metadata; platforms such as LinkedIn read it and show a “CR” content-credentials label on AI-generated or AI-edited images. Do not strip this metadata to hide AI use.
- **EU AI Act Article 50** (applies from 2 August 2026): providers must mark AI outputs in machine-readable form; deployers must disclose deepfakes and AI-generated text published to inform the public, clearly and at first exposure; artistic and creative works get a lighter disclosure ([AI Act guide](https://artificialintelligenceact.eu/transparency-rules-article-50/)). **\[Law/EU\]** Relevant whenever content reaches EU audiences.
- **Advertising:** realistic AI depictions of people, results or properties in adverts need clear disclosure and, in Nigeria, ARCON approval like any other advert (section 16.4).
- **House rule:** disclose AI use whenever a reasonable viewer would care, especially for realistic people, places and products.

### 17.8 Choosing the tool

- **Image models (ChatGPT image generation, Google Gemini/Imagen, Midjourney, Flux, Ideogram, Firefly):** best for photographic scenes and illustration; text quality varies by model and version, so always verify.
- **Layout-in-code (Claude and other assistants writing HTML, SVG or design-tool scripts):** exact text, exact brand colours and fonts, precise grids, easy edits; weaker at photographic realism. Combine: AI image for the photo, coded or design-tool layout for the type.
- **Design tools with AI (Canva, Adobe Express/Firefly, Figma):** good for templated series with brand kits and editable text.
- Prefer tools whose licence permits commercial use and that attach Content Credentials.

### 17.9 Standing instruction for AI design assistants

```markdown
You are producing a design under the Complete Design Guide. Before generating:
restate the objective, audience, format and exact text. Use only the text supplied,
spelt exactly. Invent no facts, figures, names, logos, seals, coats of arms,
watermarks or brand marks. Keep all text inside the safe area and at or above the
minimum sizes in section 4.3. Use the specified palette with 4.5:1 text contrast.
When editing, change only what is requested and preserve everything else. After
generating, run the section 17.6 verification protocol and report any line that
does not match the brief instead of presenting the image as final.
```
