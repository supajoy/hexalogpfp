# hexalog pfp

internal tool — drop a photo into a hexalog frame and export a 1000×1000 png for social.

## use

open the deployed url, choose an image (or paste a copied one with ⌘V, or double-tap the canvas), drag to reposition, scroll or use the slider to zoom, pick a frame style, then download.

## frame styles

- **badge / soft / white** — full violet rings with the cube mark
- **tag / tag · y / tag · w** — `#HEXANAUT` ribbons (violet, yellow, white)

## run locally

```sh
git clone git@github.com:supajoy/hexalogpfp.git
cd hexalogpfp
python3 -m http.server 8777
# open http://localhost:8777
```

no build step — it's a single static html file.

## deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/supajoy/hexalogpfp)

## files

- `index.html` — single-file app (vanilla html/css/js)
- `frames/` — the six overlay pngs (1000×1000, transparent center, drawn over the circular photo)
- `placeholder.png` — default avatar shown until a photo is added
