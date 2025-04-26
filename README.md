📄 README - Telco Customer Churn Analysis

📌 Project Overview

This project analyzes customer churn behavior using the "Telco Customer Churn" dataset.The goal is to understand customer demographics, services, and contracts to predict churn and create insights using Python and Power BI visualizations.

📂 Files Included

WA_Fn-UseC_-Telco-Customer-Churn.csv — Main dataset.

Untitled.ipynb — Python notebook for data cleaning and preprocessing.

Customer Risk Analysis Dashboard.pbix — Power BI dashboard file.

README.md — Project description and guide.

🛠️ Tools Used

Python (Pandas, NumPy) for data cleaning.

Power BI for dashboard and visualizations.

Jupyter Notebook for data exploration.

🧹 Data Cleaning Steps

Converted TotalCharges column to numeric format.

Handled missing values by filling with 0 where needed.

Mapped SeniorCitizen values (0 → No, 1 → Yes).

Checked and removed any duplicate records.

📊 Power BI Visualizations

The "Customer Risk Analysis Dashboard" Power BI file contains the following visualizations:

Pie Chart: Distribution of customer gender.

Bar Chart: Number of customers segmented by Internet Service type.

Line Chart: Monthly Charges trends over customer tenure.

Donut Chart: Distribution of Contract Types.

Cards: Key metrics like Total Customers, Churned Customers, and Average Monthly Charges.

Slicers: Filters for Gender, Contract Type, Internet Service, and Payment Method.

Clustered Bar Chart: Churn status against customer Senior Citizen status.

Stacked Column Chart: Dependents vs. Churn Rate.

🚀 How to Run

Open the .ipynb file in Jupyter Notebook.

Run the cleaning code step-by-step.

Export or save the cleaned CSV file.

Open Power BI Desktop.

Import the cleaned CSV and open the Customer Risk Analysis Dashboard.pbix file to explore visualizations.

📈 Future Improvements

Build predictive churn models (e.g., Logistic Regression, Random Forest).

Add more KPIs to Power BI dashboard.

Automate data refresh for dynamic dashboards.

Deploy dashboard to Power BI Service for sharing and real-time collaboration.

👤 Author

Name: Y.Nikhilesh

Date: April 2025
