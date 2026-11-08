# 14. UI, UX and web design essentials

Screens are used, not just viewed: design every component in all its states, make targets at least 44–48 px on touch screens, follow platform conventions, design mobile-first, and test with real users.

### 14.1 Nielsen’s 10 usability heuristics (1994)

The standard checklist for reviewing any interface ([The Decision Lab summary](https://thedecisionlab.com/reference-guide/design/nielsens-heuristics)): **\[Research/Practice\]**

1. Visibility of system status
2. Match between the system and the real world
3. User control and freedom
4. Consistency and standards
5. Error prevention
6. Recognition rather than recall
7. Flexibility and efficiency of use
8. Aesthetic and minimalist design
9. Help users recognise, diagnose and recover from errors
10. Help and documentation

### 14.2 Touch and click targets

| Standard | Minimum target |
| --- | --- |
| WCAG 2.2 SC 2.5.8 (AA) | 24 × 24 CSS px, or enough spacing |
| Apple Human Interface Guidelines | 44 × 44 pt |
| Google Material Design (Android) | 48 × 48 dp |

Use 44–48 px as the practical minimum on touch screens, with at least 8 px between adjacent targets. Place primary actions within thumb reach on phones (lower half of the screen). **\[Standard\]**

### 14.3 Component states (MUST design all)

Default, hover, focus (visible keyboard focus, section 10.1), active/pressed, disabled, loading, empty, error, success. Forms also need: placeholder vs label (labels always visible, never placeholder-only), helper text, validation messages next to the field.

### 14.4 Layout and responsiveness

- Mobile-first: design the smallest screen first, then expand.
- Common breakpoints: 360–480 px (phones), 768 px (tablets), 1024–1280 px (laptops), 1440 px+ (desktops).
- Columns: 4 on mobile, 8 on tablet, 12 on desktop; margins 16–24 px on mobile.
- Body text never below 16 px; line length 45–75 characters (section 4.5).
- Keep live text as HTML text, not images of text, for accessibility, search and translation.

### 14.5 Performance is design

- Pages should become usable quickly on mid-range Android phones and mobile data. Compress images (WebP/AVIF), lazy-load below-the-fold media, limit web fonts to 2–4 files.
- Google’s Core Web Vitals (loading, interactivity, visual stability) are the common benchmark; layout must not jump as images load (reserve image space).

### 14.6 Ethical interface design: no dark patterns (MUST NOT)

Harry Brignull’s catalogue of deceptive patterns ([Piwik PRO summary](https://piwik.pro/glossary/dark-patterns/)) lists practices that manipulate users and that regulators increasingly penalise: **\[Practice/Regulation\]**

- **Confirmshaming** (“No thanks, I don’t want to save money”).
- **Hidden costs** revealed only at checkout.
- **Roach motel / forced continuity:** easy to subscribe, hard to cancel.
- **Disguised ads** that look like content or navigation.
- **Bait and switch** and **misdirection.**
- **Privacy zuckering:** tricking people into sharing more data than intended.
- **Fake urgency or scarcity:** countdown timers that reset, “only 2 left” when untrue.

### 14.7 Research and testing

- Five users in a usability test typically reveal most major problems in one round; test iteratively.
- Use the five-second test for landing pages and posts, first-click tests for navigation, and A/B tests for live performance (section 18).
- Design systems (tokens for colour, type, spacing, radius, elevation, motion) keep products consistent and are the digital equivalent of a brand guideline.
