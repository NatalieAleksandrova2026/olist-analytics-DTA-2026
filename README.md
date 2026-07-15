# olist-analytics-DTA-2026
Brazilian E-Commerce (Olist) Analysis: From Raw Data to Simple Forecast
Tools: SQL (SQLite), Google Sheets, Tableau Public, Python

Data
Source: Brazilian E-Commerce Public Dataset by Olist (Kaggle)

9 CSV files, approximately 100k orders (2016–2018), relational structure.

The database was assembled from raw CSV files using the Python script sql/build_olist_db.py.

Objective
(1–2 sentences: describe the key business question or problem you are solving here).

Steps
SQL: Dataset preparation (JOINs, filtering for delivered status, monthly aggregations).

Data Cleaning & Enrichment (Google Sheets): (e.g., mapping Brazilian states to geographical regions).

Tableau: Visualizations and main insights discovered during EDA.

Python: Forecasting methodology and model selection.

Dashboard
Tableau Public Link: [Insert Link Here]

Screenshots: Available in the tableau/ directory.

Key Insights
Insight 1: (e.g., Seasonal sales peaks or top-performing regions).

Insight 2: (e.g., Average delivery times and their impact on customer satisfaction).

Insight 3: (e.g., Dominating product categories by revenue).

Forecast & Recommendations
Revenue Forecast for Next Month: [Enter Value / Currency]

Recommendations:

(Recommendation 1)

(Recommendation 2)

(Recommendation 3)

Repository Structure
Plaintext
├── data/       # Exported CSVs
├── sql/        # queries.sql, build_olist_db.py
├── tableau/    # Dashboard screenshots
├── notebook/   # Forecasting notebook (.ipynb)
└── README.md   # Project documentation
How to Reproduce
Download the dataset from Kaggle (link provided above) and extract the CSV files.

Build the database:

Bash
python sql/build_olist_db.py ./olist_csv olist.db
Run the queries from sql/queries.sql and export the results to a CSV file.

(Optional) Perform additional data cleaning/enrichment in Google Sheets.

Connect the resulting CSV to Tableau Public to view or rebuild the dashboard.

Open the Jupyter Notebook in notebook/ to run the forecasting model.
