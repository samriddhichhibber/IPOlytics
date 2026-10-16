# IPOlytics — IPO Performance & Financial Analytics Dashboard

**IPOlytics** is a financial analytics project designed to explore India's Initial Public Offering (IPO) market using SQL and Power BI. It combines structured data management, SQL-based analysis, and interactive visualizations to help users examine IPO performance and identify patterns across the market.

## Overview

The project focuses on transforming raw IPO data into meaningful financial insights through data cleaning, analytical SQL queries, and an interactive Power BI dashboard.

### Key Features

- **Data Cleaning:** Prepare and clean IPO data for reliable analysis.
- **Database Design:** Define database schemas and organize structured financial data.
- **SQL Analytics:** Use business-oriented queries to analyze IPO market data.
- **Views & Stored Procedures:** Organize reusable analytical logic within the database.
- **Query Optimization:** Use indexes to support efficient data retrieval.
- **Interactive Dashboard:** Explore IPO data and performance through Power BI visualizations.

## Tech Stack

| Technology | Purpose |
|---|---|
| SQL | Data cleaning, database management, and analytical queries |
| Microsoft Power BI | Interactive dashboard and data visualization |
| Microsoft Excel | Dataset storage and data preparation |

## Project Structure

```text
IPOlytics/
├── 01_schema.sql
├── 02_business_queries.sql
├── 03_views.sql
├── 04_procedures.sql
├── 05_indexes.sql
├── 06_data_cleaning.sql
├── IndianIpoAnalysis.pbix
├── Initial Public Offering (Updated).xlsx
├── validation_report.md
├── README.md
└── LICENSE
```

## Analytical Workflow

1. **Data Preparation:** Inspect and clean the source IPO dataset.
2. **Schema Design:** Define the database structure for organized data management.
3. **SQL Analysis:** Execute analytical queries to explore IPO-related business questions.
4. **Reusable Logic:** Create views and stored procedures for repeatable operations.
5. **Performance Optimization:** Apply indexes where appropriate to improve query efficiency.
6. **Dashboard Development:** Connect the prepared data to Power BI and present the analysis visually.

## Getting Started

### Prerequisites

- Microsoft Excel
- A SQL database engine compatible with the project's SQL scripts
- Microsoft Power BI Desktop

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/Devinbedi22/ipo-analysis-dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ipo-analysis-dashboard
   ```

3. Open the Excel dataset and inspect its structure.

4. Configure your SQL database and adapt the scripts to your database engine if necessary.

5. Execute the SQL scripts in the appropriate order, resolving any database-specific dependencies.

6. Open `IndianIpoAnalysis.pbix` in Power BI Desktop to explore the dashboard. If the report requires an external database connection, configure the data source and refresh the data.

## Validation

The repository includes a `validation_report.md` file intended to document data validation and quality checks. Refer to this file for the checks implemented in the project.

## Potential Applications

IPO analytics can support:
- Comparing IPO performance across companies and sectors.
- Exploring patterns in IPO activity over time.
- Supporting data-driven financial research.
- Communicating market trends through interactive dashboards.

## Future Enhancements

- Add additional financial performance indicators and comparative metrics.
- Incorporate time-based trend analysis and sector-level comparisons.
- Automate data ingestion and refresh workflows.
- Introduce statistical analysis and predictive modelling where appropriate.
- Add reproducible validation checks and documentation for analytical assumptions.

## License

This project is distributed under the license included in the repository. Refer to the `LICENSE` file for details.
