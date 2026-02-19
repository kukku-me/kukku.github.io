# Kukku Marketing Site

This folder contains the static HTML/CSS for the Kukku marketing site.

## GitHub Pages setup
1. Create a new GitHub repo for the website.
2. Copy this `website/` folder into that repo (or set it as the repo root).
3. In the repo settings, enable GitHub Pages for the default branch.
4. Ensure the Pages source is set to the repo root ("/") or the folder that contains `index.html`.

## Custom domain
1. Keep the `CNAME` file with `kukku.me` in the repo root served by Pages.
2. Point your domain DNS to GitHub Pages:
   - Create `A` records for `kukku.me` to GitHub Pages IPs.
   - Create a `CNAME` record for `www.kukku.me` to `kukku-me.github.io` (optional).
3. Wait for DNS to propagate and verify in GitHub Pages settings.

## Local preview
Open `index.html` directly in a browser, or run a simple static server.

