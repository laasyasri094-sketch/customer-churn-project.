# Customer Churn Prediction & Analysis

## Project overview
Analyzed a sample telecom customer dataset to explore customer churn, identify higher-risk segments, and build a baseline churn prediction model.

## Tools
- Python: pandas and scikit-learn
- SQL: SQLite
- Looker Studio: interactive dashboard

## Workflow
- Cleaned the data and converted `TotalCharges` to numeric. The 11 blank values were customers with zero tenure, so they were filled with 0.
- Used exploratory data analysis and SQL to compare churn across customer and service groups.
- Trained a logistic regression model and evaluated it on a stratified held-out test set.
- Built an interactive dashboard to show churn KPIs and segment comparisons.

## Key findings
- Overall churn rate: **26.54%**.
- Month-to-month contract churn: **42.71%**; two-year contract churn: **2.83%**.
- Median tenure was **10 months** for customers who churned and **38 months** for customers who stayed.
- Test ROC-AUC: **0.842**.
- At a **0.40** threshold, the model flagged 440 test customers: 250 churners were correctly flagged, 190 flagged customers stayed, and 124 churners were missed.

## Recommendation
A retention team could test earlier outreach for newer, month-to-month customers. These are patterns in the dataset; they do not prove what caused churn or that an intervention will reduce it.

## Files
- `customer_churn_analysis.ipynb` — Colab analysis notebook
- `Customer_churn_analysis_dashboard (1).pdf` — dashboard export
- `README.md` — project overview and findings
