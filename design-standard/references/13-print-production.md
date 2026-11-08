# 13. Print production

A print file is ready only when it has 3 mm bleed, text at least 3–5 mm inside trim, images at 300 ppi at final size, CMYK colour within the press’s ink limit, fonts embedded, and a signed-off proof. Screen-perfect designs routinely fail at the press on these points.

### 13.1 Core specifications

| Parameter | Standard |
| --- | --- |
| Bleed | 3 mm on every edge (some US printers use 0.125 in / 3.175 mm; large format may need 5–10 mm) |
| Safe zone | Text and key elements at least 3 mm inside trim; 5 mm is safer; booklets need more on the spine side |
| Resolution | 300 ppi at final size for close viewing; 200–300 ppi for posters; 100–150 ppi large format; 25–72 ppi billboards |
| Total ink coverage | 300% coated paper, 280% uncoated, 240% newsprint (confirm with the printer) |
| Rich black (large areas) | C60 M40 Y40 K100 |
| Text black | 100% K only (no rich black on small text, it misregisters) |
| Hairlines | At least 0.25 pt (0.1 mm); reversed (white) text at least 8–9 pt, preferably bold |

Values from a print file-prep reference ([CMYK print guide](https://xcreativedesign.github.io/cmyk-simulator/guide/print-file-prep.html)); always confirm with the specific printer. **\[Standard/Practice\]**

### 13.2 Colour for print

- Work in CMYK with the printer’s profile (e.g. FOGRA39/FOGRA51 coated, FOGRA52 uncoated in Europe; GRACoL/SWOP in the US; ask Nigerian printers which profile their press uses).
- Soft-proof RGB artwork before converting; bright RGB greens, blues and oranges shift.
- Specify **Pantone (spot) colours** for logos and brand colours that must match exactly, and give the CMYK build for four-colour jobs.
- Paper changes colour: uncoated stock prints darker and duller; show clients printed samples on the real stock.
- Metallics (gold, silver), foils, embossing and spot UV need separate spot-colour layers set to overprint, as the printer specifies.

### 13.3 File formats

- **PDF/X-4** is the modern default: supports live transparency, layers and colour-managed workflows, and moves easily between offset and digital presses. **PDF/X-1a** flattens everything to CMYK and is still requested by some older workflows ([PDF Association](https://www.pdfa.org/whats-the-difference-between-pdf-x-1a-and-pdf-x-4/)). **\[Standard: ISO 15930\]**
- Embed or outline all fonts; include crop marks and bleed in the export.
- Keep native files (InDesign, Illustrator, Affinity, Figma) and linked images packaged for reprints.

### 13.4 Paper and finishing

| Item | Typical choices |
| --- | --- |
| Flyers | 130–170 gsm silk or gloss |
| Business cards | 350–450 gsm, matt laminate or uncoated premium |
| Posters | 150–200 gsm, or 120 gsm blueback for outdoor |
| Brochures and booklets | 130–170 gsm inners, 250–350 gsm covers; page count in multiples of 4 |
| Invitations (e.g. weddings) | 300–400 gsm textured or pearlescent; foil and emboss for premium |
| Outdoor (banners, signage) | PVC flex, mesh, vinyl; design at 1:10 scale at higher ppi if the printer allows |

### 13.5 Proofing (MUST)

1. Digital proof checked against the preflight list in section 20.
2. Hard-copy proof for colour-critical work, on the real stock.
3. Written client sign-off on text, numbers and dates before production.
4. Check imposition, folds and binding (fold lines away from text; creep in thick booklets).

### 13.6 Large format and environmental graphics

- Legibility at distance: about 2.5 cm of cap height per 7–10 m of viewing distance (section 4.3).
- Signage needs high contrast, simple sans-serif type, and icons recognisable at a glance.
- Allow for hems, eyelets and pole pockets in banner artwork; keep text away from them.
