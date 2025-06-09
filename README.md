# Bank-Customer-Churn-Analysis

## Table of Contents
1. Background and overview.
2. Executive summary.
3. Insights deep dive.
4. Recommendations.
   
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

An interactive Tableau dashboard can be viewed [here](https://public.tableau.com/app/profile/venkata.sudheer.ayalasomayajula/viz/Book1_17492593107170/Dashboard1)

The raw dataset used can be found [here](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)

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

**This is the image showing the churn rate of customers in Germany.**

👤 **Age Distribution**
- The Age Group above 40 years is most likely to churn, with a churn rate of almost 45%.
- Whereas the age group below 40 years is showing loyalty with a nearly 13% churn rate.



<img width="182" alt="Screenshot 2025-06-08 at 10 04 24 PM" src="https://github.com/user-attachments/assets/3548cb70-a4aa-4bdb-854e-1a7da11b75c2" />

**This is the Image showing the churn rate of the above 40 years of age group.**



<img width="167" alt="Screenshot 2025-06-08 at 10 04 44 PM" src="https://github.com/user-attachments/assets/248811b5-8200-48bf-b856-9776863cefbf" />

**This is the Image showing the churn rate of the below 40 years of age group.**

💸 **Salary Segments**
- Churn rates across all income brackets are relatively stable at ~20%, but there is a slight uptick to 22% for those earning above $150k. This suggests that high earners are not necessarily more loyal, and premium service expectations may need to be reassessed.

<img width="165" alt="Screenshot 2025-06-08 at 10 16 10 PM" src="https://github.com/user-attachments/assets/d3001119-71a1-4783-9f5d-3f35cc50c8c3" />

**This is the image showing the churned customers who are earning a salary above 150k.**

💳 Credit Score
- Customers with lower credit scores (350–584) show a churn rate of around 14%, slightly higher than those with higher scores.
- The churn rate decreases to 12% for scores between 652 and 718, suggesting better financial habits correlate with retention.
  
🟢 IsActiveMember
Active members have a churn rate of only 9.55%, compared to 16.38% for inactive members, which reflects the importance of customer engagement in reducing churn.


<img width="163" alt="Screenshot 2025-06-09 at 3 28 03 PM" src="https://github.com/user-attachments/assets/a351e36e-c3fd-45df-ba0a-776bae93eb60" />

**This is the image showing the churned customers who are active.**


<img width="168" alt="Screenshot 2025-06-09 at 3 27 27 PM" src="https://github.com/user-attachments/assets/376c93fc-1bfe-4d9e-be15-d506cf92ac59" />

**This is the image showing the churned customers who are inactive.**

## Recommendations
Based on the churn analysis, the following recommendations are suggested to improve customer retention:
1. **Focus retention campaigns** on customers aged 40–50, who show the highest churn likelihood. Consider financial wellness programs, investment advisory services, or age-relevant loyalty benefits to address their specific needs and encourage retention.

2. **Actively engage inactive members** through personalized reactivation offers, digital nudges, or rewards for using banking services. The analysis shows that inactive customers are twice as likely to churn compared to active members.

3. **Evaluate customer satisfaction levels across geographies**, especially in Germany, which has a disproportionately high churn rate. Launch location-specific surveys and service audits to identify friction points and optimize regional service delivery.

4. I**mprove transparency and communication** around balance thresholds and financial planning for high-income customers (e.g., those earning above $100,000), who are still exiting despite favorable credit and engagement scores. Consider adding a premium banking tier with concierge services.
