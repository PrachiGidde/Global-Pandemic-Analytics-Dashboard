# Global Pandemic Data Analytics & Visualization Dashboard

## Project Overview

An end-to-end data analytics project analyzing COVID-19 pandemic data across
201 countries from January 2020 to March 2023. The project covers the complete
data analytics lifecycle — from raw data collection and cleaning to SQL-based
analysis and an interactive Microsoft Excel dashboard.

---

## Key Findings

| Finding | Detail |
|---|---|
| Total Confirmed Cases | 676,570,149 across 201 countries |
| Global Fatality Rate | 1.02% |
| Peak Month | January 2022 — 90.4 million new cases (Omicron wave) |
| Outlier Days Detected | 18 days exceeded 4-sigma threshold |
| Zero Recovery Anomaly | 194/201 countries flagged |
| Data Completeness | 100% across all 201 countries |
| Null Values Found | 15,630 null values in Fatality and Recovery Rate (6.8%) |

---

## Data Quality Audit Results

- **Finding 1 — Null Values:** 15,630 null values in Fatality Rate and
  Recovery Rate columns (6.8%) caused by zero confirmed cases in early
  pandemic period
- **Finding 2 — Zero Recovery Anomaly:** 194 out of 201 countries show
  zero recoveries — Johns Hopkins discontinued recovery tracking in mid-2021
- **Finding 3 — Duplicate Records:** No duplicates found across 229,743 records
- **Finding 4 — Reporting Consistency:** All 201 countries reported consistently
- **Finding 5 — Statistical Outliers:** 18 days above 4-sigma threshold —
  all in January–February 2022 corresponding to Omicron peak
- **Finding 6 — Data Completeness:** 100% completeness across all countries

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python 3.10 | Data collection, cleaning, transformation |
| Pandas 2.2.2 | ETL pipeline, data manipulation, quality audit |
| SQLite + SQL | Analytical queries, KPI extraction, wave analysis |
| Microsoft Excel | Interactive dashboard, charts, KPI scorecards |
| Google Colab | Cloud-based development environment |
| GitHub | Version control and project showcase |

---

## Dataset

- **Source:** Johns Hopkins University CSSE COVID-19 Dataset
- **Coverage:** 201 countries, Jan 2020 to Mar 2023
- **Raw Records:** 229,743 rows
- **URL:** https://github.com/CSSEGISandData/COVID-19

---

## Project Structure
Global-Pandemic-Analytics-Dashboard/

│

├── notebooks/
│   └── Global_Pandemic_Dashboard.ipynb
│

├── data/

│   ├── cleaned/
│   │   └── covid_master.csv

│   ├── sql/

│   │   ├── sql_query1_global_kpi.csv

│   │   ├── sql_query2_top10_countries.csv

│   │   ├── sql_query3_yearly_trend.csv

│   │   ├── sql_query4_anomaly_flags.csv

│   │   └── sql_query5_monthly_waves.csv

│   └── quality_reports/

│       ├── data_quality_issues.csv

│       └── completeness_scores.csv

│
├── excel_exports/
│   └── Pandemic_Data_For_Dashboard.xlsx

│
└── screenshots/
└── dashboard_screenshot.png

---

## SQL Queries Written

1. **Global KPI Summary** — Total confirmed, deaths, fatality rate
2. **Top 10 Countries** — Ranked by confirmed cases
3. **Yearly Trend Analysis** — Year over year comparison
4. **Data Quality Flags** — Zero recovery anomaly using CASE WHEN
5. **Monthly Wave Analysis** — Using LAG window function

---

## Excel Dashboard

- 5 KPI Scorecards
- Global Trend Line Chart
- Monthly Wave Bar Chart
- Top 10 Countries Bar Chart
- Year over Year Column Chart

---

## Author

**Prachi Gidde**
- LinkedIn: your-linkedin-url
- GitHub: your-github-url
- Email: your-email

---

## Data Source Credit

Johns Hopkins University CSSE —
https://github.com/CSSEGISandData/COVID-19
