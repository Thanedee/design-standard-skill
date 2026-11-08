# 3. Composition, layout and grids

Build every layout on a grid and a spacing scale, keep critical content inside a safe area, and give the canvas one dominant composition. Numbers make these rules checkable.

### 3.1 Grids

| Grid type | Best for | Notes |
| --- | --- | --- |
| Manuscript (single column) | Long text, letters, reports | Wide margins, one measure |
| Column (2–12 columns) | Websites, magazines, flyers, social graphics | 12 columns divides into 2, 3, 4 and 6; 4 columns on phones |
| Modular (rows × columns) | Catalogues, dashboards, infographics, carousels | Cells hold images or text blocks |
| Hierarchical | Posters, landing pages | Zones sized by importance rather than equal modules |
| Baseline grid | Multi-column text | All text sits on a shared baseline (multiples of 4 or 8) |

**Rules:** every major element SHOULD snap to the grid; gutters MUST be consistent; break the grid only deliberately and only once per piece (a hero image bleeding off the edge, say). **\[Practice: Swiss tradition, Müller-Brockmann\]**

### 3.2 Spacing scale

- Use a base unit of **8 px** (4 px for fine adjustments): 4, 8, 12, 16, 24, 32, 48, 64, 96, 128. This is the system used by Google’s Material Design and most digital design systems. **\[Standard/Practice\]**
- Space inside a group < space between groups < space between sections. A useful default is 1 : 2 : 4 (e.g. 16 / 32 / 64 px).
- On a 1080 px social canvas, outer margins SHOULD be at least 64 px (about 6%); 80–108 px (7.5–10%) reads as more premium.

### 3.3 Safe areas and margins

- **MUST:** keep text, logos, faces and calls to action out of the outer 5% of any canvas, and out of platform overlay zones (section 11).
- For print, keep live content at least 3–5 mm inside the trim line (section 13).
- For video, title-safe is the central 80–90% of the frame; platform interface overlays take more (section 12).

### 3.4 Proportion and ratios

- Use a consistent ratio for sizes and spaces (1.25, 1.333, 1.5, 1.618 or 2). Consistency matters more than which ratio you pick.
- **The golden ratio is a tool, not a law.** Controlled experiments have not found a reliable preference for golden proportions; Friedenberg found attractiveness “did not peak at the golden ratio” and compactness mattered more ([i-Perception 3(3), 2012](https://pmc.ncbi.nlm.nih.gov/articles/PMC3485848)). Never justify a design by claiming it follows phi. **\[Research\]**
- **Rule of thirds:** place focal points near the intersections of a 3 × 3 grid for dynamic photo crops; centre composition suits symmetry, formality and single-subject product shots. **\[Practice\]**

### 3.5 Zones and reading paths

- Divide the canvas into zones with one job each: hook (headline), proof (image or data), detail (supporting copy), action (CTA or sign-off).
- **Z-pattern** suits sparse layouts (posters, ads): top-left → top-right → diagonal → bottom-right CTA. **F-pattern** governs text-heavy layouts (section 1.4).
- Text-heavy panel on one side and image on the other is a strong default for social graphics; alternate sides across a series for variety.

### 3.6 Precision rules

- **Tangencies (MUST avoid):** edges, text and subjects must either clearly overlap or clearly separate; near-touching reads as an error.
- **Cropping:** never crop at joints (wrists, ankles, knees, neck) or through the middle of a face or product; leave look-room in front of faces and moving subjects.
- **Optical alignment:** round letters (O, C), pointed shapes (triangles, play icons) and punctuation need to overhang edges slightly to look aligned; centre icons optically, not mathematically.
- **Optical sizing:** circles and triangles must be drawn slightly larger than squares to look the same size.
- **Hanging punctuation:** in display type, quotation marks and bullets sit outside the text edge so the letters align.
- **Edge discipline:** an element either sits clearly inside the margin or bleeds clearly off the canvas; never stop 2 mm short of an edge.
