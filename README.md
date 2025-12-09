# Retail Customer Trends Analysis

Overview
This repository contains an end-to-end analytics workflow to understand retail customer behavior, identify shopping patterns, and produce business-ready insights. The work covers data ingestion and cleaning in Python, exploratory data analysis (EDA), SQL-based analysis, and an interactive Power BI dashboard. Final results are summarized in a report and presentation.

Dataset
Source: Retail customer transactions, demographics, and product details.

Key fields:
- Customer ID, Age, Gender, Location
- Product Category, Quantity, Price
- Purchase Date, Total Amount

Processed output: final_customer_data.csv (after cleaning and feature engineering)

Repository layout
- Data/
  - raw/           — original data files
  - processed/     — cleaned and transformed datasets
- Scripts/
  - Customer_Shopping_behavior.ipynb
- SQL/
  - Customer_behavior_shopping.sql
- Dashboard/
  - customer_behavior_dashboard.pbix
- Reports/
  - Customer Shopping Behavior Analysis Report.pdf
  - Customer-Shopping-Behavior-Analysis.pptx
- README.md

Workflow summary
1. Load and inspect raw data in Python.
2. Perform EDA: summary statistics, distributions, correlations, and visualizations.
3. Clean and preprocess: missing values, date/category standardization, duplicates removal.
4. Feature engineering: total spend, purchase frequency, CLV, segmentation labels.
5. Run SQL analyses for cohort, region, category, and time-series insights.
6. Build Power BI dashboard for KPIs, segmentation, and trends.
7. Produce a consolidated report and presentation for stakeholders.

Typical analyses included
- Top customers and revenue contributors
- Product category performance and repeat purchase trends
- Regional sales and retention analysis
- Monthly and quarterly trend analysis
- Average basket size and customer cohorts (high/low value)

Suggested business actions
- Target loyalty programs at high-frequency and high-value customers
- Promote high-repeat categories with bundling or personalized offers
- Focus retention efforts in underperforming regions
- Use cohort-based campaigns to increase CLV

How to run
1. Clone the repository:
   git clone https://github.com/prathit1/Retail-Customer-Trends-Analysis.git
   cd Retail-Customer-Trends-Analysis

2. Install dependencies (example):
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

3. Open and run the notebook:
   Scripts/Customer_Shopping_behavior.ipynb

4. Load SQL scripts into your DB:
   SQL/Customer_behavior_shopping.sql

5. Open the Power BI file:
   Dashboard/customer_behavior_dashboard.pbix

Notes
- Replace placeholder names (e.g., Category X, Month A, Region A) with real results from your analysis.
- Adjust file names and paths below if your repository structure differs.

Contact
GitHub: https://github.com/prathit1
