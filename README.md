![Dashboard](screenshots/dashboard_screenshot.png)
# Global Pandemic Data Analytics & Reporting Dashboard

## Project Overview
An end-to-end **data analytics and reporting project** focused on transforming large-scale COVID-19 data into **accurate, structured, and decision-ready reports**.

This project simulates a **Data Analytics & Reporting Analyst role** by emphasizing **data validation, KPI reporting, SQL analysis, and dashboard creation**.

- **Dataset**: Johns Hopkins University CSSE COVID-19
- **Coverage**: 201 countries (Jan 2020 – Mar 2023)
- **Total Records**: 229,743

---

## Business Objective
- Ensure **data accuracy and consistency** for reliable reporting  
- Generate **KPI-driven insights** for business understanding  
- Build **clear and structured dashboards** for stakeholders  

---

## Key Reporting Insights
- **676M+ total confirmed cases** across 201 countries  
- **Global fatality rate: 1.02%**  
- **Peak period identified**: January 2022 (90M+ cases)  
- Generated **Top 10 country reports** for comparative analysis  
- Identified **reporting gaps** in recovery data (194 countries)  

---

## Data Quality & Validation
Performed comprehensive data validation on 229K+ records:

- Identified and handled **15,630 null values (6.8%)**  
- Detected **zero recovery anomaly** due to discontinued reporting  
- Ensured:
  - ✅ 100% data completeness  
  - ✅ Zero duplicate records  
  - ✅ Consistent country-level reporting  

---

## SQL-Based Reporting
Developed structured SQL queries to support reporting needs:

- KPI summary (cases, deaths, fatality rate)  
- Top 10 countries by confirmed cases  
- Year-over-year trend analysis  
- Monthly wave detection using **LAG window function**  
- Data anomaly detection using **CASE WHEN**  

---

## Dashboard & Reporting
Built an **interactive Excel dashboard** designed for clarity and decision-making:

- KPI scorecards (cases, deaths, fatality rate)  
- Global trend analysis (line charts)  
- Monthly wave comparison (bar charts)  
- Top 10 countries visualization  
- Year-over-year performance tracking  

---

## Tools & Technologies
- **Python (Pandas)** – Data cleaning & transformation  
- **SQL (SQLite)** – Data querying & reporting  
- **Microsoft Excel** – Dashboard & visualization  
- **Google Colab** – Development environment  
- **GitHub** – Version control  

---

## Project Structure
Global-Pandemic-Analytics-Dashboard/

├── notebooks/
│ └── Global_Pandemic_Dashboard.ipynb

├── data/
│ ├── cleaned/
│ │ └── covid_master.csv
│ ├── sql/
│ ├── quality_reports/
│ └── excel_exports/

├── screenshots/
│ └── dashboard_screenshot.png


---

## Key Skills Demonstrated
- Data validation & quality checks  
- KPI reporting & dashboarding  
- SQL-based data extraction  
- Data analysis & trend interpretation  
- Reporting accuracy and consistency  

---

## Author
**Prachi Gidde**  
- LinkedIn: https://www.linkedin.com/in/prachi-gidde/ 
- GitHub: https://github.com/PrachiGidde 

---

## Data Source
Johns Hopkins University CSSE  
https://github.com/CSSEGISandData/COVID-19
