# SP PAPIYA FASHION

SP PAPIYA FASHION — Bengali, mobile-first e-commerce website for Bangladesh women's clothing.

Live site: https://sppapiyafashion.shop/

## Hosting
- This repo is published with GitHub Pages (main branch, root).
- `index.html` is the built site (fast-load version, 0.18 MB). Product photos are in `assets/opt/`.
- Supabase is the backend (products, orders, admin login). It works from any host — moving from Netlify to GitHub Pages does not change Supabase.
- `_redirects` is kept for Netlify; GitHub Pages ignores it. The site uses hash routing (`#/admin`, `#/product/...`), so no server redirect is needed on GitHub Pages.
- `.nojekyll` disables Jekyll so all files are served as-is.

## Deploy
Upload the contents of this folder to the repo root, enable Pages, and if moving the custom domain, set the custom domain to `sppapiyafashion.shop` in Pages settings and update DNS at Hostinger (see DNS_STEPS_BN.txt in the workspace, not in this repo).
