# Bellini · Chair as a bundle add-on — prototype

Interactive prototype of adding the Faux Fur Como Snug Kids Chair to a Vienna Collection bundle.
`index.html` shows the desktop popup on screens 768 px and wider, and the mobile bottom-sheet drawer on narrower screens, switching as the window is resized.

## Run locally
The pages load their own source at startup, so they must be served over HTTP (opening the files directly from disk won't work):

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish with GitHub Pages
Push this folder to a repository, then in **Settings → Pages** choose "Deploy from a branch", select the branch and the root folder.

## Contents
- `index.html` — picks the desktop or mobile version by screen width
- `desktop.html` — bundle page with the chair popup
- `mobile.html` — bundle page with the chair drawer
- `support.js` — the page runtime
- `vendor/` — React 18.3.1 (bundled so the pages have no CDN dependency)
- `assets/` — product photos, bundle images, icons, logo and the Monogram Serif / Cursivo fonts

Inter and the other lettering fonts load from Google Fonts.
