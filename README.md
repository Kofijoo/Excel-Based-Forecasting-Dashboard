# Excel-Based Forecasting Dashboard

A dynamic and scalable Excel tool designed to optimize software license allocation and forecast spend across multiple business units. This project empowers teams to make data-driven decisions by visualizing allocation plans, usage efficiency, and cost forecasts in real time.

---

## Project Overview

Organizations often face challenges in managing and forecasting software licensing costs, especially across departments with different usage patterns. This Excel-based dashboard solves that by integrating allocation data, usage insights, and cost metrics into an interactive and transparent forecasting system.

---

## Key Features

- **Interactive PivotTables**  
  Analyze license allocation and forecasted costs by business unit and license type.

- **Scenario Customization**  
  Simulate allocation plans using filters like month, BU, and license limits.

- **Built-in Cost Analytics**  
  Forecast cost per license and per active user using real usage percentages.

- **Utilization Flags**  
  Auto-detect underutilized licenses via conditional formatting logic.

- **Buffer Analysis**  
  Track over- or under-provisioned plans using buffer thresholds.

- **Dynamic Dashboard**  
  Visual summary using stacked columns, line charts, bar charts, and donut charts.

---

## Workbook Structure

| Sheet Name        | Purpose                                      |
|------------------|----------------------------------------------|
| `Input`           | Raw data imports or configuration (if any)   |
| `LicenseCatalog`  | License catalog metadata                     |
| `BU_Headcount`    | Business unit headcount data                |
| `UsageData`       | License usage % per product                  |
| `AllocationPlan`  | Main allocation planner + forecast model     |
| `Dashboard`       | Visual analytics and summary KPIs           |
| `ForecastPeriods` | Monthly time period selections               |

---

## Metrics & Visuals

- **Total Forecasted Cost**
- **Total Allocated Licenses**
- **Average Cost per Active User**
- **License Count > $30/User**
- **Over-Provisioning Alerts**
- **Visual Charts:**
  - Stacked Column: Forecasted Cost by BU
  - Line Chart: Buffer % by BU
  - Bar Chart: Cost per Active User
  - Donut Chart: Utilization Status

---

## Business Impact

- **Reduced manual reporting time** by 70%  
- **Improved decision-making** across 5 business units  
- **Increased forecasting accuracy and confidence**  
- **30% increase in licensing decision efficiency**

---

## How to Use

1. Update the `UsageData` and `BU_Headcount` sheets.
2. Adjust the `AllocationPlan` for new months or licenses.
3. Review updated costs and utilization alerts.
4. Use the `Dashboard` to present KPIs to stakeholders.

---

## Author

**[Joshua Agyekum]** – Data Analyst & Excel Automation Specialist  
[https://www.linkedin.com/in/joshua-agyekum/]  
[https://kofijoo.github.io/]

---

## 📃 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
