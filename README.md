# Customer Churn & Retention Analysis

## Project Overview

This project analyzes customer data to identify patterns associated with customer churn and provide data-driven recommendations that could help improve customer retention.

The analysis was completed using Python in Google Colab, with Pandas used for data cleaning and analysis and Matplotlib used for visualization.

## Business Objective

The goal of this project is to answer the following questions:

- What percentage of customers are churning?
- Which contract types have the highest churn rates?
- How does customer tenure relate to churn?
- Are payment methods associated with different churn rates?
- Does access to technical support relate to customer retention?

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Dataset

The dataset contains customer demographic, account, service, contract, payment, and churn information.

After data cleaning, the final dataset contained:

- **7,032 customers**
- **21 variables**

The `TotalCharges` column was converted from text to numeric format, and 11 records containing missing values were removed.

## Key Findings

### Overall Churn

The overall customer churn rate was **26.58%**, meaning approximately one in four customers in the dataset left the company.

### Contract Type

Month-to-month customers had a **42.71% churn rate**, compared with:

- One-year contracts: **11.28%**
- Two-year contracts: **2.85%**

Longer-term contracts were strongly associated with higher customer retention.

### Customer Tenure

Customers in their first 12 months had a **47.68% churn rate**.

Churn decreased substantially as customer tenure increased:

- 0–12 months: **47.68%**
- 13–24 months: **28.71%**
- 25–48 months: **20.39%**
- 49–72 months: **9.51%**

This suggests that the first year is a critical customer-retention period.

### Payment Method

Customers using electronic checks had the highest churn rate at **45.29%**.

By comparison:

- Automatic credit card: **15.25%**
- Automatic bank transfer: **16.73%**
- Mailed check: **19.20%**

### Technical Support

Customers without technical support had a **41.65% churn rate**, compared with **15.20%** among customers with technical support.

## Business Recommendations

Based on the analysis, the company could:

1. Improve customer onboarding and engagement during the first 12 months.
2. Offer incentives for month-to-month customers to switch to longer-term contracts.
3. Investigate why electronic-check customers experience higher churn.
4. Promote technical support services to customers who do not currently have them.
5. Use these indicators to identify high-risk customers for targeted retention campaigns.

## Important Note

The findings show associations between customer characteristics and churn. They do not establish that any individual factor directly causes customers to leave.

## Repository Contents

- `Customer_Churn_Analysis.ipynb` — complete Python analysis, visualizations, and business insights.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — dataset used for the analysis.
