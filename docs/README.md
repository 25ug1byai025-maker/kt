# kt — Site in docs/

This directory contains a simple static website intended to be served via GitHub Pages from the `docs/` folder on the `main` branch.

How to publish

1. In your repository go to Settings -> Pages.
2. Under "Source" select "Deploy from a branch" and choose the `main` branch and `/docs` folder.
3. Save — your site will be published at `https://<your-username>.github.io/kt` (it can take a few minutes).

What to customize

- `docs/index.html` — the site markup.
- `docs/styles.css` — the site styles.
- Add images or other assets under `docs/` and reference them from `index.html`.

If you prefer automatic deployments to `gh-pages`, I can add a GitHub Action for that.
