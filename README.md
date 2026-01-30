# FUCK YOU

**A single-purpose page: loud, blunt, and unapologetic — FUCK YOU.**

This is a minimal static one‑pager where the headline is the whole point. A literal, aggressive typographic poster with glitch/noise vibes, built for moments when you want to shout a stance and move on.

## Highlights
- Oversized, in‑your‑face **FUCK YOU** as the core message
- Pure static files, zero dependencies, instant load
- Nginx image ready to deploy
- Extreme, abrasive visual style with max attitude

## Quick Start
### Option 1: Run with Docker
```bash
# Build image
Docker build -t fuck-you-page .

# Run container
Docker run --rm -p 8080:80 fuck-you-page
```
Then open: `http://localhost:8080`

### Option 2: Open locally
```bash
open site/index.html
```
Or deploy `site/` to any static host.

## Structure
```
.
├── Dockerfile
├── README.md
└── site
    ├── index.html
    └── styles.css
```

## Customize
- Copy: edit `site/index.html`
- Colors/animations: edit `site/styles.css`

Want a different message instead of “FUCK YOU”? Swap it and ship.

## Disclaimer
This project contains strong profanity and aggressive content. Use it appropriately.
