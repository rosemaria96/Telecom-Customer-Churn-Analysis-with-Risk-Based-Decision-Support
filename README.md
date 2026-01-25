# Telecom-Customer-Churn-Analysis-with-Risk-Based-Decision-Support
## Project Overview
This project analyzes telecom customer behavior to identify churn patterns and implement a **rule-based risk scoring system**. It combines **data analysis, feature engineering, and decision rules** to support business retention strategies.

## Dataset
- Source: Telecom Customer Churn dataset (CSV)
- Size: 7043 rows, 21 columns
- Key features: Tenure, Contract, MonthlyCharges, TotalCharges, OnlineSecurity, TechSupport, Churn

## Project Workflow
1. **Data Cleaning**
   - Handle missing values and hidden blanks
   - Convert numeric fields to proper types
2. **Exploratory Data Analysis (EDA)**
   - Visualizations for churn patterns
   - Correlation and distribution analysis
3. **Feature Engineering**
   - Tenure buckets
   - High monthly charges flag
4. **Decision Rules / Risk Scoring**
   - Assign churn risk: Low, Medium, High
   - Include actionable business recommendations
5. **Visualizations**
   - Churn vs Contract / PaymentMethod
   - Risk vs Churn distribution

## Key Insights
- Customers with **month-to-month contracts and low tenure** have the **highest churn risk**
- Senior citizens without tech support are at **medium risk**
- High monthly charges + no online security also increases churn likelihood

## Tools & Libraries
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn

## Output Files
- Tele_Customer_Churn_Cleaned.csv : cleaned dataset
- churn_decision_rules.csv : exported rules
