# Comparison Dashboard UI Refresh — November 2026

The dashboard now uses the streamlined comparison layout discussed in the design review.

## Compare Periods
- Per-dealership first-to-last period change cards; no combined dealership KPI totals.
- A single interactive line chart with a metric selector, using permanent dealership colors.
- Full period-by-location figures table and coverage warnings remain.
- Removed redundant location-oriented bar charts from this tab.

## Compare Locations
- Existing dealership-by-dealership KPI cards, now with fixed dealership colors.
- Sorted horizontal ranking bars and a selector for the metric.
- AI appointment composition heatmap, using pink-to-green values independent of location colors.
- Compact email and service sections and full dealership-level table remain.
- Removed repeated historical trends and monthly bar charts (see Compare Periods).

## Consistent colors
Medina #4B7BFA; Orrville #18BAAE; Strongsville #F69751; Tallmadge #A374E5; Westlake #E95E96; Willoughby #80B747. CDJR #64748B (neutral slate because it was not in the six-color mockup).

## Important
- The published reporting dataset (`reports.json`) is not modified.
- The BDC Agents tab still displays the July 2026 snapshot, including Noah's name. Its card-header highlight has been changed to a muted dusty red.
- Existing saved data imports, filters, and navigation remain.
- The heatmap is performance-colored; never interpret its colors as dealership identities.
- The dashboard is publicly hosted on GitHub Pages. Inspect metrics before publishing.

## Install
Copy the contents of `serpentini-reports-main/` into the existing local Git repository at:
`C:\Users\BrianaLehlbach\Desktop\Report Website\serpentini-reports-main`
Keep `.git`, review `git status`, commit, and push `main`.
