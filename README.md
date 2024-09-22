Customer Churn Analysis for a Telecom Company
Project Overview
This project aims to identify the key factors that influence customer churn in a telecom company. Through Exploratory Data Analysis (EDA), patterns and insights were derived, helping the company understand which factors lead customers to leave and which might help improve retention.

Dataset
Source: Telco Customer Churn on Kaggle
The dataset contains customer demographics, account information, services used, and whether the customer has churned.
Technologies Used
Programming Language: Python
Libraries: pandas, seaborn, matplotlib, numpy
Development Environment: Google Colab
Steps Involved
Data Cleaning:
Handled missing values and converted columns to appropriate data types.
Data Exploration:
Visualized the distribution of key features such as MonthlyCharges, Tenure, and Contract.
Correlation Analysis:
Analyzed the relationships between numerical features and customer churn using correlation matrices.
Feature Engineering:
Created a new feature AvgMonthlySpend to better understand customer behavior.
Insights:
Customers with monthly charges above $70 had a 58% churn rate.
Customers with tenure over 30 months had a churn rate of only 15%.
80% of customers with month-to-month contracts were more likely to churn.
Key Findings
Customers with higher monthly charges and shorter tenure are more likely to churn.
Longer-term contracts (one or two-year contracts) show lower churn rates.
The company should focus on offering retention strategies for customers with month-to-month contracts.
How to Run the Project
Clone the repository or download the project files.
Install the necessary libraries using: pip install pandas seaborn matplotlib
Load the dataset (customer_churn.csv) from Kaggle or the provided link.
Open the Jupyter Notebook or Google Colab, and run the analysis.
Output
A 58% churn rate among customers with monthly charges above $70.
Only 15% churn rate among customers with a tenure of over 30 months.
Month-to-month contract customers have an 80% churn likelihood.
License
This project is open-source and available for further modifications and enhancements.
