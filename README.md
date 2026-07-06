# KapFam5 Central Dashboard v2.3

Data-driven static dashboard for `kapfam5.com`, published from the `kapfam5-home` Netlify project.

## v2.3 updates

- Added explicit Netlify `_redirects` rules so the Netlify app subdomain and `www.kapfam5.com` normalize to `https://kapfam5.com`.
- Added canonical metadata across dashboard pages for the custom domain.
- Added baseline security/cache headers for the static dashboard, assets, and JSON data.

## v2.1 updates

- Removed Home Energy section.
- Executive dashboard homepage.
- Boise investment table now includes direct Redfin, Zillow, Google Maps, and Analysis links.
- Added Save-to-Watchlist buttons using browser localStorage.
- Updated best-next-action candidates: 10473 W Jerry Peak and 10031 W Shelborne.
- Property data lives in `/data/properties.json`.

## Deploy

Copy all files to the root of the GitHub repo and push to `main`. Netlify should auto-deploy.
