# 🖥️ Methru Bandara — Portfolio

[methrubandara.com](https://methrubandara.com/)

A single-page dark-themed portfolio website built with vanilla HTML, CSS, and JavaScript. Designed to showcase projects, skills, community involvement, and personality — all in one self-contained file.

## ✨ Features

- **Dark theme** with Fira Code monospace typography
- **Draggable Husky Card** — a Northeastern-style ID badge attached to an elastic lanyard with real-time Canvas physics (spring, gravity, damping)
- **Clickable photo gallery** — 10 personal photos in the hero section that cycle on click with smooth fade transitions
- **Scroll-triggered typewriter** — the JSON-formatted about section types itself out line by line as you scroll into view
- **Interactive project cards** — logos slide in on hover with smooth cubic-bezier transitions
- **Floating navigation dock** — macOS-style bottom dock with smooth scroll anchors
- **Community timeline** — organization logos with clickable links
- **Fully responsive** — optimized for mobile with the lanyard hidden and compact layouts

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid, animations) |
| Interactivity | Vanilla JavaScript |
| Physics | Canvas API (spring dynamics, quadratic bezier curves) |
| Scroll Effects | Intersection Observer API |
| Images | Base64-encoded (fully self-contained, no external assets) |
| Font | [Fira Code](https://fonts.google.com/specimen/Fira+Code) via Google Fonts |

## 🚀 Deploy

The entire site is a single `index.html` file with all images embedded as base64. No build step, no dependencies.

**Vercel:**
1. Push this repo to GitHub
2. Import on [vercel.com](https://vercel.com)
3. Deploy — done

**GitHub Pages:**
1. Name the repo `<username>.github.io`
2. Push `index.html` to `main`
3. Enable Pages in repo settings

## 📁 Structure

```
portfolio/
└── index.html    ← everything lives here
```

## 📸 Sections

- **Hero** — name, title, location, clickable photo gallery
- **About** — typewriter-animated JSON bio with links
- **Skills** — pill-style tags for languages, frameworks, and tools
- **Projects** — Spendvia, Travel Logic, Parlay GPT, RFID Attendance, Monopoly, Portfolio
- **Interests** — sports, hobbies, favorites
- **Community** — SLSA, NEBVMC, Hudson Food Pantry, SL Lions Cricket
- **Contact** — email, GitHub, LinkedIn, Instagram, X

## 👤 About Me

Computer Science and Environmental & Sustainability Sciences student at Northeastern University (Class of 2028). Co-Founder & Technical Lead at [Spendvia](https://spendvia.ai). Previously Web Developer at [Fluorolite Plastics](https://fluorolite.com). Based in Boston, MA.

Available May – December 2026 for co-ops and new opportunities.

---

Built by Methru Bandara
