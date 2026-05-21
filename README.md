# 🇿🇦 South Africa Youth Unemployment & Skills Gap Analysis
### A Data Analyst Portfolio Project | Q1: 2023 – Q1: 2026

---

## 📌 Project Overview

This project analyses South Africa's youth unemployment trends across all nine 
provinces from 2023 to 2026, using real data from Statistics South Africa's 
Quarterly Labour Force Survey (QLFS). The goal is to identify key patterns across 
provinces, age groups, and education levels, and present findings in a clear, 
data-driven manner.

This project was built as a portfolio piece to demonstrate a full data analyst 
workflow — from raw data collection and cleaning, through to analysis, 
visualisation, and reporting.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning, summary tables, charts |
| Python (pandas, matplotlib) | Data analysis and visualisation |
| Microsoft Power BI | Interactive dashboard |
| Canva | Professional report design |

---
## 📂 Project Structure
SA_Unemployment/
│
├── data/
│   ├── SA_Unemployment_Final.xlsx      # Cleaned QLFS data (2023-2026)
│   └── SA_PowerBI_Data.xlsx            # Flat tables for Power BI
│
├── outputs/
│   ├── dashboard_screenshot.png        # Power BI dashboard screenshot
│   └── SA_Unemployment_Dashboard.pbix  # Power BI dashboard file
│
└── analysis.py                         # Python analysis script
---

## 📊 Key Findings

- Youth unemployment (15–24) stands at **60.9%** in Q1: 2026 — above 60% for the entire period
- **Eastern Cape** is the worst performing province at **44.6%**, up 5.3pp year-on-year
- **Western Cape** is the only province below 20% at **19.6%**
- Graduates face a **12.2%** unemployment rate vs **37.6%** for those without matric — a 25.4pp gap
- The NEET population grew from **3.68 million in 2023** to **3.89 million in 2026**
- The education gap has been **widening every year** since 2023

---

## 📈 Dashboard Preview

![Power BI Dashboard](outputs/dashboard_screenshot.png)

---

## 🔄 Data Analysis Process

| Phase | Tool | Description |
|-------|------|-------------|
| 1. Prepare | Excel | Extracted and structured QLFS data across 4 years |
| 2. Process | Excel | Cleaned, standardised and organised into flat tables |
| 3. Analyse | Python | Filtered and aggregated data to surface key trends |
| 4. Visualise | Python + Power BI | Built charts and interactive dashboard |
| 5. Share | Canva + GitHub | Documented findings in a professional report |

---

## 📁 Data Source

**Statistics South Africa — Quarterly Labour Force Survey (QLFS) P0211**

| Report | Period | Released |
|--------|--------|---------|
| QLFS Q1: 2023 | January – March 2023 | 2023 |
| QLFS Q1: 2024 | January – March 2024 | 2024 |
| QLFS Q1: 2025 | January – March 2025 | 2025 |
| QLFS Q1: 2026 | January – March 2026 | 12 May 2026 |

Available at: [www.statssa.gov.za](http://www.statssa.gov.za)

---

## 🚀 How to Run the Python Script

1. Clone this repository:
   git clone https://github.com/TshiamoMaise/SA-Unemployment-Analysis.git

2. Install dependencies:
   pip install pandas matplotlib seaborn openpyxl
   
3. Run the analysis:
   python analysis.py

   4. Charts will be saved automatically in the `outputs/` folder

---

## 📄 Report

A full written report documenting the data source, methodology, key findings, 
and recommendations is available as a PDF in this repository.

---

## 👤 Author

**Tshiamp Maise**  
Aspiring Data Analyst | South Africa  
📧 your.email@email.com  
🔗 [LinkedIn](www.linkedin.com/in/tshiamo-maise)

---

## 📜 License

This project is open source and available for educational purposes.  
Data sourced from Statistics South Africa — publicly available at www.statssa.gov.za
