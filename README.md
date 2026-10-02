# SaaS-Brand — BrandSuite Landing Page

A modern, single-file SaaS landing page for **BrandSuite** — "A New Vision for AI-Powered Productivity". A polished marketing site with dark mode, glassmorphism cards, and smooth scrolling sections, built entirely with HTML and the Tailwind CSS CDN. No build step, no dependencies to install — just open and ship.

## Features

- **Hero section** with a bold headline, product pitch, and call-to-action
- **Products section** showcasing the AI-powered product lineup
- **Roadmap section** — visual product roadmap timeline
- **Funding section** — investment / funding round information
- **Contact section** — contact form / contact details
- **Dark mode** — automatic theme switching based on OS preference, with localStorage persistence
- **Glassmorphism design** — frosted-glass cards, gradient text, and smooth scroll
- **Fully responsive** — mobile-first layout that adapts to tablet and desktop
- **Zero build step** — single `index.html`, styles via Tailwind CSS CDN

## Tech Stack

- **HTML5** — semantic, single-file page
- **Tailwind CSS (CDN)** — utility-first styling, dark-mode class strategy
- **Vanilla JavaScript** — theme toggle and localStorage persistence
- **Google Fonts** — Inter typeface

## Quick Start

No tooling required.

```bash
git clone https://github.com/girishlade111/SaaS-Brand.git
cd SaaS-Brand
# Option 1: just open it
open index.html            # macOS
start index.html           # Windows
xdg-open index.html        # Linux

# Option 2: serve locally (recommended for fonts/CDN caching)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project Structure

```
SaaS-Brand/
├── index.html   # The entire site: markup, styles, scripts
└── README.md
```

## Deploy

This is a static single-file site — deploy anywhere static hosting works:

- **GitHub Pages**: Settings → Pages → Deploy from branch (`main`, `/`)
- **Cloudflare Pages / Netlify / Vercel**: drag-and-drop the folder or connect the repo

## Credit

Built by **Girish Lade** — [ladestack.in](https://ladestack.in)
