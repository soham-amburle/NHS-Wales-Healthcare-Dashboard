# NHS Wales – Dashboard 8: Patient Drill-Through

## README Documentation

**Created by:** Soham S. Amburle
**Date:** 12–15 December 2025

---

## 📘 Overview

The Patient Drill-Through Dashboard provides a comprehensive, patient-level view of an individual’s healthcare journey across NHS Wales. Developed in Power BI using a synthetic dataset, the dashboard brings together patient demographics, socioeconomic risk factors, clinical complexity, care events, and outcomes in a single, integrated view. It supports detailed clinical review, quality and safety investigations, and operational analysis by presenting both event-level data and high-level indicators of patient outcomes and trajectory over time.

## 📊 Dashboard Components

### 1. Patient Snapshot & Risk Profile (KPI Cards)

These KPI cards provide immediate context about the patient’s background and clinical risk, ensuring that care events and outcomes are interpreted appropriately.

* **Patient ID** – uniquely identifies the patient being reviewed.
* **Age** – displays the patient’s age at the time of analysis.
* **Gender** – shows the patient’s recorded sex.
* **Local Health Board** – indicates the responsible NHS Wales health board.
* **Deprivation** – summarises the patient’s socioeconomic deprivation status.
* **WIMD Quintile** – places the patient within the Welsh Index of Multiple Deprivation (1 = most deprived, 5 = least deprived).
* **Comorbidity Count** – shows the number of recorded long-term conditions, indicating clinical complexity.
* **Smoking Status** – highlights lifestyle-related risk factors.
* **Flu Vaccination** – indicates whether the patient has received a flu vaccination, supporting preventative care assessment.

### 2. Patient Care Journey (Timeline Table)

* **Patient Timeline Table** – presents a chronological, event-level record of the patient’s interactions with healthcare services. Includes admission type, specialty, A&E wait times, length of stay, waiting list duration, treatment dates, and discharge dates. This table forms the factual backbone of the patient journey and supports auditability and clinical review.

### 3. Clinical Outcomes & Safety (Outcome Cards)

These indicators summarise key outcomes and safety-related events associated with the patient’s care.

* **Readmitted Within 30 Days** – flags unplanned readmissions, a key quality-of-care metric.
* **Mortality** – indicates whether the patient died, supporting outcome monitoring and case review.
* **Infection** – shows whether a healthcare-associated infection occurred.
* **Infection Type** – displays the recorded type of infection, where applicable.
* **Bed Type** – identifies the level of care required (e.g., general ward or higher acuity).
* **Bed Occupancy Percentage** – provides operational context by indicating capacity pressure associated with the patient’s bed usage.

### 4. Patient Trajectory Over Time (Scatter Plot)

* **Patient Length of Stay by Event (Scatter Plot)** – visualises length of stay across successive patient events, enabling identification of patterns, escalation, or improvement in hospital utilisation over time. Differentiation by admission type supports comparison between emergency and elective care episodes.

## 📌 Summary

The Patient Drill-Through Dashboard delivers a holistic, patient-centred view of healthcare delivery and outcomes across NHS Wales. By combining demographic and risk context, detailed care events, outcome indicators, and a visual representation of patient trajectory, the dashboard enables:

* Structured clinical and multidisciplinary team (MDT) review
* Quality and safety investigations
* Analysis of frequent attenders and long-stay patients
* Informed operational and service improvement discussions

**Created by:** Soham S. Amburle
**Date:** 12–15 December 2025
