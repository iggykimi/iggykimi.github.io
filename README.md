# iggykimi.github.io

GitHub Pages user site. It hosts the public pages that Google Play needs for my Android apps.

| Path | URL |
|---|---|
| Quiet Focus privacy policy | https://iggykimi.github.io/privacy-policy/ |
| Lumora landing page | https://iggykimi.github.io/lumora/ |
| Lumora privacy policy | https://iggykimi.github.io/lumora/privacy.html |
| Lumora terms of use | https://iggykimi.github.io/lumora/terms.html |
| Lumora Digital Asset Links | https://iggykimi.github.io/lumora/.well-known/assetlinks.json |

`assetlinks.json` lists the SHA-256 fingerprints of the certificates that sign Lumora (`com.zrano.lumora`), including the Play App Signing key.

`.nojekyll` is an empty file that turns off the Jekyll build. Jekyll skips folders whose name starts with a dot, so without it `.well-known/` is not published and `assetlinks.json` returns 404.

Pages serves the `main` branch from the root. A push to `main` publishes it.
