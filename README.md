# 🏥 Healthcare Analytics Dashboard – Power BI

This Power BI dashboard provides a comprehensive overview of healthcare data, including billing, patient demographics, medical conditions, and clinical insights. It is designed for hospital administrators, data analysts, and healthcare professionals to monitor trends, track key metrics, and support data-driven decision-making.

## Key Features:

### Total Billing & Patient Overview
- Displays total billing amount and number of patients.
- Visualizes billing trends over the months.

### Patient Demographics
- Gender distribution with percentage split.
- Average patient age gauge.

### Test Results Summary
- Overview of test result categories (Normal, Abnormal, Inconclusive).

### Monthly Trends
- Tracks patient admissions and billing amounts monthly.

### Medical Condition Distribution
- Pie chart showing patient count by condition (e.g., Asthma, Cancer, Hypertension).

### Billing by Doctor
- Bar chart ranking doctors by total billing contribution.

## Data Cleaning & Preparation:

- **Duplicates identified and removed using Power Query:**
  - Open `Transform Data` > Right-click the table > `Remove Duplicates`
  - Based on `Name`, `Admission Type`, `Date of Admission`, etc.
- Data grouped and filtered to ensure consistency and accuracy.

## Data Fields Used:
- `Name`
- `Age`, `Gender`, `Average Age`
- `Date of Admission`, `Discharge Date`
- `Doctor`, `Medical Condition`, `Test Results`
- `Billing Amount`, `Total Billing`
- `Hospital`, `Insurance Provider`

## 🛠 Technologies:
- **Power BI Desktop** for dashboard creation and visualizations.
- **Power Query** for data transformation.
- **Excel** and **SQL** data sources (integrated).

## Suggested Dashboard Title:
- Healthcare Analytics Dashboard
- Clinical & Financial Overview of Patients

## Pages Included:
1. **Summarize** – High-level KPIs and visualizations.
2. **Insurance Provider** – Detailed breakdown by insurance.
3. **Patient Details** – Record-level insights.

   
## Screenshots

### Page 1: Dashboard Overview
![Page 1](https://github.com/Sricharan-A/Healthcare-Analytics-Dashboard/blob/main/page.1.jpeg)

### Page 2: Patient Insights
![Page 2](https://github.com/Sricharan-A/Healthcare-Analytics-Dashboard/blob/main/page.2.jpeg.png)

### Page 3: Medical Conditions Breakdown
![Page 3](https://github.com/Sricharan-A/Healthcare-Analytics-Dashboard/blob/main/page.3.png)


