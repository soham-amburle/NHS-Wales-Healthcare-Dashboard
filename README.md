# NHS Wales Healthcare Dashboard  
*17 November 2025 – Present*

## 📌 Project Overview
This repository contains a suite of interactive **Power BI dashboards** designed to analyse key NHS Wales healthcare performance indicators.  
The dashboards are built using a **synthetic dataset of 50,000 patient records**, reflecting realistic patterns in emergency care, elective pathways, inpatient activities, quality outcomes, population characteristics, and workforce/finance metrics.

### Dashboard Pages
| Page | Name | Purpose |
|------|------|---------|
| **1** | Executive Summary | High-level KPIs |
| **2** | A&E Performance | Emergency care metrics |
| **3** | Outpatient & RTT | Waiting lists and elective flow |
| **4** | Inpatient Flow | Beds, LOS, discharges |
| **5** | Quality & Safety | Infection, mortality, readmissions |
| **6** | Population Health | Patient characteristics |
| **7** | Finance & Workforce | Cost and staffing |
| **8** | Patient Drill-through | Individual patient journey |

---

## 📁 Repository Structure

```text
NHS-Wales-Healthcare-Dashboard/
│
├── data/                               # Synthetic datasets (CSV/Excel)
│   └── nhs_wales_synthetic.csv
│
├── Dashboard_1_Executive_Summary/      # Page 1: Executive Summary
│
├── Dashboard_2_AE_Performance/         # Page 2: A&E Performance
│
├── Dashboard_3_Outpatients_RTT/        # Page 3: Outpatients & RTT
│
├── Dashboard_4_Inpatient_Flow/         # Page 4: Inpatient Flow
│
├── Dashboard_5_Quality_Safety/         # Page 5: Quality & Safety
│
├── Dashboard_6_Population_Health/      # Page 6: Population Health
│
├── Dashboard_7_Finance_Workforce/      # Page 7: Finance & Workforce
│
├── Dashboard_8_Patient_Drillthrough/   # Page 8: Patient-level journey drill-through
│
├── dashboards/                         # Master Power BI file(s)
│   └── NHS_Wales_Dashboard.pbix
│
└── README.md                           # Project overview & documentation

## ⭐ Key Features

- **Interactive Slicers:** Filter by date, age, gender, local health board, and specialty.  
- **KPI Cards:** Key metrics such as A&E attendances, 4-hour performance, RTT backlog, bed occupancy, LOS, mortality, and staffing utilisation.  
- **Trend & Time-Series Visuals:** Monthly and weekly performance tracking across pathways.  
- **Distribution Charts:** A&E wait times, LOS distributions, specialty-level RTT profiles.  
- **Drill-through & Tooltip Insights:** Patient-level journey pages and contextual mouse-hover insights.  
- **Conditional Formatting:** Target-driven highlighting across all major KPIs.  
- **Integrated Workforce & Finance Views:** Links operational pressures to staffing and cost.

---

## 🗂️ Dataset

- **File:** `nhs_wales_synthetic.csv`  
- **Records:** ~50,000 synthetic patient encounters  
- **Includes Fields For:**  
  - **Patient demographics** — age, sex, WIMD quintile  
  - **Admissions & activity** — specialty, admission type, referral dates, LOS  
  - **A&E metrics** — wait times, ambulance arrival & response  
  - **Clinical outcomes** — mortality, infection, readmission indicators  
  - **Operational metrics** — bed occupancy, pathway milestones  
  - **Finance & workforce** — cost-of-care, agency hours  

> ⚠️ **Important:** The dataset is **fully synthetic**. No real patient data is included.  
> It is designed solely for **analytics, training, and dashboard development**.

---

## 🚀 How to Use

1. Open **Power BI Desktop**.  
2. Load the main file:  
dashboards/NHS_Wales_Dashboard.pbix

sql
Copy code
3. When prompted, connect the dataset from:  
data/nhs_wales_synthetic.csv

yaml
Copy code
4. Use slicers to explore data by board, specialty, demographics, and timeframe.  
5. Navigate through the dashboard pages (1–8) via the Power BI navigation sidebar.  
6. Use drill-through features to inspect individual patient journeys.

---

## 📬 Feedback & Contributions

Feel free to open issues or submit pull requests to improve:  
- Dashboard structure  
- Visualisation optimisation  
- Data modelling  
- Folder organisation  
- Documentation

---


