# Co-Annotator — GitHub Pages site

Static project page for **Co-Annotator (ACM UIST 2026)**, in the same format and theme as the SwEYEpinch page (`style.css` and `script.js` are copied from it).

## Deploy

1. Create a GitHub repo (e.g. `co-annotator`) and push this folder to its root.
2. **Settings → Pages**: Source `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<user>.github.io/<repo>/`.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Assets

- `assets/Co-Annotator_UIST2026.pdf`: the arXiv version (2608.30352), CC BY 4.0, clean camera-ready text.
- `assets/interface_demo.mp4`: the hero loop, re-encoded from the talk's stage-2 interface clip (silent).
- `assets/co-annotator-30s.mp4`: the 30-second video.
- Figures are web-sized JPEGs of the paper's figures.

Numbers on the page come from the paper (main.tex contributions list, US2 and US3 results).
