# Galvanic Energy site rebuild

Static mockups for the Galvanic Energy website rebuild. All fonts, images and styles are inlined in each HTML file, so there is no build step.

## Live pages

Published with GitHub Pages:

- Galvanic Energy: https://hammonds-media-marketing.github.io/galvanic-rebuild/
- Bright Star Lithium: https://hammonds-media-marketing.github.io/galvanic-rebuild/bright-star.html

| File | Page |
| --- | --- |
| `index.html` | Galvanic Energy homepage mockup |
| `bright-star.html` | Bright Star Lithium CEO mockup |

## How deployment works

- `.github/workflows/deploy-pages.yml` runs on every push to `main` (or manually via **Actions → Deploy to GitHub Pages → Run workflow**).
- It publishes `index.html` and `bright-star.html` to GitHub Pages. A `.nojekyll` file is included so the site also works if Pages is set to "Deploy from a branch".
- Repo setting required once: **Settings → Pages → Source: GitHub Actions**. The workflow tries to enable this automatically on first run.
