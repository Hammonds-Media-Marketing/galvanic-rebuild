# Galvanic Energy site rebuild

Single-page mockup for the Galvanic Energy website. All fonts, images and styles are inlined in `mockup.html`, so there is no build step.

## Live site

Published with GitHub Pages at:
https://hammonds-media-marketing.github.io/galvanic-rebuild/

## How deployment works

- `.github/workflows/deploy-pages.yml` runs on every push to `main` (or manually via **Actions → Deploy to GitHub Pages → Run workflow**).
- It copies `mockup.html` to `index.html` and publishes it to GitHub Pages.
- Repo setting required once: **Settings → Pages → Source: GitHub Actions**. The workflow tries to enable this automatically on first run.
