# NHS Wales Healthcare Dashboard
17 November, 2025 - Present

## Project Overview
This project contains interactive **Power BI dashboards** analyzing NHS Wales healthcare data. The dashboards focus on key performance areas including:

- **A&E Performance** (attendances, wait times, 4-hour compliance, ambulance response)  
- **Outpatient & RTT** (waiting times, elective care, referral-to-treatment targets)  
- **Inpatient Flow** (bed occupancy, length of stay, discharge trends)  
- **Quality & Safety** (infection rates, readmissions, mortality)  
- **Population Health** (demographics, comorbidities, vaccination uptake)  
- **Finance & Workforce** (costs, agency staffing)

The dashboards use a **synthetic dataset** of 50,000 patient records based on NHS Wales service data, suitable for testing and analysis purposes.

---

## Repository Structure

```text
NHS-Wales-Healthcare-Dashboard/
│
├── data/                             # Synthetic datasets (CSV/Excel)
│   └── nhs_wales_synthetic.csv
│
├── Dashboard_1_Executive_Summary/       # Dashboard 1: Exec Summary
│  
├── Dashboard_2_AE_Performance/       # Dashboard 1: A&E Performance
│  
├── Dashboard_3_Outpatients_RTT/      # Dashboard 2: Outpatient & RTT
│   
├── Dashboard_4_Inpatient_Flow/       # Dashboard 3: Inpatient Flow
│
├── Dashboard_5_Quality_Safety/       # Dashboard 4: Quality & Safety
│
├── Dashboard_6_Population_Finance/  # Dashboard 5: Population Health & Finance
│
├── dashboards/                       # Master Power BI files
│   └── NHS_Wales_Dashboard.pbix
│
└── README.md                         # Project overview, instructions, and repo info
```
---

## Key Features

- **Interactive Slicers:** Filter by date, age, gender, local health board, and specialty.  
- **KPIs & Cards:** Total attendances, average wait times, % seen within 4 hours, ambulance callouts, conversion rates.  
- **Line Charts & Trends:** Track A&E attendances and ambulance response times over time.  
- **Histograms:** Distribution of A&E wait times to identify bottlenecks.  
- **Tooltips & Drill-through:** Hover details for patient demographics and care metrics.  
- **Conditional Formatting:** Visual cues for KPIs to highlight performance against targets.

---

## Dataset

- **File:** `nhs_wales_synthetic.csv`  
- **Records:** 50,000 synthetic patient encounters  
- **Columns Include:**  
  - Patient demographics (age, sex, WIMD quintile)  
  - Admission details (type, specialty, event/referral dates, length of stay)  
  - Clinical outcomes (mortality, readmissions, infections, comorbidities)  
  - Operational metrics (A&E wait minutes, ambulance callouts/response, bed occupancy)  
  - Finance & staffing (cost of care, agency staff usage)  

> Note: This dataset is **synthetic** and does not contain real patient data. It is intended for **dashboard testing and analysis practice**.

---

## How to Use

1. Open `NHS_Wales_Dashboard.pbix` in **Power BI Desktop**.  
2. Load the synthetic dataset from `data/nhs_wales_synthetic.csv`.  
3. Use slicers to filter by date, demographics, or health board.  
4. Explore KPIs, charts, and interactive visuals on each dashboard page:  
   - **A&E Performance**  
   - **Outpatient & RTT**  
   - **Inpatient Flow**  
   - **Quality & Safety**  
   - **Population Health**  
   - **Finance & Workforce**  

---
