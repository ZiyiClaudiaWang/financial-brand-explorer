# Financial Brand Explorer

An interactive financial brand explorer using Intuify survey results

## Explore

- Browse 30 financial brands in a four-column desktop directory (8 rows for 30 brands)
- Compare brands by awareness, usage, MOST, LEAST, and net preference across generations
- Interactive leaderboards, charts, brand comparisons, and brand details
- Search brands and filter audience groups

## Brand assets

All 30 brand logos and the Intuify logo come from the project team's supplied logo archive and are stored as optimized, lossless WebP images in `assets/logos/`

The dashboard embeds these same logos in `index.html`, so they display without relying on external favicon providers, including when the HTML is opened offline

The surrounding icon frames have transparent backgrounds and no borders; opaque colors that are part of a supplied logo itself remain intact

## Deployment

Use GitHub Pages from the `main` branch, repository root. No backend is required

## Data

Uses aggregate, unweighted survey metrics from the team's cleaned sample (n=982)
Net preference = MOST% − LEAST% in percentage points
The analysis is descriptive, not causal, and not a conversion funnel
No respondent-level raw data are included

All brand names and trademarks belong to their respective owners. This is an independent academic research prototype

## Changelog

V7 — Replaced logo placeholders with supplied brand logos and official Intuify logo, changed browse cards to four columns, and shortened `View details` to `View`
