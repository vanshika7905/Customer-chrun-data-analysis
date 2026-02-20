📊 Telecom Customer Churn Analysis
📌 Project Overview

Customer churn is one of the most critical problems faced by telecom companies. In this project, I performed Exploratory Data Analysis (EDA) on a telecom customer dataset to understand customer behavior and identify key factors that contribute to customer churn.

The analysis focuses on customer demographics, services subscribed, contract types, billing methods, and charges to gain insights into churn patterns.

📂 Dataset Information

Dataset Name: Customer Churn Dataset

Total Records: 7,043 customers

Total Features: 21 columns

Target Variable: Churn (Yes / No)

Key Features:

Customer Demographics: gender, SeniorCitizen, Partner, Dependents

Service Details: PhoneService, InternetService, OnlineSecurity, StreamingTV, etc.

Account Information: tenure, Contract, PaymentMethod

Billing Details: MonthlyCharges, TotalCharges

🛠️ Tools & Libraries Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib – data visualization

Seaborn – statistical plots

Jupyter Notebook

🔍 Steps Performed

Data Loading & Inspection

Loaded CSV file using Pandas

Checked dataset shape and structure

Data Cleaning

Verified missing values

Checked data types of all features

Exploratory Data Analysis (EDA)

Analyzed churn distribution

Studied relationships between churn and:

Contract type

Monthly charges

Internet service type

Payment method

Tenure

Visualization

Used plots to identify churn trends

Compared churn vs non-churn customers

📈 Key Insights

Customers with month-to-month contracts have a higher churn rate.

Higher monthly charges are strongly associated with churn.

Customers using fiber optic internet show more churn.

Long-tenure customers are less likely to churn.

Automatic payment methods reduce churn risk.
