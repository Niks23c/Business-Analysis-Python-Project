## 📊 Business Analysis with Python – Data Analysis Project
🧠 Project Objective
This project aims to uncover valuable business insights from customer data using Python's data analysis libraries. The primary goal is to identify patterns, trends, and actionable insights that can support better decision-making and improve overall business performance.

## 📂 Dataset Description
Dataset Name: Telco.csv

Source: Telecom company’s customer dataset

Records: ~7,000 customers

Features:

Customer ID, Gender, Senior Citizen, Partner, Dependents

Tenure, Phone & Internet Services

Contract, Payment Method, Monthly Charges

Total Charges, Churn Status, etc.

## 🔧 Tools & Technologies Used
Language: Python

IDE: Jupyter Notebook

Libraries:

pandas – Data manipulation

numpy – Numerical calculations

matplotlib & seaborn – Data visualization

scipy – Statistical testing

plotly – Interactive visualizations (optional)

## 📈 Key Steps & Workflow
📥 Data Loading
Imported dataset using pandas

Initial inspection using .head(), .info(), and .describe()

## 🧹 Data Cleaning
Checked for null values and data types

Handled missing or incorrect values in TotalCharges

Converted columns to appropriate data types

## 🔍 Exploratory Data Analysis (EDA)
Univariate analysis: distribution of numerical & categorical features

Bivariate analysis: churn vs tenure, charges, contract type, etc.

Correlation heatmaps to identify strong relationships

Visualized key patterns influencing customer churn

## 🧠 Business Insights
Customers on month-to-month contracts had higher churn rates

High churn among customers with fiber optic internet

Senior citizens and single customers are more likely to churn

Electronic checks associated with higher churn

## 📌 Actionable Recommendations
Offer discounts on long-term contracts to reduce churn

Improve customer support for high-risk groups (e.g. senior citizens)

Incentivize online auto-pay methods to reduce churn

## 📊 Highlighted Visuals

Churn distribution pie chart

![Churn pie](images/customerchurn.JPG) ← 

Boxplots: Monthly Charges vs Churn

![Churn BOX](images/Monthly.JPG) ← 

Bar charts: Contract Type vs Churn Rate

![Churn CONTRACT](images/Contract.JPG) ← 

Heatmap of feature correlations
![Churn CONTRACT](images/Feature.JPG) ← 



