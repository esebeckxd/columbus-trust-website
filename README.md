# Columbus Trust — Website

Marketing website for **Columbus Trust GmbH** (Munich) — strategic partnership and transaction advisory for the financial services sector since 1999.

## Stack

Static HTML, CSS, and a handful of vanilla JS lines. No build step.

- `index.html` — German (default)
- `en.html` — English
- `impressum.html`, `datenschutz.html` — legal pages
- `styles.css` — design system (palette, typography, layout)
- `assets/` — logo and other media

## Local preview

```bash
python3 -m http.server 8765
# → http://127.0.0.1:8765/
```

## Deployment

Deployed on Vercel as a static site (no framework). Pushes to `main` deploy to production; PRs get preview URLs automatically.
