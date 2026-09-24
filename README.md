# Major Dream Williams personal website

A static, dependency-free website for `www.majordreamwilliams.com`.

## Deploy

Import `MajorDream444/majordreamwilliams-site` into Vercel with the Other framework preset. Keep the root directory as `/`, leave build command empty, and deploy `main`. Add `majordreamwilliams.com` and `www.majordreamwilliams.com` in Vercel Domains. Follow the exact DNS records shown there and redirect the apex to `www`.

## Publish content

Edit `index.html` for the public biography, speaking offer and selected work. Edit `vault/index.html` to publish approved books, essays, talks and theories. Do not put private research or third-party PDFs in this public repo. Booking currently opens an email to `contact@majordreamwilliams.com`. Replace the publication-link request with Major's confirmed Substack URL. Add approved headshots and event media once supplied.

Run `python3 -m http.server 8000` locally and inspect `/` and `/vault/` at desktop and mobile widths before publishing.
