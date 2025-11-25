# NHS Wales – Dashboard 4: Inpatient Flow
### README Documentation  
**Created by:** Soham S. Amburle  
**Date:** 20–24 November 2025

---

## 📘 Overview
The **Inpatient Flow Dashboard** provides a comprehensive view of inpatient activity and hospital capacity across **NHS Wales**.  
Built in **Power BI** using a synthetic dataset, this dashboard focuses on key inpatient metrics including **length of stay (LOS)**, **bed occupancy**, **discharge trends**, and **specialty-level inpatient workload**.

The dashboard supports operational leaders, hospital managers, and clinical teams by surfacing trends in bed utilisation, inpatient efficiency, and patient throughput.  
With several slicers and interactive visuals, users can explore inpatient dynamics by **admission type**, **specialty**, **bed type**, and **date range**, enabling data-driven decisions for capacity planning and service improvement.

---

## 📊 Dashboard Components

### **1. Slicers (Interactive Filters)**  
These slicers allow users to refine inpatient data across multiple operational dimensions:

- **Admission Type** – filters data by nature of admission (Elective, Non-Elective, Emergency)  
- **Specialty** – isolates results for specific clinical specialties  
- **Bed Type** – separates occupancy and LOS by bed category (e.g., General & Acute, ICU)  
- **Event Date** – enables time-based filtering for trends and seasonal analysis  

---

### **2. KPI Cards**
Instant at-a-glance indicators of inpatient performance and hospital efficiency:

- **AVG LOS (Days)** – average length of stay for inpatients  
- **Median LOS (Days)** – median length of stay, less sensitive to extreme outliers  
- **Avg. Bed Occupancy (%)** – overall average percentage of inpatient bed utilisation  
- **Total Discharges** – total number of inpatient discharges in the selected period  

---

### **3. Gauge**
- **Avg. Bed Occupancy (%)**  
  Provides a visual representation of occupancy relative to capacity thresholds, helping identify periods of operational pressure.

---

### **4. Average Waiting Days by Specialty (Clustered Column Chart)**  
Shows average inpatient waiting days across specialties, highlighting areas with higher waiting times and possible delays in inpatient pathways.

---

### **5. Patients by Waiting Time Band (Clustered Bar Chart)**  
Displays the distribution of inpatients across waiting-time ranges, helping identify long-wait cohorts and specialty-level bottlenecks.

---

### **6. Average Bed Occupancy Trend (Line Chart)**  
Time-series line chart illustrating how bed occupancy percentages change over time—useful for trend detection, capacity monitoring, and seasonal pattern analysis.

---

### **7. Number of Discharges by Year (Clustered Column Chart)**  
Shows annual discharge volumes, enabling comparisons of inpatient throughput year-over-year.

---

## 📌 Dashboard Story & Navigation
This dashboard is structured to offer a clear understanding of inpatient behaviour and hospital flow:

1. **Begin with the KPI Cards** to understand system-wide inpatient performance—LOS, occupancy, and discharge volume.  
2. **Use slicers** (Admission Type, Specialty, Bed Type) to explore inpatient activity across different service areas.  
3. **Evaluate waiting times** using specialty-level averages and waiting-time band distributions.  
4. **Monitor operational strain** through the Average Bed Occupancy gauge and line chart trends.  
5. **Review throughput** using year-wise discharge counts to understand changes in patient flow across time.

Together, these components provide a detailed, data-driven narrative of hospital inpatient pressure, inefficiency hotspots, and overall flow dynamics.

---

## 👤 Author
**Created by:** Soham S. Amburle  
**Date:** 20–24 November 2025
