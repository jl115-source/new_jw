# Joseph Lockwood — Personal Website

A lightweight static personal website focused on weather, energy, quantitative research, and public open-source work.

## Design

The visual direction is intentionally restrained and editorial: large serif typography, uppercase navigation, generous whitespace, a single atmospheric hero graphic, and text-led sections. The site is built from plain HTML, CSS, and a tiny amount of JavaScript — no build step or framework required.

## Files

- `index.html` — site structure and content
- `styles.css` — layout, typography, responsive styles
- `script.js` — mobile navigation and footer year

## Preview locally

Open `index.html` directly in a browser, or run a small static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

In the repository on GitHub:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Save.

GitHub will provide the public Pages URL after deployment.

For a cleaner personal URL, rename or move the site to a repository named `jl115-source.github.io`; GitHub Pages will then use `https://jl115-source.github.io/`.

## Content notes

Public professional descriptions are intentionally broad. Proprietary forecasting, trading, and employer-specific methods should remain out of this repository.
