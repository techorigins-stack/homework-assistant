# Homework Assistant

A static marketing landing page for **Homework Assistant**, hosted on GitHub Pages.

Dark, editorial single-page site: fixed navbar, full-height hero, stats bar with an
animated count-up, a 12-column feature grid, a full-bleed CTA, and a footer.
Built with plain HTML, CSS, and a small vanilla-JS file for scroll reveals — no build step.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | Page markup |
| `styles.css` | All styling (dark theme, responsive) |
| `script.js` | Scroll-reveal animations + stat count-up |
| `media/favicon.svg` | Favicon |

## Run locally

Any static server works, e.g.:

```bash
npx serve .
# or
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Deploy

Served as-is by GitHub Pages from the default branch root.
Settings → Pages → Source: *Deploy from a branch* → `main` / `root`.
