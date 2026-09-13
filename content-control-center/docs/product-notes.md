# MVP Developer Notes

The implementation is deliberately a small SPA so it can be tested by opening `index.html`, while keeping application state and UI code separated into `app.js` and `style.css`.

Important rules implemented: Project is the brand/workspace entity; no Idea/Planning statuses; KPI is outside Scenario; Deadline sits with Title/Status and includes date + countdown until overdue; role-aware dashboard/module visibility; monthly calendar remains visible without horizontal scroll; mobile sidebar is a drawer; Production has Kanban/Table toggle; local persistence is enabled; Activity Log contains Project/Date/Time/User/User ID/Change.

Prototype content: Pardis weeks 1–4 are populated from the supplied Pardis source. Alireza Test uses one scenario per week from Pardis weeks 5–9 starting at 1 Mehr.
