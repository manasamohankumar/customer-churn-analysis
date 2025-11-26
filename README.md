# Customer Churn Prediction & Retention Strategy
Telecommunications (Australia) — Business Analytics Project

# Project Overview
Australian telecommunications companies — including Telstra, Optus, Vodafone and TPG — face persistent customer churn challenges. Customer churn directly impacts recurring revenue and increases acquisition costs.

This project predicts customer churn using the Telco Customer Churn dataset (Kaggle) and provides data-driven strategic recommendations for reducing churn.
The analysis covers:
  1. Customer behaviour patterns
  2. Key churn drivers
  3. Predictive modelling (Logistic Regression & Random Forest)
  4. Retention strategy for high-risk customers

# Business Problem
A mid-sized Australian telecom provider (“AussieConnect”) is experiencing a 26–27% churn rate. 
Leadership wants to:
  1. Understand why customers churn
  2. Identify high-risk customers
  3. Develop targeted retention strategies based on data

# Objectives
  1. Analyse customer demographics, usage behaviour, and service features
  2. Identify key churn predictors
  3. Build churn prediction models
  4. Evaluate performance and trade-offs
  5. Provide actionable business recommendations

# Tools & Techniques
  1. Python (Pandas, NumPy, Seaborn, Matplotlib)
  2. Scikit-Learn (Logistic Regression, Random Forest, Train/Test Split)
  3. One-Hot Encoding & Feature Scaling
  4. EDA & Insight Storytelling
  5. Business Strategy Recommendations

# Exploratory Data Analysis (Key Insights)
   
1️. Churn Distribution
    - 26% customers churned
    
    - Indicates class imbalance (typical in churn problems)
<img width="922" height="746" alt="image" src="https://github.com/user-attachments/assets/a12c4f0f-6dc8-4d1c-a1c6-f5e2a6bf2be2" />

2️. Churn vs Tenure
     - Customers with 0–12 months tenure churn the most
     
     - L0yalty increases significantly after first year
     <img width="958" height="608" alt="image" src="https://github.com/user-attachments/assets/535dd909-3d18-4ad4-91e5-4e9abcce3387" />

3️. Churn vs Monthly Charges
    - High-paying customers churn more
    
    - Price sensitivity is a major driver
    <img width="968" height="630" alt="image" src="https://github.com/user-attachments/assets/e36c4ecd-14ea-4fb8-8709-d058d5be3726" />

4️. Churn vs Contract Type
    - Month-to-month customers churn 3–4× more
    
    - One-year & two-year contracts strongly reduce churn
<img width="986" height="696" alt="image" src="https://github.com/user-attachments/assets/bcaf0302-c99a-47de-ba24-5526234f9c74" />

5️.  Service Features
    - Customers WITHOUT the following churn more
    
    - Online Security
    
    - Tech Support
    
    - Device Protection
    
    - These services reduce pain points and increase retention.
   <img width="862" height="544" alt="image" src="https://github.com/user-attachments/assets/483e5610-05d1-4a08-8691-081ea38cee32" />
<img width="912" height="570" alt="image" src="https://github.com/user-attachments/assets/80f6b846-bb91-46ab-8085-8baab22d260f" />

