# NEXUS Datapad v0.2

Campaign content is now separated from the interface.

## Main files
- `index.html` — site shell
- `style.css` — visual styling
- `app.js` — navigation, search and rendering
- `data/campaign.json` — campaign database

## Editing lore
Most future updates only require editing `data/campaign.json`. Cross-links use the target record's `id`.

## Local testing
Because the app loads JSON, run a simple local web server:

`python -m http.server 8000`

Then open `http://localhost:8000`.

## Publishing
Suitable for GitHub Pages, Cloudflare Pages, or another static host.
