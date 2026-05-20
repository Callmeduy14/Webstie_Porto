# Yudi — Personal Portfolio

Personal portfolio website built from scratch with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies.

**Live:** [GANTI-URL-KAMU.netlify.app](https://GANTI-URL-KAMU.netlify.app)

---

## Features

- Amber / warm color scheme with automatic dark mode (`prefers-color-scheme`)
- Custom animated cursor with magnetic buttons
- Hero with text scramble animation and "now building" indicator
- Marquee skill ticker
- Horizontal drag-to-scroll project cards with 3D tilt
- Experience timeline
- Scroll-triggered reveal animations and section line draws
- Copy-to-clipboard email with toast notification
- Floating scroll-to-top button
- Splash screen on first visit
- Download CV button
- Language badges (ID · DE · EN)
- Scroll progress bar
- Responsive — mobile friendly
- SEO ready: Open Graph, Twitter Card, JSON-LD structured data, sitemap, robots.txt

## Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, `color-mix`, `prefers-color-scheme`) |
| Logic | Vanilla JavaScript (IntersectionObserver, Web Animations) |
| Fonts | Space Grotesk + Inter (Google Fonts) |
| Hosting | Netlify |

## Project Structure

```
WebsitePorto/
├── index.html          — entire site (single file)
├── FOTO.png            — profile photo
├── YudiLebenslauf .pdf — CV download
├── sitemap.xml         — for Google indexing
├── robots.txt          — crawler config
└── .gitignore
```

## Local Development

No build step needed. Just open the file:

```bash
open index.html
```

## Deployment

Connected to Netlify via GitHub. Every push to `main` triggers an automatic deploy.

To update the live URL after deploying, find and replace `GANTI-URL-KAMU` in:
- `index.html` (4 places)
- `robots.txt` (1 place)
- `sitemap.xml` (1 place)

## License

© 2025 Yudi. All rights reserved.
