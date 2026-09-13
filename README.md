# Data Analysis Projects Portfolio

A comprehensive collection of 9 real-world data analysis projects across multiple tools and technologies, covering logistics, supply chain, operations, and business intelligence.

---

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Projects Summary](#projects-summary)
  - [Excel Projects](#excel-projects)
  - [Python Projects](#python-projects)
- [Tools & Technologies](#tools--technologies)
- [Getting Started](#getting-started)
- [Project Details](#project-details)
- [Data Sources](#data-sources)
- [Key Skills Demonstrated](#key-skills-demonstrated)
- [Roadmap](#roadmap)
- [Installation & Setup](#installation--setup)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Overview

This portfolio showcases professional-grade data analysis projects that solve real-world business problems. Each project demonstrates technical proficiency in data manipulation, visualization, analysis, and reporting using industry-standard tools.

### What's Included
- 5 Excel Projects (13 MB) - Advanced spreadsheet modeling and dashboarding
- 4 Python Projects (4.5 MB) - Data science, web scraping, and ETL pipelines
- 30 Files Total - Well-organized, documented, and production-ready
- Real Datasets - From Kaggle and public sources
- Complete Documentation - README files for each project

---

## Repository Structure

```
excel-power-pivot-kpi-dashboard/
|
|-- excel/
|   |-- 01_inventory_control/
|   |   |-- 01_inventory_control.xlsx
|   |   |-- README.md
|   |-- 02_kpi_dashboard/
|   |   |-- 02_kpi_dashboard.xlsx
|   |   |-- README.md
|   |-- 03_inventory_parameters/
|   |   |-- 03_inventory_parameters.xlsx
|   |   |-- README.md
|   |-- 04_supplier_evaluation/
|   |   |-- 04_supplier_evaluation.xlsx
|   |   |-- README.md
|   |-- 05_budget_tracking/
|       |-- 05_budget_tracking.xlsx
|       |-- README.md
|
|-- python/
|   |-- 01_sales_eda/
|   |   |-- 01_sales_eda.ipynb
|   |   |-- requirements.txt
|   |   |-- amazon_sales_cleaned.csv
|   |   |-- README.md
|   |-- 02_inventory_optimization/
|   |   |-- 02_inventory_optimization.ipynb
|   |   |-- requirements.txt
|   |   |-- inventory_optimization_results.csv
|   |   |-- README.md
|   |-- 03_web_scraping/
|   |   |-- 03_web_scraping.ipynb
|   |   |-- requirements.txt
|   |   |-- books_scraped_data.csv
|   |   |-- README.md
|   |-- 04_etl_pipeline/
|       |-- 04_etl_pipeline.ipynb
|       |-- requirements.txt
|       |-- README.md
|
|-- README.md (this file)
|-- LICENSE (MIT)
|-- .gitignore
```

---

## Projects Summary

### Excel Projects

| # | Project | Description | Dataset Size | Key Concepts |
|---|---------|-------------|--------------|--------------|
| 01 | Inventory Control | ABC/XYZ analysis classifying 7,116 SKUs by value and demand variability | 12 months | Pivot Tables, ABC Analysis, Data Classification |
| 02 | KPI Dashboard | Interactive sales dashboard tracking metrics across 45 stores | 3 years (2010-2012) | Dashboard Design, Slicers, Dynamic Charts, KPI Tracking |
| 03 | Inventory Parameters | Advanced calculations for inventory management (Safety Stock, EOQ, Reorder Points) | 290 SKUs, 25 months | Statistical Functions, Advanced Formulas, Risk Analysis |
| 04 | Supplier Evaluation | Multi-criteria decision model ranking 35 suppliers | 12 Criteria | MCDM, Normalization, Weighted Scoring, Ranking |
| 05 | Budget Tracking | Variance analysis and executive dashboard for budget monitoring | 6 Categories, 12 months | Budget vs Actual, Variance Analysis, Executive Reporting |

**Excel Skills Demonstrated:**
- Pivot Tables & Pivot Charts
- Advanced Formulas (SUMIF, COUNTIF, VLOOKUP, INDEX/MATCH, SUMPRODUCT)
- Conditional Formatting & Data Validation
- Dashboard Design & Interactive Slicers
- Named Ranges & Dynamic References
- Statistical Functions (NORM.S.INV, SQRT, CEILING)

---

### Python Projects

| # | Project | Description | Jupyter Notebook | Key Libraries |
|---|---------|-------------|-----------------|----------------|
| 01 | Sales EDA | Exploratory analysis of Amazon India sales data | Yes | pandas, matplotlib, seaborn |
| 02 | Inventory Optimization | EOQ & Safety Stock calculations for 303 SKUs | Yes | pandas, numpy, scipy, matplotlib, seaborn |
| 03 | Web Scraping | Extract & analyze book data from e-commerce site | Yes | requests, BeautifulSoup, pandas |
| 04 | ETL Pipeline | End-to-end data pipeline for 100K e-commerce orders | Yes | pandas, numpy, sqlalchemy, sqlite3 |

**Python Skills Demonstrated:**
- Data Manipulation & Cleaning (pandas, numpy)
- Statistical Analysis (scipy, statistical functions)
- Data Visualization (matplotlib, seaborn)
- Web Scraping (requests, BeautifulSoup, HTML parsing)
- ETL Pipelines (multi-source extraction, transformation, loading)
- Database Operations (SQLAlchemy, SQLite)
- Jupyter Notebook Documentation

---

## Tools & Technologies

### Spreadsheets
- Microsoft Excel (Advanced)
- Power Query
- Pivot Tables & Charts
- Advanced Formulas & Functions

### Programming Languages
- Python 3.9+
- Jupyter Notebooks

### Python Libraries

| Category | Libraries |
|----------|-----------|
| Data Processing | pandas, numpy |
| Analysis | scipy |
| Visualization | matplotlib, seaborn |
| Web Scraping | requests, BeautifulSoup |
| Database | sqlalchemy, sqlite3 |

### Databases
- SQLite
- Relational data modeling

### Version Control
- Git
- GitHub

---

## Project Details

### Excel 01: Inventory Control

Objective: Classify products using ABC/XYZ analysis for inventory prioritization

What it does:
- Analyzes 7,116 SKUs from Amazon sales data
- Calculates ABC ranking (by annual sales value)
- Calculates XYZ ranking (by demand variability)
- Creates 2D matrix for inventory management
- Provides actionable insights for stock optimization

Key Metrics: Revenue contribution, Demand variability, Inventory categories

---

### Excel 02: KPI Dashboard

Objective: Track and visualize key sales performance indicators

What it does:
- Aggregates Walmart sales data (45 stores, 3 years)
- Displays KPIs: Total Sales, Growth Rate, Store Performance
- Interactive slicers for filtering by store and period
- Dynamic charts updating based on selections
- Executive-ready dashboard layout

Key Metrics: Weekly sales, Store performance, Trend analysis

---

### Excel 03: Inventory Parameters

Objective: Calculate optimal inventory management parameters

What it does:
- Computes Economic Order Quantity (EOQ)
- Calculates Safety Stock levels
- Determines Reorder Points
- Assesses risk metrics (Value at Risk)
- Handles 290 SKUs with 25 months of history

Key Metrics: EOQ, Safety Stock, Reorder Point, Service Level

---

### Excel 04: Supplier Evaluation

Objective: Rank suppliers using multi-criteria decision model

What it does:
- Evaluates 35 suppliers across 12 criteria
- Applies weighted scoring system
- Normalizes scores using Min-Max scaling
- Ranks suppliers objectively
- Supports vendor selection decisions

Key Metrics: Quality, Cost, Delivery, Service scores

---

### Excel 05: Budget Tracking

Objective: Monitor budget performance and variance

What it does:
- Tracks budgeted vs actual expenses
- Calculates variance across 6 cost categories
- Creates variance analysis dashboard
- Shows monthly trends
- Highlights over/under budget items

Key Metrics: Budget variance %, Category breakdown, Trend analysis

---

### Python 01: Sales EDA

Objective: Explore Amazon sales patterns and customer behavior

Notebooks: 01_sales_eda.ipynb

What it does:
- Loads and explores Amazon India sales dataset
- Analyzes consumption patterns
- Evaluates discount effectiveness
- Assesses customer satisfaction metrics
- Generates visualization dashboard

Output: Insights report, visualizations, recommendations

---

### Python 02: Inventory Optimization

Objective: Calculate optimal inventory parameters using statistical methods

Notebooks: 02_inventory_optimization.ipynb

What it does:
- Processes 2.5 years of sales data for 303 SKUs
- Calculates EOQ using classical formula
- Determines Safety Stock using demand forecasting
- Computes Reorder Points
- Performs ABC classification
- Quantifies inventory risk

Output: Optimization results CSV, visualization, recommendations

---

### Python 03: Web Scraping

Objective: Extract and analyze e-commerce data programmatically

Notebooks: 03_web_scraping.ipynb

What it does:
- Scrapes book data from Books to Scrape website
- Handles pagination automatically
- Parses HTML using BeautifulSoup
- Cleans and validates extracted data
- Exports results to CSV
- Demonstrates ethical scraping practices

Output: Books dataset CSV with price, rating, availability data

---

### Python 04: ETL Pipeline

Objective: Build complete data pipeline from extraction to analysis

Notebooks: 04_etl_pipeline.ipynb

What it does:
- Extracts from 9 source files (Olist dataset)
- Processes 100K+ e-commerce orders
- Cleans datetime and null values
- Performs feature engineering
- Translates categories
- Loads into SQLite database
- Demonstrates business queries

Output: SQLite database, transformed data, query results

---

## Key Skills Demonstrated

### Data Analysis
- Exploratory Data Analysis (EDA)
- ABC Analysis & Classification
- Time Series Analysis
- Variance Analysis
- Statistical Testing

### Data Visualization
- Interactive Dashboards (Excel)
- Charts & Graphs (matplotlib, seaborn)
- Dashboard Design Principles
- KPI Visualization

### Data Engineering
- ETL Pipeline Development
- Data Cleaning & Transformation
- Database Design & Querying
- Web Scraping

### Business Acumen
- Inventory Management
- Supply Chain Optimization
- Financial Analysis
- Operational Metrics
- Decision Support Systems

### Technical Skills
- Advanced Excel Formulas
- Python Programming
- SQL & Database Management
- Git & Version Control
- Jupyter Notebooks

---

## Getting Started

### For Excel Projects
1. Download the .xlsx file from the respective project folder
2. Open in Microsoft Excel 2016 or later
3. Enable macros/dynamic features if prompted
4. Read the project README for detailed instructions

### For Python Projects

Prerequisites:
- Python 3.9 or higher
- pip or conda

Installation:

```bash
# Clone the repository
git clone https://github.com/AyushAhuja-23/excel-power-pivot-kpi-dashboard.git
cd excel-power-pivot-kpi-dashboard

# Install dependencies for all Python projects
pip install pandas numpy scipy matplotlib seaborn requests beautifulsoup4 sqlalchemy

# Or install per project
cd python/01_sales_eda
pip install -r requirements.txt
```

Running Jupyter Notebooks:

```bash
# Install Jupyter (if not already installed)
pip install jupyter

# Navigate to project directory
cd python/01_sales_eda

# Launch Jupyter
jupyter notebook 01_sales_eda.ipynb
```

---

## Data Sources

All datasets are publicly available and sourced from Kaggle or public websites:

| Project | Dataset | Source | Size |
|---------|---------|--------|------|
| Excel 01 | Amazon Sales Report | Kaggle | ~7K SKUs |
| Excel 02 | Walmart Weekly Sales | Kaggle | 45 stores, 3 years |
| Excel 03 | Dynamic Inventory Dataset | Kaggle | 290 SKUs, 25 months |
| Excel 04 | Suppliers Ranking | Kaggle | 35 suppliers |
| Excel 05 | Financial Dataset | Kaggle | Budget vs Actual |
| Python 01 | Amazon Sales Dataset | Kaggle | Sales transactions |
| Python 02 | Dynamic Inventory Dataset | Kaggle | 303 SKUs, 30 months |
| Python 03 | Books to Scrape | books.toscrape.com | Practice website |
| Python 04 | Olist E-Commerce | Kaggle | 100K+ orders |

Note: Raw data files are not included in this repository due to file size. Download from the sources above using the links provided.

---

## Notes

- Each project folder contains its own detailed README.md with:
  - Project objective
  - Data source information
  - Methodology explanation
  - Key findings & results
  - How to use/interpret the outputs

- Data Handling: Raw datasets are not included in the repository. Each project README provides links to download the original data.

- Datasets: All datasets are either publicly available from Kaggle or from legitimate public sources. Some data has been anonymized or is synthetic.

- Reproducibility: Each project is self-contained and can be run independently following the instructions in its README.

---

## Roadmap

Future enhancements planned for this portfolio (not yet started):

### Python 05: Predictive Maintenance
- Failure prediction using classification models
- Libraries: scikit-learn, pandas

### Tableau
- Logistics Dashboard
- Sales Performance Dashboard
- Customer Segmentation Dashboard
- Supply Chain Visualization
- Financial Overview Dashboard

### Power BI
- Warehouse KPI Dashboard
- Procurement Analysis
- Project Tracking Dashboard
- HR Headcount Dashboard
- Operational Costs Dashboard

### SQL (MySQL/PostgreSQL)
- Inventory Queries
- Sales Reporting
- Customer Analysis
- Supply Chain Queries
- Data Cleaning & Transformation Scripts

### Machine Learning
- Demand Forecasting
- Anomaly Detection
- Classification Models
- Customer Clustering
- Regression Analysis

---

## Important Notes

- Data Privacy: All datasets are publicly available or anonymized
- Raw Data: Not included in repo due to file size limitations
- Reproducibility: Each project is independent and can be run separately
- Python Version: Requires Python 3.9 or higher
- Excel Version: Works with Excel 2016 and later

---

## Contributing

Contributions, suggestions, and feedback are welcome!

To contribute:
1. Fork the repository
2. Create a feature branch (git checkout -b feature/improvement)
3. Commit your changes (git commit -am 'Add improvement')
4. Push to the branch (git push origin feature/improvement)
5. Submit a Pull Request

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

MIT License allows you to:
- Use commercially
- Modify the code
- Distribute
- Use privately

Just remember to include the license notice.

---

## Author

Ayush Ahuja

Data Analyst | Business Intelligence | Supply Chain Optimization

Location: Ahmedabad, Gujarat, India

Connect with me:
- GitHub: https://github.com/AyushAhuja-23
- LinkedIn: [https://www.linkedin.com/in/ayush-ahuja-356400279/]
- Email: ahujaayush@outlook.com
- 

---

## Acknowledgments

- Data Sources: Kaggle, public datasets, and ethical web scraping
- Inspiration: Real-world business problems in supply chain and operations
- Original Author Framework: Built upon professional data analysis practices

---

## Support & Questions

If you have questions about any project:
1. Check the project-specific README.md first
2. Review the code comments and documentation
3. Open an Issue on GitHub

---

## If You Find This Helpful

Please consider:
- Starring this repository
- Sharing with others
- Providing feedback
- Contributing improvements

---

## Repository Stats

- Total Projects: 9
- Total Files: 30+
- Total Size: ~17 MB
- Excel Files: 5 workbooks
- Python Notebooks: 4 Jupyter notebooks
- Documentation: Complete for each project
- Data Sources: 9 different datasets

---

Last Updated: September 13, 2026
Status: Production Ready
Quality: 5/5 Stars

---

This portfolio represents a professional-grade collection of data analysis projects demonstrating expertise in spreadsheet modeling, Python programming, and business intelligence.
