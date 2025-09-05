# Telco Customer Churn Analysis  

## Overview  
This project focuses on **customer churn** in a telecom company.  
Customer churn (also called attrition) refers to the percentage of customers who stop using a service during a given period. A high churn rate is a major business risk, as it reduces revenue and increases customer acquisition costs.  

The main goal of this project is **data preprocessing and exploratory analysis**. Some machine learning models are tested, but the emphasis is on preparing clean data and extracting business insights.  

---

## Dataset  
The dataset (`Telco_customer_churn.xlsx`) contains:  
- Customer demographics (gender, senior citizen, dependents)  
- Contract information (month-to-month, one-year, two-year)  
- Services subscribed (phone, internet, TV, streaming)  
- Payment details (billing type, charges, payment method)  
- Churn label (Yes/No)  

---

## Methods  
1. **Data Preprocessing (DPT)**  
   - Handling missing values  
   - Converting “Total Charges” into numeric values  
   - Feature engineering (e.g., monthly/tenure ratio)  
   - Scaling and encoding variables  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation heatmaps  
   - Distribution of churn by contract type, tenure, payment method  
   - Visualizations with matplotlib, seaborn, and plotly  

3. **Modeling**  
   - XGBoost classifier with SMOTE for imbalanced data  
   - Evaluation with accuracy, recall, precision, F1-score, and ROC-AUC  

---

## Key Findings  
- **Churn Rate:** Around 26% of customers leave → a significant business concern.(this means approximately **1 out of every 4 customers is lost**).
- **Contract Type:** Month-to-month contracts have the highest churn; long-term contracts reduce churn.  
- **Payment Method:** Automatic payment methods are linked to lower churn.  
- **Tenure:** New customers (first 6 months) are most likely to churn; loyal customers stay longer.  
- **Services:** Fiber internet users churn more often; bundled services reduce churn.  

---

## Business Insights  
- Encourage **long-term contracts** to reduce churn risk.  
- Provide discounts or promotions for **automatic payments**.  
- Improve the **onboarding process** in the first months of service.  
- Pay special attention to **fiber internet customers** with service quality improvements.  
- Protect revenue by offering loyalty benefits to **high-value customers**.  

---
## Conclusion  
This project demonstrates how **data preprocessing and exploratory business analysis** can work together.  
The current focus is on preparing clean data and identifying key churn insights using Python.  

As a next step, these results could be extended with **BI visualization tools**, where business users can interact with the data.  
Possible dashboards may include:  
- **Customer Segmentation:** churn rates by demographics, contract type, or payment method  
- **KPI Dashboard:** total customers, churn %, and revenue loss  
- **Trend Analysis:** churn trends over time  
- **Revenue Impact:** financial effect of churn by customer segment  

Such dashboards would allow managers to better understand customer behavior and design effective retention strategies.


