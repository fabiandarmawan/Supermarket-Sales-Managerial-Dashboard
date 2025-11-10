# Supermarket Sales Managerial Dashboard (Excel/Pivot Tables)

An interactive, single-sheet managerial dashboard built entirely in **Microsoft Excel** to track, analyze, and optimize key performance indicators (KPIs) for a retail supermarket.

## Project Goal
The primary objective of this project was to transform raw transactional sales data into a dynamic, user-friendly dashboard that provides a shop manager with real-time insights for strategic decision-making in inventory, pricing, and sales strategy.

## Key Features & Analysis
The dashboard uses **Pivot Tables**, **Pivot Charts**, and **Slicers** to enable quick analysis across various dimensions:

### Key Performance Indicators (KPIs)
The dashboard provides a high-level summary using the following critical metrics:
* **Total Revenue:** Gross sales value across all transactions.
* **Gross Profit:** The total profit generated (Total Selling Value - Total Buying Value).
* **Profit Margin %:** The percentage of revenue retained as profit (Profit / Total Revenue).
* **Total Transaction Volume:** The count of all sales records over the period.

### Core Analysis Sections
1.  **Sales & Profitability Trends:** Time-series charts showing monthly/annual trends for both Revenue and Profit.
2.  **Product Performance:** Ranked tables and charts identifying the **Top 5** and **Bottom 5** products and categories by Profit and Revenue.
3.  **Customer/Sales Channel Analysis:** Breakdown of performance by `SALE TYPE` (e.g., Direct Sales vs. Wholesaler) to inform targeted marketing efforts.
4.  **Operational Insights:** Analysis of payment modes (`PAYMENT MODE`) to understand transaction flow and speed.

## Skills Demonstrated
This project showcases proficiency in the entire data analysis pipeline using Excel:

* **Data Cleaning and Preparation:** Consolidated raw transactional data into a clean **Master Data** source, including calculated fields for `TOTAL SELLING VALUE` and `PROFIT`.
* **Data Modeling:** Established a single, reliable source table for all downstream analyses.
* **Pivot Tables & Pivot Charts:** Mastery of aggregating large datasets into meaningful summaries and visualizations.
* **Dynamic Dashboard Design:** Implementation of **Slicers** and **Report Connections** for instant filtering across all charts and KPIs.
* **KPI Calculation:** Defining and displaying crucial business metrics for executive review.

## Repository File Structure

| File Name | Description |
| :--- | :--- |
| `SUpermarket Shop Managerial Dashboard.xlsx` | The complete, interactive Excel dashboard file with all sheets (Dashboard, Master Data, Analysis). |
| `SUpermarket Shop Managerial Dashboard.xlsx - Input Data.csv` | The raw, initial transactional data before any cleaning or calculations. |
| `SUpermarket Shop Managerial Dashboard.xlsx - Master Data.csv` | The final, cleaned, and enhanced dataset used as the source for all pivot tables. |
| `SUpermarket Shop Managerial Dashboard.xlsx - Analysis.csv` | Contains the source Pivot Tables, calculated fields, and support data that feed the final dashboard charts. |
