# Yue (Zelda) Hu — Portfolio

Static mirror of [yuezeldahu.framer.website](https://yuezeldahu.framer.website/), fully self-contained (all Framer assets are vendored under `assets/`).

- Every page is protected by a client-side password gate (SHA-256 hash check, session-scoped). The password is not stored in this repo — only its hash.
- Built for GitHub Pages at the base path `/portfolio/`. If the repo is renamed, the `/portfolio` path prefix in the HTML/JS must be updated.

## Local preview

```
python3 -m http.server 8901
```

Then open http://localhost:8901/ — note the site expects to be served under `/portfolio/`, so for local preview serve the parent directory containing this folder named `portfolio`.

## Pages

/ , /about, /exploration, /community, /colmo, /collection-page-old, /virtu-ai, /oudio, /animal-farm, /backpac, /drum
