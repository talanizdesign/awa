# Awa

A mobile app that asks how the apps you use make you feel — the story of building it, from idea to a working iOS app, with the real app embedded to try.

By Teresa Alaniz. Awa — including its concept, name and design — is her intellectual property. © 2026 Teresa Alaniz. All rights reserved.

## Deploy (GitHub Pages)

Static site — no build step. Enable Pages on the `main` branch, root folder. `.nojekyll` is included so the embedded app (`awa-app/_expo/`) is served.

The embedded app is built for the path `/awa/` (repo name `awa`). If you rename the repo, update the base path `/awa/awa-app` in `awa-app/index.html` and `awa-app/_expo/static/js/web/entry-*.js`.
