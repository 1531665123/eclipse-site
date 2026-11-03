# Eclipse — website

Static landing page for Eclipse. Plain HTML + CSS, no build step.

- `index.html` — the whole page (styles are inline)
- `images/` — logo and screenshots

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. In the repo: **Settings → Pages → Build and deployment**, set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<user>.github.io/<repo>/` within a minute or two.

## To do before launch

- Point the **Download for Windows** and **Devlog** buttons at real links (search `href="#"` in `index.html`).
- Replace the placeholder system requirements in the Download section.
