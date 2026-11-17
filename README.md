# Financial Brand Explorer

An interactive, client-side dashboard for exploring generational differences in financial-services brand awareness, current usage and stated preferences

## Features

- 30 financial brands across five audience views (Overall, Gen Z, Millennials, Gen X, Baby Boomers)
- Searchable and scrollable brand picker
- Sortable metric leaderboard (awareness, current usage, MOST, LEAST, net preference)
- Interactive usage vs preference scatter plot
- Clickable brand details and a cross-generation comparison table
- Responsive layout with hover, focus and active states

## Quick start

Open `index.html` in your browser — no server, build step or dependency installation required

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `financial-brand-explorer`
2. Upload the contents of this folder to the repository root
3. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and `/ (root)`
4. GitHub will show the public website URL

## Data

`data/brand_metrics.json` contains **aggregate, unweighted** metrics derived from `Brand_Landscape_Results.xlsx` → `Brand Metrics` in the project's source workbook

- Research analysis sample: n = 982
- Cohorts: Gen Z (215), Millennials (275), Gen X (242), Baby Boomers (250)
- Brands: 30
- Net preference: `MOST% - LEAST%`, measured in percentage points
- This is descriptive survey data, not causal evidence

No respondent-level microdata are included in the repository

## Branding and external resources

The interface uses an Intuify-inspired blue/turquoise/green palette and a **stylized, non-official wordmark symbol**. Brand logos are fetched from Simple Icons or a Google favicon service when the viewer is online. Some icons may not resolve; in that case a neutral diamond placeholder is displayed rather than a fabricated brand monogram

Brand marks and names belong to their respective owners. This dashboard is an academic research prototype and is not an official Intuify product

## Versioning

- v0.3 — Intuify-inspired redesign, complete 30-brand selection, searchable dropdown, meaningful button states, hover interactions, 5 audience filters, local data bundle
