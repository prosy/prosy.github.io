# Greg Prosl — Build Portfolio

A single-file [reveal.js](https://revealjs.com) slide deck of build/evidence assets, hosted on GitHub Pages. No build step — reveal.js loads from the jsDelivr CDN, so the whole thing is `index.html` + `/assets`.

## Structure
```
index.html                     # the deck (CDN reveal.js + inline charcoal/amber theme)
assets/
  deploy-log-1-cadence.png     # Production Deploy Log — week-by-week cadence
  deploy-log-2-breakdown.png   # Production Deploy Log — landings by market side
```

## Preview locally
Just open `index.html` in a browser (needs internet for the CDN):
```
open index.html
```
Or serve it (avoids any file:// quirks):
```
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Add a new asset
1. Drop the image in `assets/`.
2. Copy the commented "Pattern for a new asset section" block in `index.html`, point `src` at your image, write the kicker + headline + one-paragraph context (defensible, plain), and a caption with provenance.
3. Keep claims traceable — every number should survive an interview.

## Deploy to GitHub Pages
1. Create a public repo and push this folder to `main`.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.
3. Live in ~1 min at `https://<username>.github.io/<repo>/`
   (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

## Notes
- `hash: true` gives shareable per-slide URLs (e.g. `…/#/1/2`).
- Press **S** for speaker notes, **Esc** for slide overview, **?** for all shortcuts.
- Images are bitmaps; for the sharpest result on Retina/projectors, export source vizzes at 2× or as SVG when possible.
