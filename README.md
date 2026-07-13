# E-Commerce Sales Dashboard

An interactive Power BI dashboard analyzing e-commerce sales performance — built to turn raw transactional data into real-time, decision-ready business insights.

<img width="1314" height="735" alt="Dashboard" src="https://github.com/user-attachments/assets/16680111-88b8-4c68-ae08-261bfd2abb40" />



## Overview

This project transforms raw e-commerce sales data into a live, interactive Power BI dashboard, covering the full pipeline from data cleaning to business reporting:

- **$438K** in total revenue visualized across product lines
- **$37K** in profit tracked and broken down by category
- Real-time filtering via slicers and dynamic KPI cards

## Tech Stack

- **Power BI** — dashboard design and interactivity
- **DAX** — custom measures for KPIs (revenue, profit, and category-level metrics)
- **Power Query** — data cleaning and transformation within Power BI
- **Python (Jupyter Notebook)** — pre-processing and data cleaning (`data_cleaning.ipynb`)

## Repository Structure

| File | Description |
|---|---|
| `sales_dashboard.pbix` / `DASHBOARD.pbix` | Power BI dashboard file |
| `data_cleaning.ipynb` | Python notebook for cleaning and preparing the raw dataset |
| `cleaned_sales.csv` | Cleaned dataset used to build the dashboard |
| `train.csv` | Raw source sales data |
| `business_queries.sql` | SQL queries for business-side analysis |
| <img width="1314" height="735" alt="Dashboard" src="https://github.com/user-attachments/assets/69bf73f5-864a-4e6d-9dc0-d9ad4fa446a5" />
 | Dashboard screenshot |

## Key Features

- **KPI Cards** — at-a-glance revenue and profit tracking
- **Dynamic Charts** — visual breakdown of sales performance by product line
- **Slicers** — interactive filtering for real-time, drill-down analysis
- **DAX Measures** — custom calculations powering each KPI

## How to View

1. Clone or download this repository
2. Open `sales_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Explore the report using the built-in slicers and filters

## Data Pipeline

1. Raw sales data (`train.csv`) is cleaned and transformed using Python in `data_cleaning.ipynb`
2. Cleaned output (`cleaned_sales.csv`) is loaded into Power BI
3. Power Query handles further in-platform transformation
4. DAX measures calculate KPIs, which power the dashboard's visuals

## Author

**Meenakshi**
[GitHub](https://github.com/meenakship0805) · [LinkedIn](https://www.linkedin.com/in/meenakshi-pandey-82036a2aa/)
