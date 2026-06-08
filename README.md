# Vital Signals Systems

The official website of **Vital Signals Systems LLC** — a biomedical technology company developing AI-powered software and hardware that analyze biomedical signals across brain, heart, sleep, movement, and respiratory systems.

**Live site:** [vitalsignalssystems.com](https://vitalsignalssystems.com)

---

## About the company

Vital Signals Systems develops technologies designed to support clinical decision-making, early risk detection, and accessible health communication for the communities they serve.

**Founders**
- Dr. Rim H. Chaif, Founder, Health AI Research
- Dr. Ali K. Ibrahim, Co-Founder, Biomedical Engineering

**Headquarters:** Boca Raton, Florida, United States

---

## Repository structure

This is a static website. All HTML, CSS, and JavaScript are contained in a single `index.html` file for simplicity and fast loading.

```
.
├── index.html         # Full website (HTML + inline CSS + inline JS)
├── README.md          # This file
├── .gitignore         # Files ignored by git
└── wrangler.jsonc     # Cloudflare Pages / Workers configuration
```

---

## Tech stack

- **HTML5** — semantic markup
- **CSS3** — custom design system with CSS variables, responsive grid, and CSS animations
- **Vanilla JavaScript** — scroll-triggered reveal animations using IntersectionObserver
- **Google Fonts** — IBM Plex Serif (headings) and Inter (body)
- **Cloudflare Pages** — hosting and global CDN

No build step, no framework, no dependencies. Open `index.html` in any browser to view locally.

---

## Brand

**Palette**
- Aubergine `#35134A` — primary brand color
- Plum `#5B247A` — accent
- Lavender `#EFE7F7` — soft section backgrounds
- Teal `#0F7C8C` — Health AI accent
- Rose `#E0446D` — Cardiac accent

**Typography**
- Headings: IBM Plex Serif
- Body & nav: Inter

**Brand line:** Signals · Intelligence · Impact

---

## Running locally

1. Clone the repository:
   ```bash
   git clone https://github.com/RimouchH/vitalsignals-site.git
   cd vitalsignals-site
   ```
2. Open `index.html` in any modern browser:
   ```bash
   open index.html   # macOS
   ```
   Or simply double-click the file.

No server or build step required.

---

## Deployment

The site deploys automatically to **Cloudflare Pages** whenever changes are pushed to the `main` branch.

To update the site:
1. Edit `index.html` (locally or directly on GitHub)
2. Commit and push to `main`
3. Cloudflare Pages rebuilds and deploys within 1–2 minutes
4. Hard refresh the live site to bypass cache: **Cmd+Shift+R** (Mac) or **Ctrl+Shift+R** (Windows)

---

## Contact

- **Partnerships and inquiries:** info@vitalsignalssystems.com
- **Careers:** careers@vitalsignalssystems.com

---

© 2026 Vital Signals Systems LLC. All rights reserved.
