# AtliQ Hardware Sales & Finance Analytics Report

This project is a **complete end-to-end Sales & Finance Analytics solution** built in **Excel with Power Query, Power Pivot, and DAX**, focused on analyzing the performance of **AtliQ Hardware** across customers and markets from **2019 to 2021**.

## Project Objective

To design interactive, user-friendly reports that enable Atliq Hardware's leadership to:
- Assess **customer performance** over three years.
- Evaluate **market (country-level) performance**.
- Compare **actual sales vs. targets** for strategic decision-making.
- Identify growth opportunities and underperforming areas.

---

## Data Sources
The analysis integrates multiple datasets:
| File Name               | Description                      |
|-------------------------|----------------------------------|
| `dim_customer.xlsx`     | Customer details and regions    |
| `dim_market.xlsx`       | Country-level market data       |
| `dim_product.xlsx`      | Product and division details    |
| `fact_sales_monthly.xlsx` | Monthly sales transactions     |
| `ns_targets_2021.xlsx`  | 2021 market-wise sales targets  |

---

## Solution Architecture

### ETL (Extract, Transform, Load)
- Imported and cleaned data using **Power Query**.
- Corrected errors (like spelling mistakes in market names).
- Added a custom **Date Dimension Table** to handle fiscal years and time intelligence.

### Data Modeling
- Created a **star schema** connecting fact and dimension tables.
- Established relationships to enable seamless filtering and analysis.

### DAX Measures
- Developed key measures like:
  - `net_sales`
  - `net_sales_2019`, `net_sales_2020`, `net_sales_2021`
  - YoY Growth (`2021 vs 2020`)
  - Sales Target Variance and % (`2021 - Target`, `2021 - Target %`)

---

## Reports Created

### **Customer Performance Report**
Displays customer-wise net sales across 2019–2021 with **YoY growth** analysis between 2020 and 2021.  
**Filters:** Region, Market, Division.  
**Highlights:** Conditional formatting, readable design, dynamic insights.

### **Market Performance Report**
Evaluates **country-level sales performance**, comparing actual sales against **2021 targets** and calculating variances.  
**Filters:** Region, Market.  
**Highlights:** Detects over/under-performing markets and guides resource allocation.

---

## Key Features
- Scalable Data Model.
- Accurate YoY and target-based analytics.
- User-centric report design for clarity and actionability.
- Dynamic date handling with fiscal year support.
- Professional number formatting (K/M/B auto-formatting).

---

## Tech Stack
- **Excel (Power Query, Power Pivot, DAX)**
- **Pivot Tables & Charts**
- **Data Modeling & Relationships**
- **ETL and Data Cleaning**
