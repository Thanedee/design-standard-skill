# 12. Motion and video design

Assume the video is watched on a phone with the sound off: hook in the first 1–2 seconds, burn in accurate captions, keep text inside the safe zone and on screen long enough to read, and use motion only to direct attention.

### 12.1 Why captions and visual storytelling come first

In a Verizon Media and Publicis survey of 5,616 US adults (2019), **69%** watched video with the sound off in public, and **80%** of caption users were not deaf or hard of hearing ([Streaming Media](https://www.streamingmedia.com/Articles/News/Online-Video-News/80-of-Video-Caption-Users-Arent-Hearing-Impaired-Finds-Verizon-131860.aspx)). **\[Research, industry survey\]** Captions are therefore required for reach, not only for accessibility (WCAG 1.2.2).

### 12.2 Structure of short-form video (Reels, TikTok, Shorts, Status)

1. **Hook (0–2 s):** the first frame alone must communicate the subject (a striking visual, a bold on-screen line, a question). Never open on a logo or a slow fade.
2. **Promise (2–5 s):** what the viewer will get.
3. **Payoff (body):** one idea per shot; change shot every 1.5–4 s for pace, slower for premium or emotional content.
4. **Close:** the takeaway and one call to action, held for at least 2 s.
5. **Cover frame:** design a separate thumbnail/cover that reads as a static post.

### 12.3 On-screen text

- Reading time: hold text at least **0.3 s per word plus 1 s** (a 6-word line needs about 3 s). Never flash text faster than it can be read.
- Maximum about 7 words per line, 2 lines per caption block.
- Captions: high-contrast (white with dark outline or box), sentence case, 48–64 px on a 1080 × 1920 frame, inside the safe zone (section 11.2).
- **MUST** proofread captions: auto-captions mishear names, numbers and Nigerian terms (Lekki, Ikoyi, ₦ amounts, Yoruba words).

### 12.4 Motion principles

Disney’s 12 principles of animation, adapted to interfaces, remain the basis of motion craft: squash and stretch, anticipation, staging, straight-ahead vs pose-to-pose, follow-through, slow in and slow out (easing), arcs, secondary action, timing, exaggeration, solid drawing and appeal ([UI/UX Atlas summary](https://uiux-atlas.pages.dev/lessons/motion/the-12-principles-of-animation-adapted-to-ui)). **\[Practice\]**

| Motion | Typical duration | Easing |
| --- | --- | --- |
| Small UI elements (chips, toggles) | 100–150 ms | ease-out entering |
| Mid-size (menus, cards) | 150–250 ms | ease-out / ease-in-out |
| Full-screen transitions | 250–400 ms | ease-in-out, e.g. cubic-bezier(0.4, 0, 0.2, 1) |
| Staggered list items | 30–60 ms between items | — |
| Text reveal in social video | 300–600 ms per element | ease-out |
| Logo sting / brand reveal | 1–3 s total | brand-defined |

- **Staging:** animate one thing at a time; motion is the strongest attention cue, so everything that moves competes.
- Elements that belong together move together (common fate, section 1.3).
- Enter with ease-out, exit with ease-in; never linear except for continuous loops.
- Consistent direction: if slides advance left, transitions always move left.

### 12.5 Video technical standards

| Item | Standard |
| --- | --- |
| Vertical social | 1080 × 1920, 9:16, 30 fps (25 fps acceptable), H.264 or H.265, AAC audio |
| Landscape | 1920 × 1080 or 3840 × 2160, 16:9 |
| Bitrate (1080p H.264) | 8–12 Mbps for upload masters; platforms re-compress |
| Audio loudness | About –14 LUFS integrated for social and streaming; peaks below –1 dBTP |
| Title-safe (broadcast) | Central 90% (action-safe) and 80% (title-safe) |
| Frame rate | Do not mix frame rates in one edit; 24 fps for cinematic, 30 for social, 60 for fast motion |

### 12.6 Audio

- Use only licensed music: platform libraries, royalty-free libraries with commercial licences, or commissioned tracks. Trending sounds on personal accounts are often not cleared for brand or ad use (section 16).
- Voice clarity first: music ducked 12–20 dB under speech.
- Subtitle any speech; describe important sound effects in captions where meaningful.

### 12.7 Seizure and comfort safety

No more than three flashes per second (WCAG 2.3.1); avoid strobe and rapid red flashes; keep camera shake and zooms gentle (section 10.4).
