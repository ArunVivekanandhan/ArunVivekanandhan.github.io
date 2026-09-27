# arunvivekanandhan.github.io

Root site for `https://arunvivekanandhan.github.io/`.

- `/.well-known/assetlinks.json` — Digital Asset Links: proves that the Android app
  `io.github.arunvivekanandhan.deutschcoach` (Deutsch-Coach, Google Play) belongs to this site, so the app opens
  without a browser address bar. The two `REPLACE_WITH_…` values are the SHA-256 certificate fingerprints
  (upload key from PWABuilder, app signing key from Play Console → App integrity).
- `.nojekyll` — tells GitHub Pages to serve the `.well-known` folder.
- `index.html` — forwards to the app: https://arunvivekanandhan.github.io/deutsch-coach/
