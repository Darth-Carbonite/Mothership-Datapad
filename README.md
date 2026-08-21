# NEXUS Datapad v0.3

## New in v0.3
- Boot sequence
- Recent Intelligence panel driven by `updateState`
- Breadcrumb navigation
- Knowledge states
- Record IDs and archive integrity
- Image support with graceful placeholders
- Stronger redaction presentation
- Special Monarch treatment
- Improved cross-links and record headers

## Updating the live GitHub Pages site
Replace the current root-level `index.html`, `app.js`, `style.css`, and `data/campaign.json` with these versions. Add the `images/` folders. Commit to `main`; GitHub Pages should redeploy automatically.

## Recent Intelligence
Use `NEW`, `UPDATED`, `COMPROMISED`, or `NONE` in `updateState`.

## Knowledge states
Use `KNOWN`, `PARTIAL`, `UNVERIFIED`, or `CLASSIFIED`.

## Images
Add files matching the paths in `campaign.json`, for example `images/personnel/arkady.webp`. Missing files display a terminal-style placeholder rather than a broken image.

## Security note
Do not place unrevealed GM-only secrets in this public JSON. Visual redaction is presentation only.
