# Little Bird Sitter Kit — website

Landing page for the **Little Bird Sitter Kit**, a 6-page printable PDF that helps bird owners hand over care instructions to a sitter.

Live site: <https://ponkrit12.github.io/little-bird-sitter-kit/>

## Structure

```
index.html               Single-page landing site
404.html                 Not-found page
assets/
  css/styles.css         Styles (design tokens at the top)
  js/main.js             Nav, scroll reveal, FAQ accordion
  img/
    kit-cover-preview.jpg    Hero preview (from the listing poster)
    kit-pages-preview.jpg    All-six-pages preview
    og-image.jpg             Social share image
    favicon.svg              Bird favicon
    pages/page-01..06.jpg    Per-page thumbnails for the "What's Inside" cards
robots.txt
.nojekyll                Keeps GitHub Pages from running Jekyll
```

## Editing

- **Store link** — the Payhip URL appears in a few places in `index.html`
  (header, hero, FAQ, final CTA, footer, and the JSON-LD block). Search for
  `payhip.com` and replace if the listing moves.
- **Colours / type** — all design tokens live in `:root` at the top of
  `assets/css/styles.css`.

## Deploy

Static site — no build step. Pushing to `main` is all that's needed once
GitHub Pages is enabled for this repository (branch `main`, folder `/`).

## Notes

- The source PDFs are intentionally **not** part of this repository
  (see `.gitignore`); they are the paid product.
- Copy on the page states: personal use only, not veterinary advice.
