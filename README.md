# score-cache-slides

Explainer slide deck for [score-cache](https://github.com/nick-hildebrant-etas/score-cache) — a self-hosted, hermetic dependency mirror and build cache for the eclipse-score / S-CORE project family.

**[View slides →](https://nick-hildebrant-etas.github.io/score-cache-slides/)**

## What's covered

- Why score-cache exists (the problem it solves)
- Architecture and services (bazel-remote, devpi, cargo-mirror, artifact mirror)
- Why a public cache container is needed
- Replacing with Artifactory / Nexus in corporate environments
- How it is built with Dagger
- Why Dagger was chosen
- Dagger benefits for score/reference-integration and modules
- Decisions taken and open decisions

## Development

```bash
npm install
npm run preview   # live preview at http://localhost:8080
npm run build     # build static HTML to dist/index.html
```

Slides are written in [Marp](https://marp.app) Markdown (`slides.md`).
SVG diagrams live in `images/`.

## Deployment

Slides are automatically built and deployed to GitHub Pages on every push to `main`.
