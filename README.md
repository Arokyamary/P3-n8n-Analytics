# P3: n8n Intelligent Analytics Automation

An automated analytics pipeline that queries PostgreSQL, generates AI executive reports using Groq LLaMA 3, sends Slack alerts, and auto-refreshes a Google Sheets dashboard — eliminating 3+ hours of daily manual reporting.

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| n8n | Workflow Automation |
| PostgreSQL | Database |
| Groq LLaMA 3 | AI Report Generation |
| Slack | Alerts & Notifications |
| Google Sheets | Live Dashboard |

---

## 📊 Features
- ✅ AI-generated daily executive summary sent to Slack every morning
- ✅ Real-time demand spike detection every 15 minutes
- ✅ Automated Google Sheets dashboard refresh daily
- ✅ Eliminates 3+ hours of manual reporting

---

## ⚙️ Workflows

### 1️⃣ AI Daily Executive Report
- Runs every day at **8:00 AM**
- Queries PostgreSQL for yesterday's sales data by category
- Groq LLaMA 3 generates a 5-sentence executive summary
- Sends report automatically to Slack channel

### 2️⃣ Demand Anomaly Alerts
- Runs every **15 minutes**
- Detects demand spikes across category and city
- Sends instant Slack alert if spike is found

### 3️⃣ Google Sheets Auto-Refresh
- Runs every day at **7:00 AM**
- Queries PostgreSQL for daily KPIs
- Appends data rows to Analytics Dashboard Google Sheet

---

## 📁 Project Structure
```
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
```

---

## 🚀 Run Locally

### Prerequisites
- Node.js v20+
- PostgreSQL
- Groq API Key (free at console.groq.com)
- Slack Workspace

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/Arokyamary/P3-n8n-Analytics.git
cd P3-n8n-Analytics
```

**2. Install and start n8n**
```bash
npm install -g n8n
n8n start
```

**3. Open browser at** `http://localhost:5678`

**4. Import workflows**
- Click Add Workflow
- Click `...` menu
- Click Import from File
- Select each JSON file from n8n_workflows folder

**5. Set up credentials**
- PostgreSQL connection
- Groq API Key
- Slack Bot Token
- Google Sheets OAuth

**6. Activate all 3 workflows**

---

## ⚡ Impact
- Eliminates 3+ hours of daily manual reporting
- Real-time anomaly detection every 15 minutes
- Automated Google Sheets dashboard refresh

---

## 👩‍💼 Built by Arokyamary
