# 📊 Interactive Sales Dashboard

> Replacing static monthly reports with self-service regional sales analytics — built in Power BI with drill-down filters across 6+ regions.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat)

---

## 📌 Project Overview

Regional sales teams were relying on static monthly reports that required analyst involvement every time a manager wanted to compare performance. This project replaces that workflow with a fully **interactive, self-service Power BI dashboard** that lets regional managers explore data independently — without waiting on anyone.

Built during my Data Analyst internship at **HackVeda**, this dashboard covers profit margin, average sales, and regional performance across 6+ regions with drill-down capability by region and product category.

---

## 🎯 Problem Statement

| Before | After |
|---|---|
| Static monthly PDF/Excel reports | Live interactive Power BI dashboard |
| Analyst required for every query | Managers explore data independently |
| No drill-down capability | Drill-down by region and product category |
| Delayed insights | Real-time performance visibility |

---

## 📊 Dashboard Features

| Feature | Details |
|---|---|
| KPI Tracking | Profit margin and average sales across all regions |
| Regional Comparison | Side-by-side performance view across 6+ regions |
| Product Category Breakdown | Filter by category to spot underperformers |
| Drill-down Filters | Interactive slicers for region, category, and time period |
| Underperformance Surfacing | Automatically highlights regions below target |

---

## 🔍 Methodology

1. **Data Ingestion** — Imported raw sales data from Excel/CSV into Power BI
2. **Data Cleaning** — Handled nulls, duplicates, and inconsistent region labels using Power Query
3. **Data Modelling** — Built relationships between sales, region, and product category tables
4. **DAX Measures** — Created calculated measures for profit margin %, average sales, and YoY comparisons
5. **Dashboard Design** — Designed drill-down views with slicers, bar charts, maps, and KPI cards
6. **Delivery** — Presented to supervisors with clear recommendations on underperforming regions

---

## 💡 Business Impact

- Regional managers can now **independently compare performance** by region and product category
- Eliminated analyst bottleneck — insights available on demand, not on a monthly schedule
- Surfaced underperforming areas without manual investigation, enabling faster corrective action
- Replaced static reports across **6+ regions** with a single source of truth

---

## 🛠️ Tech Stack

- **Power BI** — Primary dashboard and visualisation tool
- **DAX** — Calculated measures for KPIs, margins, and aggregations
- **Power Query (M)** — Data cleaning and transformation
- **Excel / CSV** — Source data format
- **Tableau** — Secondary visualisation (comparative analysis)

---

## 📁 Repository Structure

```
sales-dashboard/
│
├── data/
│   └── sales_data.csv                 # Cleaned sales dataset
│
├── dashboard/
│   ├── sales_dashboard.pbix           # Power BI dashboard file
│   └── screenshots/
│       ├── overview.png               # Dashboard overview
│       ├── regional_breakdown.png     # Regional comparison view
│       └── product_category.png      # Category drill-down view
│
├── insights/
│   └── regional_insights.md          # Key findings and recommendations
│
└── README.md
```

---

## 🚀 How to View the Dashboard

1. Download the `.pbix` file from the `dashboard/` folder
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers to filter by region, product category, and time period

> No coding required — just Power BI Desktop installed on your machine.

---

## 👤 Author

**Kartik Divte**
📧 kartikdivte@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/kartikdivte/)
