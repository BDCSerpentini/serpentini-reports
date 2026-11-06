# BDC Agent Performance tab

Added a **BDC Agents** dashboard tab using Matador All Users export from July 1–31, 2026. The data is embedded in `index.html`, so no changes to `reports.json` are necessary.

- 21 agents from the screenshot, including **Noah** instead of the old display name **Woah**.
- Four metrics for each: Messages Sent, Customers Messaged, Handoffs, Handoff Reply Rate.
- Most Messaged Location follows the sole location row available for each agent (or "No messages" for zero-message agents).
- Search by agent, filter dealership, and sort by metric.
- Fixed July 2026 snapshot; changing dashboard period selectors does not change the agent data.
- This GitHub Pages site is public: agent performance figures will be publicly visible if published.

## To deploy

Extract the ZIP; copy its contents into your local Git checkout at `C:\Users\BrianaLehlbach\Desktop\Report Website\serpentini-reports-main` without replacing `.git`; review `git status` and push the changes to `main`.
