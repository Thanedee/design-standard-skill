# 10. Accessibility and inclusive design

Meet WCAG 2.2 Level AA as the floor for everything digital: 4.5:1 text contrast, no meaning by colour alone, alt text on every informative image, captions on every video, no more than three flashes a second, and tap targets of at least 24 × 24 px. Accessible design is better design for everyone, including people reading a phone in Lagos sunlight.

### 10.1 WCAG 2.2 numbers designers must know

WCAG 2.2 became a W3C Recommendation on 5 October 2023 and added nine success criteria ([W3C, What’s new in WCAG 2.2](https://w3.org/WAI/standards-guidelines/wcag/new-in-22/)). **\[Standard\]**

| Criterion | Level | Requirement |
| --- | --- | --- |
| 1.4.3 Contrast (Minimum) | AA | Text 4.5:1; large text (24 px, or 18.5 px bold) 3:1 |
| 1.4.6 Contrast (Enhanced) | AAA | Text 7:1; large text 4.5:1 |
| 1.4.11 Non-text Contrast | AA | Icons, chart parts, input borders, focus indicators 3:1 |
| 1.4.1 Use of Colour | A | Colour is never the only way information is conveyed |
| 1.4.4 Resize Text | AA | Text can be enlarged to 200% without loss of content |
| 1.4.12 Text Spacing | AA | Layout survives line height 1.5×, paragraph spacing 2×, letter spacing 0.12×, word spacing 0.16× font size |
| 1.1.1 Non-text Content | A | Informative images have text alternatives |
| 1.2.2 / 1.2.4 Captions | A / AA | Pre-recorded and live video has captions |
| 2.2.2 Pause, Stop, Hide | A | Auto-moving content lasting over 5 s can be paused |
| 2.3.1 Three Flashes | A | Nothing flashes more than three times in any one second (above threshold) ([W3C](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html)) |
| 2.5.8 Target Size (Minimum) | AA | Pointer targets at least 24 × 24 CSS px, or spaced so a 24 px circle fits |
| 2.4.11 Focus Not Obscured | AA | Keyboard focus is never fully hidden |
| 2.4.13 Focus Appearance | AAA | Focus indicator at least a 2 px perimeter with 3:1 change in contrast |

### 10.2 Text alternatives (alt text)

- **Every informative image needs alt text (MUST)**, including social posts. LinkedIn supports alt text (“Alt text” under the image on desktop, “ALT” on mobile) and recommends under 120 characters; Instagram allows up to 1,000 ([summary of platform API docs](https://adaptlypost.com/blog/linkedin-alt-text-character-limit)).
- Describe purpose and content, not appearance only: “Graphic: Lagos land fees may have tripled. New property values took effect 1 May 2026; Lekki Phase 1 consent rose from ₦12–18m to ₦40–90m (reported).”
- When an image contains text, the alt text must include that text.
- Decorative images get empty alt text (alt="") on the web.
- Do not start with “Image of”; screen readers already announce images.

### 10.3 Colour-vision deficiency

- About 1 in 20 Nigerian men has a colour-vision deficiency (section 5.6). Never rely on red vs green, or colour alone, for status, charts or required fields.
- Simulate deuteranopia, protanopia and tritanopia (Figma, Photoshop proof setups, Stark, Coblis) before approval.

### 10.4 Motion and seizure safety

- No more than three flashes per second; avoid large red flashes completely.
- Respect reduced-motion settings on the web (prefers-reduced-motion); offer static alternatives.
- Avoid parallax and large zoom effects that trigger vestibular discomfort, or make them subtle.

### 10.5 Cognitive accessibility

- Plain language, short sentences, one idea per line or slide.
- Consistent placement of navigation, labels and calls to action.
- Avoid time pressure, fake countdowns and auto-advancing content without controls.
- Use icons plus words, not icons alone.

### 10.6 Inclusive representation

- Show the audience as it is: ages, skin tones, body types, abilities, genders, religions and family types.
- Avoid stereotypes in roles (who is the boss, who serves, who cleans).
- Use inclusive, respectful language and correct names and titles.
- Test designs with real users from the target audience where stakes are high.

### 10.7 Real-world conditions

- Design for bright sunlight, low-end Android screens, cracked screens and low brightness: favour higher contrast than the minimum.
- Design for slow data: compress images and videos (section 19), keep text live (not baked into images) on websites.
- Test on a real mid-range phone at normal brightness before approval.
