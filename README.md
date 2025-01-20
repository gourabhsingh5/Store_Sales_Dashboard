# SuperStore Sales Dashboard

## Overview

The **SuperStore Sales Dashboard** is an interactive, data-driven visualization project aimed at uncovering key business insights from the SuperStore dataset. The dashboard provides a comprehensive analysis of sales, profits, and customer behavior across multiple dimensions, including region, segment, category, and more. By leveraging Power BI, this project focuses on answering critical business questions, identifying growth opportunities, and assisting stakeholders in making data-backed decisions.

This repository contains:
- The dataset used for analysis.
- Screenshots of the Power BI dashboards.
- Insights derived from the data visualizations.
- Instructions to replicate the project.

---

## Dataset Details

The dataset used in this project represents transactional data for SuperStore, including sales, profit, and customer-related details.

**Key Features of the Dataset**:
- **Number of Records**: 9,994 rows.
- **Columns**:
  - `Order Date`, `Ship Date`, `Region`, `Segment`, `Ship Mode`, `Category`, `Sub-Category`, etc.
  - Metrics: `Sales`, `Profit`, `Discount`, `Quantity`, `Shipping Cost`.
- **Time Period Covered**: 2019 to January 2021.
- **Data Source**: Publicly available SuperStore dataset.
- ## Dataset used
- <a href="https://github.com/gourabhsingh5/Store_Sales_Dashboard/blob/main/SuperStore_Sales_Dataset.csv">Dataset</a>

---

## Dashboards and Insights

- Dashboard Interaction <a href="https://github.com/gourabhsingh5/Store_Sales_Dashboard/blob/main/Screenshot%202025-01-21%20021840.png">View Dashboard</a>
- Dashboard Interaction for Sales Forecast <a href="https://github.com/gourabhsingh5/Store_Sales_Dashboard/blob/main/Screenshot%202025-01-21%20021858.png">View Dashboard</a>

### 1. **SuperStore Sales Dashboard** (Primary)

#### Key Metrics:
- **Total Sales**: $252,000
- **Total Quantity Sold**: 3,529
- **Total Profit**: $27,000
- **Average Shipping Days**: 4 days

---

#### Insights:

##### **Sales by Segment**:
- **Consumers** contribute the largest share of sales (54%), followed by **Corporate** (30%) and **Home Office** (17%).
- **Actionable Insight**: Focus marketing campaigns on Consumers to maintain growth while exploring opportunities to increase Corporate and Home Office sales.

##### **Sales by Region**:
- **Actionable Insight**: Investigate why other regions are not reflected in this view or explore further regional performance.

##### **Sales by Payment Mode**:
- **Cash on Delivery (COD)** is the most popular payment method, accounting for 44% of sales, followed by **Online Payments** (37%).
- **Actionable Insight**: Promote alternate payment methods like Cards (19%) through loyalty programs or discounts.

---

##### **Monthly Sales Year-over-Year (YoY)**:
- Clear seasonal trends are visible, with significant spikes in November and December.
- **Actionable Insight**: Allocate additional resources and inventory to meet seasonal demand during holiday months.

##### **Sales by Sub-Category**:
- **Phones** lead with $36K in sales, followed by **Tables** ($26K) and **Storage** ($26K).
- **Actionable Insight**: Increase inventory for top-performing sub-categories and explore cross-selling opportunities.

##### **Sales by Ship Mode**:
- **Standard Class** dominates shipping preferences (48% of sales), followed by **Second Class** (21%).
- **Actionable Insight**: Optimize Standard Class shipping processes to reduce delivery times and costs.

##### **Geographical Analysis**:
- The map visualization highlights **Sales and Profit by State**, with states like California and New York contributing significantly.
- **Actionable Insight**: Expand marketing efforts and distribution channels in underperforming states to balance revenue distribution.

---

### 2. **Sales Forecast Dashboard** (Predictive Analysis)

#### Key Metrics:
- **Sales Forecast for 15 Days**:
  - Predictive models forecast upcoming sales trends using historical data.
  - **Actionable Insight**: Utilize forecasts to optimize inventory, staffing, and resource allocation.

#### Insights:

##### **Sales Trends Over Time**:
- Historical sales trends show regular spikes around holiday seasons and promotional events.
- **Actionable Insight**: Design promotional campaigns that align with historical spikes in sales.

##### **Sales by State**:
- **California** leads with $0.34M in sales, followed by **New York** ($0.19M) and **Texas** ($0.12M).
- **Actionable Insight**: Replicate the sales strategies of top-performing states in lower-performing regions.

---

## Tools and Technologies Used

- **Power BI**: For data visualization and dashboard creation.
- **Microsoft Excel**: For data preprocessing and cleaning.
- **Python (Optional)**: For advanced analytics and predictive modeling.
- **GitHub**: For project documentation and version control.

---
