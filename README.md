# Supermarket Sales Managerial Dashboard (Excel/Pivot Tables)

A single-sheet managerial dashboard engineered within **Microsoft Excel**, designed to facilitate interactive, key performance indicator (KPI) driven analysis of retail supermarket sales performance.

---

## Project Context and Data Provenance

The underlying dataset utilized for this exercise constitutes **synthetic** (non-production) transactional records, procured from a public data analysis challenge.

The core objective of this initiative is to furnish demonstrable evidence of robust technical proficiency throughout the entirety of the data analysis and visualization pipeline:

1.  **Data Structuring:** The methodological process of transforming disparate raw transactional inputs into a clean, calculated **Master Data** table.
2.  **Data Modeling:** The application of advanced **Pivot Tables** to achieve effective data aggregation and multi-dimensional statistical summarization.
3.  **Visualization Design:** The engineering of a dynamic dashboard interface utilizing interconnected **Slicers** and **Pivot Charts** for enhanced data interaction.

---

## Analytical Outputs and Key Performance Metrics

The dashboard architecture is fundamentally constructed to address critical business inquiries pertaining to profitability, inventory management, and operational efficiency.

### Key Performance Indicators (KPIs)

The primary performance indicators are prominently featured to support swift executive assessment and decision-making:

* **Total Revenue**
* **Gross Profit**
* **Profit Margin %:** A crucial metric for evaluating the effectiveness of operational cost management.
* **Total Transaction Volume:** The aggregate count of all sales records over the specified period.

### Core Analysis Sections

| Analysis Focus | Visualization Method | Business Application |
| :--- | :--- | :--- |
| **Profitability Trends** | Time-series charts (Lines/Area) | Monitors fluctuations in monthly and annual Revenue and Profit streams. |
| **Product Performance** | Ranked Bar/Column Charts | Establishes the performance rank of products and categories by Profit to inform inventory and strategic procurement. |
| **Sales Channel Efficacy** | Breakdown Tables | Provides comparative performance analysis across distinct sales types (e.g., Direct Sales versus Wholesaler transactions). |
| **Operational Efficiency** | Distribution Charts | Executes analysis of payment methods (`PAYMENT METHODS`) to assess transaction processing speed and resource allocation. |

---

## Technical Competencies Demonstrated

* **Data Cleaning & Preparation:** Implementation of calculated fields (`PROFIT`, `PROFIT MARGIN`) and meticulous consolidation of raw data to ensure Pivot Table readiness.
* **Data Modeling:** Establishment of a singular, reliable `Master Data` source to maintain data integrity across all reporting elements.
* **Pivot Table & Pivot Chart Generation:** Expertise in multi-variable data aggregation, statistical summary, and visual representation.
* **Dynamic Design:** Demonstrated competence in utilizing **Slicers** and **Report Connections** to create instantaneous, cross-functional filtering.
* **Data Visualization:** Strategic selection and customization of chart types for maximum clarity and analytical insight dissemination.

## Repository File Structure

| File Name | Purpose |
| :--- | :--- |
| `Supermarket Sop Managerial Dashboard.xlsx` | The comprehensive, interactive Microsoft Excel workbook containing the final dashboard, all pivot tables, and the calculation engine. |
| `Input Data.csv` | The raw, original transactional sales data exported in CSV format. |
| `Master Data.csv` | The cleaned, enhanced, and modeled dataset, serving as the definitive source for all dashboard components. |
| `Analysis.xlsx` | Supporting data extracted from the analysis sheet, containing pivot tables and calculation outputs. |
