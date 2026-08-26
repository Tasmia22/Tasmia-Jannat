# Tasmia Jannat — Research Portfolio

A responsive, single-page academic/research portfolio built with plain HTML, CSS, and JavaScript.

## Files

- `index.html` — site content and structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and subtle scroll-in animations
- `Tasmia_Jannat_CV.pdf` — downloadable CV

## Preview locally

Open `index.html` directly in a browser.

For a local web server, from this directory run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repository, e.g. `tasmia-jannat.github.io`.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

If the repository is exactly `<your-github-username>.github.io`, it will become your main GitHub Pages website.

## Personal photo

The current hero uses a clean `TJ` monogram so the site works immediately without a photo. If you want to use a professional headshot, add the image to the folder and update the hero card in `index.html`.

## Editing

All content is written directly in `index.html`. The visual system is controlled by CSS variables at the top of `styles.css`, especially:

- `--bg`
- `--surface`
- `--accent`
- `--ink`
- `--muted`

No build step or JavaScript framework is required.
