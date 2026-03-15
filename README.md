# score-cache-slides

Reveal.js slide deck explaining [score-cache](https://github.com/nick-hildebrant-etas/score-cache) — a hermetic build cache for the S-CORE project.

## Live slides

Once GitHub Pages is enabled for this repository, the deck is published at:

```
https://nick-hildebrant-etas.github.io/score-cache-slides/
```

## Topics covered

- Why S-CORE needs a hermetic dependency cache
- What is inside score-cache (bazel-remote, devpi, cargo-mirror, artifact mirror)
- Why a public cache container is the right default
- How to replace it with Artifactory / Nexus in a corporate environment
- How score-cache is built with Dagger and why Dagger was chosen
- How Dagger helps with score/reference-integration and reusable modules
- Open decisions and decisions that are already settled

## Viewing locally

Open `index.html` in any modern browser — no build step required.  All
Reveal.js assets are loaded from the jsDelivr CDN.

## Deployment

Pushing to `main` triggers the GitHub Actions workflow in
`.github/workflows/pages.yml`, which publishes the `index.html` directly to
GitHub Pages.  Enable Pages in the repository settings
(**Settings → Pages → Source: GitHub Actions**) to activate the deployment.
