\# P3: n8n Intelligent Analytics Automation



An automated analytics pipeline that queries PostgreSQL, generates AI executive reports using Groq LLaMA 3, sends Slack alerts, and auto-refreshes a Google Sheets dashboard — eliminating 3+ hours of daily manual reporting.



\## 🛠️ Tech Stack

\- \*\*n8n\*\* — Workflow Automation

\- \*\*PostgreSQL\*\* — Database

\- \*\*Groq LLaMA 3\*\* — AI Report Generation

\- \*\*Slack\*\* — Alerts \& Notifications

\- \*\*Google Sheets\*\* — Live Dashboard



\## 📊 Workflows

\- \*\*Workflow 1: AI Daily Executive Report\*\* — Runs at 8 AM, queries PostgreSQL, Groq AI writes executive summary, sends to Slack

\- \*\*Workflow 2: Demand Anomaly Alerts\*\* — Runs every 15 minutes, detects demand spikes, sends instant Slack alert

\- \*\*Workflow 3: Google Sheets Auto-Refresh\*\* — Runs at 7 AM, appends daily KPIs to Analytics Dashboard



\## 🚀 Run Locally

git clone https://github.com/Arokyamary/P3-n8n-Analytics.git

cd P3-n8n-Analytics

npm install -g n8n

n8n start



\## 📁 Project Structure

P3\_n8n\_Automation/

├── n8n\_workflows/

│   ├── workflow1\_ai\_daily\_report.json

│   ├── workflow2\_anomaly\_alerts.json

│   └── workflow3\_google\_sheets.json

├── screenshots/

│   ├── workflow1\_screenshot.png

│   ├── workflow2\_screenshot.png

│   └── workflow3\_screenshot.png

└── README.md



\## ⚡ Impact

\- Eliminates 3+ hours of daily manual reporting

\- Real-time anomaly detection every 15 minutes

\- Automated Google Sheets dashboard refresh



\## 👩‍💼 Built by Arokyamary

