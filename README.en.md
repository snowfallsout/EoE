# Echoes of Emotion (EoE)

A website combining contemporary ceramic art with modern digital interactive technology.

## Overview
- Entry point: `index.html`
- Static resources: `assets/`, `include/`
- Build metadata: `needle.buildinfo.json`
- Current status: Early prototype (static front-end, JavaScript + HTML)

## Quick start (local)
1. Open `index.html` directly in your browser for a quick preview.
2. Or run a simple static server:
   - Python 3:
     ```
     python -m http.server 8000
     ```
     then visit `http://localhost:8000`.
   - Node (live-server / http-server):
     ```
     npx live-server
     ```

## Build & Deploy
- If you have a build step, add `package.json` and scripts (`build`, `start`) and document them here.
- To publish via GitHub Pages:
  - Place a site in `docs/` or use `gh-pages` branch and enable Pages in repository settings.
  - Optionally add a GitHub Actions workflow to automate build + deploy.

## Repository layout
- `index.html` — Site entry page
- `assets/` — Images, audio, video, other static assets
- `include/` — Shared HTML fragments or modules
- `needle.buildinfo.json` — Build metadata

## Contributing
See `CONTRIBUTING.md` for how to contribute, branch naming, PR process and code style.

## Contact / Maintainer
- Repository: https://github.com/snowfallsout/EoE
- Maintainer: Xueyi Huang (github: snowfallsout)、SINWU LOK (github: sinwulok）
