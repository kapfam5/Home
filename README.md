# KapFam5 Central Dashboard

Netlify-ready static site package for `kapfam5.com` / GitHub repo `kapfam5/Investments`.

## Included sections

- Executive Dashboard home page
- Boise Investment Dashboard
- Property Comparison Tool
- Weekly Boise Investment Report Archive
- Boise Family Trip dashboard
- Cobernator Dynasty dashboard placeholder
- Travel hub

## Latest implemented changes

- Removed the Home Energy dashboard.
- Converted the home page into a live executive dashboard.
- Added direct quick links for properties: Redfin, Zillow, Google Maps, and in-dashboard analysis anchors.
- Added saved/priority watchlist functionality using browser local storage.
- Added latest Week 2 Boise rental investment candidates and best-next-action properties.
- Preserved the data-driven structure for weekly updates using `/data/*.json`.

## Netlify deployment

Upload this folder or the ZIP contents to Netlify, or commit/push all files to the GitHub repository connected to Netlify.

Recommended Netlify settings:

- Build command: none
- Publish directory: `/` or repository root

## Weekly update files

Update these files each Monday:

- `/data/properties.json`
- `/data/market-summary.json`
- `/data/weekly-reports.json`

The dashboard reads those JSON files and refreshes the visible tables and cards automatically.
