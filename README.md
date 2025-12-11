<readme>
  <title>NHS Wales Healthcare Dashboard</title>
  <date>17 November, 2025 – Present</date>

  <section id="overview">
    <header>Project Overview</header>
    <paragraph>
      This project contains a suite of interactive Power BI dashboards analyzing NHS Wales healthcare data across key operational, clinical, and population health domains. It uses a synthetic dataset of 50,000 patient records modeled on NHS Wales service activity.
    </paragraph>

    <dashboardPages>
      <page number="1">Executive Summary – High-level KPIs and system overview</page>
      <page number="2">A&amp;E Performance – Emergency care flow, wait times, 4-hour compliance</page>
      <page number="3">Outpatient &amp; RTT – Waiting lists, elective performance, RTT metrics</page>
      <page number="4">Inpatient Flow – Bed occupancy, LOS, discharges, bottlenecks</page>
      <page number="5">Quality &amp; Safety – Mortality, readmissions, infections, safety indicators</page>
      <page number="6">Population Health – Demographics and patient characteristics</page>
      <page number="7">Finance &amp; Workforce – Costs, staffing, agency usage</page>
      <page number="8">Patient Drill-through – Individual patient journey exploration</page>
    </dashboardPages>
  </section>

  <section id="repository-structure">
    <header>Repository Structure</header>
    <structure>
      <folder name="data">
        <file>nhs_wales_synthetic.csv</file>
      </folder>

      <folder name="Dashboard_1_Executive_Summary"/>
      <folder name="Dashboard_2_AE_Performance"/>
      <folder name="Dashboard_3_Outpatients_RTT"/>
      <folder name="Dashboard_4_Inpatient_Flow"/>
      <folder name="Dashboard_5_Quality_Safety"/>
      <folder name="Dashboard_6_Population_Health"/>
      <folder name="Dashboard_7_Finance_Workforce"/>
      <folder name="Dashboard_8_Patient_Drillthrough"/>

      <folder name="dashboards">
        <file>NHS_Wales_Dashboard.pbix</file>
      </folder>

      <file name="README.md"/>
    </structure>
  </section>

  <section id="features">
    <header>Key Features</header>
    <feature>Interactive slicers for date, age, sex, health board, and specialty</feature>
    <feature>Executive KPI cards across domains</feature>
    <feature>Flow and trend visualizations</feature>
    <feature>Quality &amp; safety monitoring views</feature>
    <feature>Population segmentation and demographic analysis</feature>
    <feature>Patient-level drill-through exploration</feature>
    <feature>Conditional formatting aligned with NHS Wales targets</feature>
  </section>

  <section id="dataset">
    <header>Dataset</header>
    <file>nhs_wales_synthetic.csv</file>
    <recordCount>50000</recordCount>

    <fields>
      <category name="Demographics">
        <field>Age</field>
        <field>Sex</field>
        <field>WIMD quintile</field>
      </category>

      <category name="Activity">
        <field>Referral dates</field>
        <field>Attendance type</field>
        <field>Specialty</field>
      </category>

      <category name="Operational metrics">
        <field>A&amp;E wait times</field>
        <field>Bed occupancy</field>
        <field>Length of stay</field>
      </category>

      <category name="Clinical outcomes">
        <field>Mortality</field>
        <field>Readmissions</field>
        <field>Infections</field>
        <field>Comorbidities</field>
      </category>

      <category name="Finance &amp; workforce">
        <field>Cost of care</field>
        <field>Agency staffing usage</field>
      </category>
    </fields>

    <note>
      This dataset is synthetic and does not contain real patient information.
    </note>
  </section>

  <section id="usage">
    <header>How to Use</header>
    <steps>
      <step>Open the file NHS_Wales_Dashboard.pbix in Power BI Desktop.</step>
      <step>Ensure the dataset is located in the /data folder.</step>
      <step>Refresh data connections to load nhs_wales_synthetic.csv.</step>
      <step>Navigate through dashboard pages 1–8.</step>
      <step>Use slicers to explore performance by health board, demographics, dates, and specialties.</step>
    </steps>
  </section>
</readme>
