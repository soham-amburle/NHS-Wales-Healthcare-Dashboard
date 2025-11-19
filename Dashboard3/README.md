# NHS Wales – Dashboard 3: Outpatients & Elective Pathway (Referral to Treatment, RTT)
### README Documentation  
**Created by:** Soham S. Amburle  
**Date:** 19 November 2025

---

## 📘 Overview
The **Outpatients & Elective Pathway Dashboard** provides a detailed analysis of patient flow through the **Referral to Treatment (RTT)** pathway across **NHS Wales**.  
Built in **Power BI** using a synthetic dataset, this dashboard highlights key metrics such as total referrals, waiting times, compliance with RTT targets, and specialty-level backlog analysis.

The dashboard is designed to support healthcare managers and decision makers by visualizing bottlenecks, monitoring performance, and identifying priority areas for intervention.  
Interactive filters and slicers allow users to explore data by specialty, pathway stage, and patient characteristics.

---

## 📊 Dashboard Components

### **1. Cards (KPI Indicators)**
These cards provide an instant snapshot of pathway performance:

- **Total Referrals** – total number of patients referred into outpatient or elective pathways  
- **Patients Waiting >26 Weeks** – number of patients exceeding the 26-week RTT target  
- **Patients Waiting >52 Weeks** – number of patients exceeding the 52-week threshold  
- **Patients Treated Within 26 Weeks (Gauge)** – percentage of patients treated on time  

- **Total Patients Treated** – count of completed treatments  
- **Average Waiting Days** – average days between referral and treatment  
- **Longest Wait (Gauge)** – maximum waiting time recorded  

---

### **2. Slicer (Interactive Filter)**

- **Specialty** – allows users to filter visuals by clinical specialty (e.g., Orthopaedics, Ophthalmology, ENT, etc.)

---

### **3. Charts / Visualizations**

- **Average Waiting Days by Specialty (Clustered Bar Chart)**  
  Compares the mean waiting days across specialties to identify slower pathways and bottlenecks.

- **Patients by Waiting Time Band (Stacked Column Chart)**  
  Shows the distribution of patients across RTT waiting time bands (0–26 weeks, 26–52 weeks, 52–104 weeks, 104+ weeks) per specialty.

- **Referral to Treatment Funnel**  
  Visualizes patient flow from referral → waiting → treatment, highlighting drop-offs and delays in the pathway.

---

## 📌 Dashboard Story & Navigation
This dashboard tells a clear story about outpatient and elective pathway performance:

1. **Start with the top-level KPIs** (Total Referrals, Patients Waiting >26/52 Weeks, Patients Treated Within 26 Weeks) to understand demand and backlog.  
2. **Use the Specialty slicer** to focus on particular clinical areas.  
3. **Analyze efficiency and bottlenecks** with Average Waiting Days and Longest Wait.  
4. **Compare specialties** using the clustered bar chart and stacked column chart to prioritize resource allocation.  
5. **Follow the Referral to Treatment Funnel** to see how patients progress through the pathway and where delays occur.

This structure supports decision makers in identifying high-priority specialties, monitoring RTT compliance, and targeting interventions to reduce delays.

---

## 👤 Author
**Created by:** Soham S. Amburle  
**Date:** 19 November 2025
