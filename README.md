# Financial Brand Explorer

An interactive dashboard for comparing financial-services brand awareness, current usage and stated preferences across generations, using aggregate survey results

## Explore

- 30 brands and five audience views: Overall, Gen Z, Millennials, Gen X, Baby Boomers
- Full-width leaderboard: highest, lowest or largest generational gap; top 10 or all 30
- Searchable brand picker, interactive preference-versus-usage scatter chart
- Choose up to four brands for a generation-by-generation comparison
- Brand detail view with rank among the 30 surveyed brands, cross-generation spread and metric definitions
- Responsive design and hover/focus states

## Run and deploy

Open `index.html` directly, or serve the repository root with a static HTTP server

On GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)`

## Data

`data/brand_metrics.json` contains aggregate, unweighted results. The dashboard embeds the same aggregates for offline use

- Cleaned respondents: n = 982
- Gen Z: 215; Millennials: 275; Gen X: 242; Baby Boomers: 250
- 30 brands, five reported measures
- Net Preference = MOST% − LEAST%, in percentage points

The charts are descriptive. Brand rankings are survey rankings, not market rankings, and do not establish individual preference-to-use conversion or causal impact. No respondent-level records are included

## Logos and brand identity

Nine locally stored SVG symbols are in `assets/logos` and embedded as offline fallbacks. Other brand icons are attempted via public favicon sources; if unavailable, the brand name is shown rather than a fabricated logo. Upload properly sourced logos to `assets/logos` to remove the external dependency and update `LOCAL` in `index.html`

Brand names and marks are the property of their owners. The Intuify-styled header mark is illustrative, not the official logo. This is an independent academic research prototype

## Versioning

- V5: full-width leaderboard with ranked categories, responsive side-by-side charts, up to four brand comparisons, context-rich details, logo and styling refinements