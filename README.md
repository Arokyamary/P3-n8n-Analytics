P3: n8n Intelligent Analytics Automation

An automated analytics pipeline that queries PostgreSQL, generates AI executive reports using Groq LLaMA 3, sends Slack alerts, and auto-refreshes a Google Sheets dashboard — eliminating 3+ hours of daily manual reporting.

🛠️ Tech Stack
n8n — Workflow Automation
PostgreSQL — Database
Groq LLaMA 3 — AI Report Generation
Slack — Alerts & Notifications
Google Sheets — Live Dashboard

📊 Workflows
Workflow 1: AI Daily Executive Report — Runs at 8 AM, queries PostgreSQL, Groq AI writes executive summary, sends to Slack
Workflow 2: Demand Anomaly Alerts — Runs every 15 minutes, detects demand spikes, sends instant Slack alert
Workflow 3: Google Sheets Auto-Refresh — Runs at 7 AM, appends daily KPIs to Analytics Dashboard

P3_n8n_Automation/

├── n8n_workflows/

│   ├── workflow1_ai_daily_report.json

│   ├── workflow2_anomaly_alerts.json
│   └── workflow3_google_sheets.json
├── screenshots/
│   ├── workflow1_screenshot.png
│   ├── workflow2_screenshot.png
│   └── workflow3_screenshot.png
└── README.md

⚡ Impact
Eliminates 3+ hours of daily manual reporting
Real-time anomaly detection every 15 minutes
Automated Google Sheets dashboard refresh

👩‍💼 Built by Arokyamary
