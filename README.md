# NHS Wales Healthcare Dashboard
**Project Duration:** 17 November 2025 – Present

## Project Overview
This project contains interactive **Power BI dashboards** analyzing healthcare data across **NHS Wales**. The dashboards focus on key performance areas including:

- **A&E Performance** – attendances, wait times, 4-hour compliance, ambulance response.  
- **Outpatient & RTT** – elective care, referral-to-treatment pathway, waiting times, backlog.  
- **Inpatient Flow** – bed occupancy, length of stay (LOS), discharge trends, waiting times.  
- **Quality & Safety** – infection rates, mortality, 30-day readmissions, specialty-level safety.  
- **Population Health** – demographics, comorbidities, vaccination uptake, deprivation.  
- **Finance & Workforce** – costs, agency staffing, operational resource utilization.  
- **Patient Drill-Through** – individual patient journey, events, outcomes, trajectory over time.

The dashboards use a **synthetic dataset** of 50,000 patient records based on NHS Wales service data, suitable for testing and analysis purposes.

---

## Dashboard Pages

| Dashboard | Name                  | Purpose & Details | Date |
|-----------|----------------------|-----------------|------|
| 1         | Executive Summary     | High-level KPIs across services for quick operational and strategic overview. | N/A |
| 2         | A&E Performance       | Emergency care metrics: attendances, average wait times, % seen within 4 hours, ambulance callouts, conversion rates. | 17–18 Nov 2025 |
| 3         | Outpatients & RTT     | Elective pathway analysis: total referrals, patients waiting >26/52 weeks, average waiting days, RTT funnel, specialty-level backlog. | 19 Nov 2025 |
| 4         | Inpatient Flow        | Hospital capacity and patient flow: bed occupancy, average & median LOS, discharges, waiting time bands, specialty-specific throughput. | 20–24 Nov 2025 |
| 5         | Quality & Safety      | Clinical outcomes: MRSA/C. Diff/overall infection rates, mortality, readmissions within 30 days, infections by specialty. | 25–28 Nov 2025 |
| 6         | Population Health     | Demographics & risk factors: age distribution, sex, comorbidities, smoking status, WIMD quintiles, flu vaccination uptake. | 29 Nov – 04 Dec 2025 |
| 7         | Finance & Workforce   | Operational and financial metrics: total cost of care, average cost per encounter, agency staff usage, cost per bed day, bed occupancy, length of stay. | 09 Dec 2025 |
| 8         | Patient Drill-Through | Patient-level journey: chronological care events, outcomes, length of stay scatter plot, KPI cards for risk and clinical context. | 12–15 Dec 2025 |

---

## Repository Structure

```text
NHS-Wales-Healthcare-Dashboard/
│
├── data/                             # Synthetic dataset
│   └── nhs_wales_synthetic.csv
│
├── Dashboard2/                        # Dashboard 2: A&E Performance
│   ├── Dashboard2.png                  # Dashboard image
│   ├── Dashboard2_Details.md           # Detailed documentation
│   └── README.md                       # Dashboard-specific readme
│
├── Dashboard3/                        # Dashboard 3: Outpatients & RTT
│   ├── Dashboard3.png
│   ├── Dashboard3_Details.md
│   └── README.md
│
├── Dashboard4/                        # Dashboard 4: Inpatient Flow
│   ├── Dashboard4.png
│   ├── Dashboard4_Details.md
│   └── README.md
│
├── Dashboard5/                        # Dashboard 5: Quality & Safety
│   ├── Dashboard5.png
│   ├── Dashboard5_Details.md
│   └── README.md
│
├── Dashboard6/                        # Dashboard 6: Population Health
│   ├── Dashboard6.png
│   ├── Dashboard6_Details.md
│   └── README.md
│
├── Dashboard7/                        # Dashboard 7: Finance & Workforce
│   ├── Dashboard7.png
│   ├── Dashboard7_Details.md
│   └── README.md
│
├── Dashboard8/                        # Dashboard 8: Patient Drill-Through
│   ├── Dashboard8.png
│   ├── Dashboard8_Details.md
│   └── README.md
│
└── README.md                          # Project overview, instructions, and repo info
```
test
