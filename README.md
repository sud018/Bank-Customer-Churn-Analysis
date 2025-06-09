# Bank-Customer-Churn-Analysis

## Background and overview
This project focuses on analyzing **Customer Churn Patterns** in the banking sector using a real-world-like dataset. This dataset is taken from Kaggle and contains banking customer information with attributes like:
- **Customer demographics** (age, gender, geography)
- **Account activity** (tenure, balance, number of products, activity status)
- **Churn status** (whether the customer exited the bank or stayed)

The Objective of this analysis is to:
- Explore **key drivers of customer churn** in the banking sector
- Visualize **churn trends** across customer profiles and behaviours
- Calculate **churn rates** using various factors like Age, Activity, Tenure, IsActive
- Suggest **strategies** to improve customer retention and engagement

An interactive Tableau Dashboard is created to facilitate stakeholders with clear, visual insights and allow interactive exploration.

## Executive Summary
This analysis revealed a significant **churn issue**, with approximately 20% of customers leaving the bank. The main factors affecting are Age, Geography, and IsActiveMember. According to the observation, the age group above 40 years is leaving the bank where the churn is especially elevated, and the problem is **regionally concentrated**, with a huge loss of customers in Germany. Another factor affecting is InactiveMembers, with inactivity nearly doubling the likelihood of churn. 

Other patterns include:
- Tenure shows no strong correlation with churn, indicating that even long-term customers are at risk of leaving.
- Female customers churn at a slightly higher rate than males.

These findings indicate an urgent need for targeted engagement and retention strategies, particularly focused on high-risk regions and inactive or aging customer groups. The upcoming sections and the interactive Tableau dashboard will dive deeper into these trends and outline actionable recommendations.
 
<img width="656" alt="Screenshot 2025-06-08 at 9 18 57 PM" src="https://github.com/user-attachments/assets/888dadc3-c0bb-4246-a843-c7951ecd9b95" />

## Insights Deep Dive
The customer churn analysis for the Bank reveals several meaningful patterns that can drive data-informed retention strategies:

📍 **Geography and Gender**
- Germany exhibits the highest churn rate of 32%, significantly higher than France(16%) and Spain(17%).
- Within Germany, **female customers** churn at a staggering 38%, compared to 28% for males, indicating that targeting gender-specific factors could improve retention.
  
<img width="649" alt="Screenshot 2025-06-08 at 10 02 09 PM" src="https://github.com/user-attachments/assets/ff39c3cc-4b8b-4ea4-bc5e-08bec761c7f6" />

👤 **Age Distribution**
- The Age Group above 40 years is most likely to churn, with a churn rate of almost 45%.
- Whereas the age group below 40 years is showing loyalty with a nearly 13% churn rate.



<img width="182" alt="Screenshot 2025-06-08 at 10 04 24 PM" src="https://github.com/user-attachments/assets/3548cb70-a4aa-4bdb-854e-1a7da11b75c2" />
**This is the Image showing the churn rate of the above 40 years of age group**



<img width="167" alt="Screenshot 2025-06-08 at 10 04 44 PM" src="https://github.com/user-attachments/assets/248811b5-8200-48bf-b856-9776863cefbf" />
**This is the Image showing the churn rate of the below 40 years of age group**






