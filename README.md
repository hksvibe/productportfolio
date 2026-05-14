# Harsh Kumar Sharma — Portfolio Website

**Live site:** [harshkumarsharma.in](https://harshkumarsharma.in)

Personal portfolio of Harsh Kumar Sharma — AI-first Product Leader with 11+ years across BFSI, Fintech & SaaS. Built as a single-file HTML portfolio with all CSS and JS inline.

---

## What's Inside

| Section | Description |
|---|---|
| **Hero** | Name, title, impact bar (GMV, AUM, GMV metrics) |
| **About** | Bio, resume download, LinkedIn link |
| **Experience** | Full career timeline — Kotak Securities, Safexpay, Increff, MedTrail, BookYourGame, Midnight Breakfast |
| **Products** | Six product cards — Neome, Stockcase, Aasaan, Marketplace Dashboard, Pocket Pulse, MedTrail |
| **Writing** | Auto-scrolling carousel of 5 Medium articles |
| **Testimonials** | 4-card carousel — Avijeet Alagathi, Devi Prasad Biswal, Pranali Salunkhe, Rajesh Kurkute |
| **Skills** | Horizontal scrollable skill cards across 6 competency areas |
| **Patent** | Engineering patent certificate |
| **Education** | G.H. Raisoni College of Engineering |
| **Contact** | Formspree-powered contact form with email + mobile validation |

---

## Files

```
/
├── index.html        ← Entire portfolio (HTML + CSS + JS, single file)
├── bg-music.mp3      ← Ambient background music (auto-plays on first interaction)
└── README.md         ← This file
```

> **Note:** `bg-music.mp3` must be in the same directory as `index.html` for the ambient player to work on the live site.

---

## Tech Stack

- **Pure HTML/CSS/JS** — no frameworks, no build step, no dependencies
- **Fonts:** Inter (body), Sora (headings), JetBrains Mono (code/labels) via Google Fonts
- **Form backend:** [Formspree](https://formspree.io) (`/f/xvzdywlw`)
- **Hosted on:** GitHub Pages with custom domain via GoDaddy

---

## Key Features

- **Dark theme** with indigo/purple gradient accents
- **Scroll reveal animations** on all sections
- **Ticker bar** with AI & product keywords
- **Writing carousel** — CSS `@keyframes` marquee, pauses on hover
- **Testimonials carousel** — IntersectionObserver dwell timer (4.5s before auto-advance)
- **Skills horizontal scroll** — swipe hint on mobile
- **Ambient music player** — floating pill UI, auto-plays on first page interaction, loops
- **Contact form** — Formspree POST with email regex + mobile number validation
- **Fully responsive** — mobile-optimised layout at 768px and 480px breakpoints

---

## Updating Content

Since everything lives in `index.html`, all edits are made directly to that file.

**To update the resume link** — search for `drive.google.com/file` and replace both occurrences.

**To add a new writing card** — duplicate a `.wcard` block inside `#writing-track` and update the `href`, cover SVG, title, and description.

**To update experience bullets** — find the relevant `.timeline-item` block and edit the `<li class="timeline-bullet">` lines.

**To change contact form endpoint** — search for `formspree.io/f/` and replace the form ID.

---

## Deployment (GitHub Pages)

1. Push `index.html` and `bg-music.mp3` to the `main` branch root
2. Go to **Settings → Pages → Source → Deploy from branch → main / root**
3. For a custom domain, add a `CNAME` file containing your domain (e.g. `harshkumarsharma.in`)
4. In GoDaddy DNS, add two `CNAME` records pointing to `hksrise.github.io`

---

## Contact

- **Email:** hksharma.product@gmail.com
- **LinkedIn:** [linkedin.com/in/hksrise](https://linkedin.com/in/hksrise)
- **Medium:** [medium.com/@hksrise](https://medium.com/@hksrise)
