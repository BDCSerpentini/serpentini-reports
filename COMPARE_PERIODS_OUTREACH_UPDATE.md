# Compare Periods · Automations & Broadcasts update

Updated `index.html` to include a new outreach comparison section between Matador Dashboard and Email Template Performance.

- Separate Automations and Broadcasts toggle; one metric selector with counts and rates.
- Two selected months or quarters, inherited from Compare Periods.
- Inherits the existing dealership filter, supports seven individual dealerships.
- By dealership / by period chart grouping, and sorting high/low/A–Z.
- Counts use horizontal bars; rates use dot/lollipop marks automatically.
- Difference card uses percentage-point changes for percent metrics, relative changes for counts.
- Quarterly data uses sums for counts, message-weighted reported reply rates and recomputed engagement/efficiency.
- Missing rows and months remain missing, not zero; partial-quarter coverage explicitly flagged.
- No changes needed in Streamlit: uses existing published `automations` and `broadcasts` arrays in `reports.json`.

To deploy: replace `index.html` in website repository, optionally include this markdown note. Do not overwrite the live `reports.json` with a stale copy.
