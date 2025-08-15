# 🧠 Stack Overflow Developer Survey Dashboard

This project analyzes the Stack Overflow Developer Survey using Python, SQL, and IBM Cognos Analytics. It features a multi-tab dashboard that visualizes developer preferences across languages, databases, platforms, frameworks, and demographics. The goal is to deliver clear, actionable insights for stakeholders through scalable data workflows and executive-ready reporting.

---

## 🚀 Project Highlights

- 🔍 **Multi-tab Cognos dashboard** with filters and conditional formatting
- 🧹 **Python preprocessing** for multi-value columns and missing data
- 🧠 **Feature engineering** to map, explode, and enrich survey responses
- 📊 **SQL queries** for slicing data and supporting dashboard logic
- 🎯 **Executive summary** in PowerPoint for stakeholder communication

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                            |
|-----------------|------------------------------------|
| Python (pandas) | Data cleaning & feature engineering |
| SQL             | Filtering, aggregation, and joins   |
| Cognos Analytics| Dashboard design & visualization    |
| PowerPoint      | Executive summary presentation      |

---

## 📁 Repository Structure

stackoverflow-dashboard/
│
├── data/
│   └── datasets
│
├── scripts/
│   ├── preprocess.py
│   └── sql_queries.sql
│
├── dashboards/
│   ├── dashboards
│  
│
├── report/
│   └── executive_summary.pptx
│
├── README.md
└── requirements.txt

## 📊 Dashboard Highlights
- Top-N filtering and conditional palettes
- Multi-value column explosion and mapping
- Demographic breakdowns and tech stack trends

## 📜 Executive Summary
See `report/capstone-story.pptx` for stakeholder-ready insights.

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run `scripts/preprocess.py` and `feature_engineering.py`
4. Explore the dashboard mockup in `dashboards/`

## 📌 Notes
- Cognos dashboard is not interactive here—see screenshots and notes
- Data source: Stack Overflow Developer Survey (public dataset)

