# Service Appointments redesign

Changes in `index.html`:
- Bitly Clicks -> Link Clicks.
- GA4 Active Users -> Reschedules (in this setup GA4 users represent reschedule-form submitters as confirmed by the reporting owner).
- GA4 Users ÷ Clicks -> Click → Reschedule Rate.
- Four compact KPI cards including previous-month rate change where comparable data exists.
- All Dealerships: fixed-location-color dealership rankings by a selected service metric.
- One Dealership: link-click vs reschedule activity breakdown.
- Monthly trend chart with selectable metric, preserving gaps for unpublished months; for a month selection, show recent reported months, and for a quarter selection, the three quarter months.
- Data-derived insights and an expandable detail table.

No data files are included. Existing `reports.json` is unchanged. Stored keys `clicks` and `users` are retained for compatibility with the Streamlit publisher.

**Reporting caveat:** This is a cross-source ratio of GA4 form-submitters to Bitly link clicks; it does not establish that the same unique users clicked and submitted. Users may have submitted directly without Bitly click, or clicked more than once.
