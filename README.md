# Financial-Data-Exploration-and-Visualization-in-Power-BI

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Dashboard Projects](#dashboards)
- [Tools](#tools)
- [Data Cleaning/Preparation](#datacleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
---
This project aims to provide insights into the financial performance of the customers at Aurora Bank.
The dataset was analysed to generate insights on the Customer Demographics, Debt-to-income ratio, Debt Risk Score, customer spending pattern and the trend in credit and debit card usage.

### Data Source
Financial Data: The primary dataset used for this analysis is the "aurora_bank_data.csv" file, containing customers, transaction and card data.

## Dashboard Projects
#### Demographics Dashboard
![Demographics Dashboard](https://github.com/Funke-Shittu/Financial-Data-Exploration-and-Visualization/blob/main/Demographic.png?raw=true)
#### Financial Health Dashboard
![Financial Health Dashboard](https://github.com/Funke-Shittu/Financial-Data-Exploration-and-Visualization/blob/main/Financial.png?raw=true)
#### Transaction Dashboard
![Transaction Dashboard](https://github.com/Funke-Shittu/Financial-Data-Exploration-and-Visualization/blob/main/Transaction%20Det..png?raw=true)
#### Card Details Dashboard
![Card Details Dashboard](https://github.com/Funke-Shittu/Financial-Data-Exploration-and-Visualization/blob/main/Card%20Details.png?raw=true)

### Tools
- Excel - Data Extraction
- Power Query - Data Cleaning
- Power BI - Creating Reports

### Data Cleaning/Preparation
In the initial data preparation phase, the following tasks was performed;
1. Data extraction, loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring the financial data to answer questions, such as:
1. What is the customer demographics? (Age, gender and geographical distribution of customers)
2. What is the Credit Score Analysis? (Distribution of credit scores and the factors influencing them (e.g., income, debt, age)
3. What is the Financial Health? (Debt-to-income ratios and identify high-risk customers)
4. What is the number of credit/debit cards per customer and usage trends by demographic?

### Data Analysis
Include some interesting code worked with

`DAX

`_avg age = AVERAGE(dim_users_data[current_age])`

`DTI category = 
SWITCH(
    TRUE(),
    dim_users_data[DTI] <30, "Low Risk",
    dim_users_data[DTI] >=30 && dim_users_data[DTI] <50, "Manageable",
    dim_users_data[DTI] >=50 && dim_users_data[DTI] <150, "Risky Border",
    dim_users_data[DTI] >=150 && dim_users_data[DTI] <190, "High Risk",
    "Severe Risk")`

    
    
### Results
The analysis results are as follows;
1. The bank has more female than male customers with an average age, 45.
2. Income and debt has greater impact on the customers credit score than their age.
3. Highest debt-to-income ratio is in the 21-30 and 41-50 age group, with the debt-to-income ratio at 138.17
4. Each customer has an estimate of 3 cards, with most favouring Mastercard and Visa more than the other card brands.

### Recommendations
Based on the analysis, the following is reccommended;
- Offer credit counseling and financial literacy programs to low and middle income groups.
- Implement strict lending and monitor clients with high debt-to-income.
- Give incentives for cards that are less favoured by giving cashback and credit-building rewards.

🥰

💻
