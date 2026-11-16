# Bellini · Faux Fur Como Snug Kids Chair — personalization prototype

Interactive, responsive product page prototype (desktop and mobile layouts in one page).

## Run locally
The page loads its own source at startup, so it must be served over HTTP (opening `index.html` directly from disk won't work):

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish with GitHub Pages
Push this folder to a repository, then in **Settings → Pages** choose "Deploy from a branch", select the branch and the root folder.

## Contents
- `index.html` — the prototype
- `support.js` — the page runtime
- `vendor/` — React 18.3.1 (bundled so the page has no CDN dependency)
- `assets/` — product photos, icons, logo and the Monogram Serif / Cursivo fonts

Inter and the other lettering fonts load from Google Fonts.
