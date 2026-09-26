Ausfig12 FIXED offline

Upload these files to the root of the GitHub repository:
- index.html
- sw.js
- manifest.webmanifest
- icon.svg

GitHub Pages: Settings -> Pages -> Deploy from a branch -> main -> /(root).
After deployment, open the site once online. Then it can work offline from the service-worker cache.

Argon2id is embedded inside index.html. No CDN is required.
