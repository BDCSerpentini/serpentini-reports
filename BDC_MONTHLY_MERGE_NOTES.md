# Combined KPI Comparison + Monthly BDC Reporting

This release uses the latest KPI Comparison website version as the base.
It preserves the automatic KPI chart selector, and adds month-specific BDC Agent Performance data read from `months[YYYY-MM].bdcAgents` in `reports.json`.
The original July 2026 agent snapshot is used only when no published July record exists.
No historical metrics in `reports.json` were changed.
After deployment, verify the dealership KPI chart and BDC Agents month selector.
