# 7. Information design and data visualisation

Pick the chart that encodes the key comparison as position or length, start bars at zero, label directly, state the takeaway as the headline, and cite the source on the graphic.

### 7.1 How accurately people read visual encodings

Cleveland and McGill ranked encodings by how much error people make reading them ([Journal of the American Statistical Association 79, 1984](https://info3312.infosci.cornell.edu/ae/graphical-perception.html)). **\[Research\]** From most to least accurate:

1. Position on a common scale (dot plots, aligned bars)
2. Position on non-aligned scales (small multiples)
3. Length, direction, angle
4. Area
5. Volume, curvature
6. Shading and colour saturation

Consequence: bar and dot charts beat pie charts, bubbles and 3D charts whenever precise comparison matters.

### 7.2 Choosing the chart

| Message | Best chart | Avoid |
| --- | --- | --- |
| Compare amounts across items | Horizontal bar chart, sorted | 3D bars, pie with many slices |
| Change over time | Line chart (bars for few periods) | Pies, unevenly spaced dates |
| Parts of a whole | Stacked bar or 100% bar; pie or donut only for 2–4 slices | Pies with 6+ slices, 3D pies |
| Before vs after for many items | Slope chart or dumbbell (dot range) | Two separate pies |
| A range (e.g. ₦12–18 m to ₦40–90 m) | Range bars or dumbbells showing low–high | Single midpoint presented as exact |
| Distribution | Histogram, box or strip plot | Average alone |
| Relationship between two measures | Scatter plot | Dual-axis line charts |
| Contribution to a change | Waterfall | Stacked bars |
| Location | Choropleth or dot map, normalised per capita | Raw totals on area maps |
| A single striking number | Big number with context (“up 3× since May 2026”) | A chart with one bar |

### 7.3 Honesty rules (MUST)

- **Bar charts start at zero.** Truncated axes inflate perceived differences, and Correll et al. found visual warnings such as broken axes do not reliably correct the impression ([Truncating the Y-Axis: Threat or Menace?, 2020](https://arxiv.org/pdf/1907.02035)). Line charts may use a non-zero baseline when the meaningful change is small relative to the level, but say so. **\[Research\]**
- Area and icons must scale by area, not by height (doubling an icon’s height quadruples its area).
- Same units and same scale when charts are compared side by side.
- Show ranges and uncertainty where the data has them; label estimates as estimates (“reported figures”).
- Never cherry-pick start and end dates to manufacture a trend.
- Cite the data source and date on the graphic itself.

### 7.4 Clarity rules

- **Headline states the takeaway** (“Lekki consent fees roughly tripled”), not the topic (“Consent fees 2025–2026”).
- Label data directly instead of using legends wherever possible.
- Remove gridlines, borders, shadows and backgrounds that carry no data (Tufte’s data-ink principle), but see 7.5.
- Highlight the one series or bar that matters in the accent colour; grey the rest.
- Sort bars by value unless order has meaning (time, age bands).
- Round numbers to the precision the reader needs (₦40 m, not ₦40,183,229).
- Use colour-blind-safe palettes and redundant encoding (labels, patterns).

### 7.5 Embellishment: when “chartjunk” helps

Bateman et al. found illustrated charts were read as accurately as plain ones and were remembered significantly better two to three weeks later ([CHI 2010, “Useful junk?”](https://webspace.science.uu.nl/~telea001/uploads/VACourse/Baterman10.pdf)). **\[Research\]** Rule: for social and marketing graphics, a relevant illustration that reinforces the message MAY be added; for analytical or decision-making charts, keep it minimal. Embellishment must never distort the data.

### 7.6 Infographics

- One story per infographic; 3–5 key points; a clear reading path (top to bottom or numbered).
- Use progressive disclosure: split across carousel slides rather than cramming.
- Icons and illustrations from one family (section 6.6).
- Every number sourced; every chart honest (7.3).
