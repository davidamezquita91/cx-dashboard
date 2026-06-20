# CX Metrics Dashboard

Internal dashboard for Winmore CX operations — tracks implementation progress, support ticket performance, and open bugs & tasks across customers.

## What's inside

- **Implementations** — Epic and story progress for active customer implementations (GW, Titanium, MSC, AIT, OIA), with due dates, assignees, and latest status updates
- **Support Tickets · 2026** — Resolution time analytics, charts by priority/assignee/type, and a full searchable ticket log
- **Bugs & Tasks** — Open engineering escalations filterable by customer

## How to update

1. Export the latest data from Jira/Zendesk into `CX Metrics 2026 (N).xlsx` with the five sheets: `implementations`, `implementations_updates`, `customer_bugs`, `customer_tasks`, `support`
2. Ask Claude (Cowork) to update the dashboard using the new file
3. Re-upload `cx_dashboard.html` to this repo and commit

## Viewing

Open the live dashboard: [cx_dashboard.html](./cx_dashboard.html)

Or via GitHub Pages once enabled: `https://<your-username>.github.io/cx-dashboard/cx_dashboard.html`

## Last updated

June 20, 2026
