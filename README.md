# treehole-landing

Download & install landing page for **亦可赛艇 / treehole**, the unofficial
mobile client of SJTU's anonymous campus forum.

- App source: [ayaka-notes/treehole-app](https://github.com/ayaka-notes/treehole-app)
- Static site lives in [`docs/`](./docs) — a single self-contained `index.html`
  (no build step), with Chinese / English i18n.
- Deployed to **GitHub Pages** via `.github/workflows/pages.yml` on every push to `main`.

## What the page covers

- Android APK and iOS IPA download buttons
- Feature overview
- A fool-proof, step-by-step **iOS install guide** (AltStore sideloading)
- A short Android install guide

## Local preview

It is plain HTML — just open `docs/index.html` in a browser, or:

```bash
cd docs && python3 -m http.server 8000
```

## Configuration

Download / repository URLs are constants at the top of the `<script>` block in
`docs/index.html` (`RELEASES`, `REPO`) — edit them there if the locations change.
