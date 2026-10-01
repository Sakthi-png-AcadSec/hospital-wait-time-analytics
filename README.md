# Hospital Wait-Time Analytics

**Healthcare Operations Analytics | SQL Server | Power BI | Python | Machine Learning**

## Overview

This project analyzes hospital visit and waiting-time data to identify operational patterns, understand variations across doctor types and arrival hours, and support data-driven healthcare operations decisions.

The project combines SQL-based data analysis, a Power BI dashboard, Python-based data preparation, and a baseline machine-learning classification approach. It is designed as a portfolio project demonstrating analytical problem-solving and the translation of operational data into actionable business insights.

## Business Problem

Hospitals need visibility into patient flow and waiting-time patterns to identify periods that may require further operational investigation. Analyzing historical visit records can help operations teams understand demand patterns, compare waiting times, and identify opportunities for process improvement.

## Project Objectives

- Analyze waiting-time patterns by date, arrival hour, and doctor type.
- Create SQL tables, analytical views, and data-quality checks.
- Develop a Power BI dashboard for monitoring operational KPIs.
- Explore machine-learning approaches for waiting-time classification.
- Translate analytical findings into potential operational improvement opportunities.

## Tech Stack

- **SQL Server:** Database design, analytical queries, views, and data-quality checks.
- **Power BI:** KPI reporting, interactive visualization, and operational analysis.
- **Python:** Data preparation and machine-learning experiments.
- **Pandas:** Data cleaning and transformation.
- **Scikit-learn:** Baseline classification model evaluation.
- **Excel:** Aggregate data preparation and reporting.

## Key Analysis Areas

1. Waiting-time distribution and summary statistics.
2. Waiting-time patterns by arrival hour.
3. Comparison across doctor types.
4. Daily visit volumes and waiting-time trends.
5. Identification of visits exceeding defined waiting-time thresholds.
6. Baseline machine-learning model evaluation.

## Repository Structure

- `sql/` — Database schema, analytical views, and data-quality checks.
- `python/` — Data preparation and baseline model scripts.
- `powerbi/` — DAX measures, dashboard build guide, and preview.
- `data/derived_aggregates/` — Prepared aggregate datasets for reporting.
- `docs/` — Data dictionary and interpretation notes.

## How to Run

1. Install SQL Server and SQL Server Management Studio (SSMS).
2. Execute the SQL scripts in the order described in the project documentation.
3. Install the Python dependencies listed in `requirements.txt`.
4. Run the data-preparation script using your authorized local source dataset.
5. Open Power BI Desktop and import the prepared aggregate workbook or connect to the SQL views.
6. Create the report using the supplied DAX measures and dashboard build guide.
7. Validate dashboard calculations against the SQL results.

## Important Limitations

- The recorded waiting-time field must be interpreted according to the source dataset's definition; it may include more than queue time alone.
- Historical patterns do not establish the causes of waiting times.
- Machine-learning outputs are exploratory and require appropriate validation before operational use.
- Any estimated operational benefits should be treated as scenarios until measured in a real implementation.
- The project is an analytical prototype, not a deployed hospital information system or a clinically validated decision-support tool.

## Future Enhancements

- Add validated demand forecasting and waiting-time prediction.
- Introduce product requirements, user stories, and user acceptance tests.
- Develop a scenario-based business case for operational improvements.
- Extend the dashboard with additional validated operational metrics.
- Evaluate privacy, access-control, and integration requirements.

## Disclaimer

This is an educational and portfolio project. Findings are intended to demonstrate data analytics and business analysis methods and should not be interpreted as clinical recommendations.

## Author

**Sakthivel K**

Interests: Healthcare Analytics | Business Analysis | Product Strategy | Data-Driven Decision Making
