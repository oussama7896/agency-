# Studio

A San Francisco marketing agency landing page. Neubrutalist style, single self-contained HTML file, no build step.

## Stack

- One file: `index.html` (HTML + inline CSS + vanilla JS)
- Google Fonts: Lexend Mega (display), Public Sans (body)
- No frameworks, no build, no dependencies

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

It's a single static file. Drop it anywhere:

- **GitHub Pages**: enable in repo settings, point to root
- **Netlify**: drag the folder onto netlify.com/drop
- **Vercel**: `vercel` in this folder
- **Cloudflare Pages**: connect this repo

## Sections

Hero, marquee, services, process (5-step), local (SF neighborhoods + office), reviews (Trustpilot / Google / LinkedIn), about (team), CTA, footer.

## Palette

- `--bg`        `#FDF2F8`  cream pink
- `--paper`     `#FEFAF6`  warm off-white
- `--ink`       `#1a0a14`  near-black, tinted magenta
- `--pink`      `#EC4899`  hot pink accent
- `--cyan`      `#06B6D4`  cyan accent
- `--yellow`    `#FACC15`  yellow accent
