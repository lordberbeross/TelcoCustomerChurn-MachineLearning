# 📊 Telco Customer Churn Prediction & Business Insights

This project focuses on identifying customers likely to leave a telecommunications company. As an analyst the goal was to build a predictive model while extracting actionable insights to help the business reduce churn and increase customer lifetime value.

## 🎯 Business Problem
Customer acquisition costs significantly more than retention. By predicting which customers are at risk of leaving (churning), the company can intervene with targeted marketing strategies to maintain its revenue base.

## 🛠️ Tech Stack & Methodology
- **Language:** Python
- **Libraries:** Pandas (Data Wrangling), Matplotlib & Seaborn (EDA), Scikit-learn (Machine Learning)
- **Framework:** CRISP-DM (Business Understanding -> Data Prep -> Modeling -> Evaluation)
- **Model:** Logistic Regression (Chosen for its high explainability)
  

<img width="589" height="394" alt="image" src="https://github.com/user-attachments/assets/a5ce8123-2e62-4ea3-9069-37de7c6e3479" />



## 📈 Key Insights from EDA
- **Contract Type:** Customers on "Month-to-month" contracts represent the highest churn risk.
- **Pricing Pressure:** A clear correlation was found between higher monthly charges and increased churn rates.
- **Service Quality:** Surprisingly, **Fiber Optic** users have a higher churn rate than DSL users, suggesting potential technical issues or pricing dissatisfaction in this segment.
- **Paperless Billing:** Digital-savvy customers using paperless billing are more likely to switch providers, possibly due to higher market awareness.

## 🤖 Model Performance
- **Accuracy Score:** **78.68%**
- The model provides a solid baseline for identifying high-risk customers before they terminate their service.

  <img width="719" height="461" alt="image" src="https://github.com/user-attachments/assets/a733da19-9ba4-40e0-a66e-2cabbcb2459c" />

## 💡 Strategic Business Recommendations
1. **Contract Incentives:** Launch a campaign to migrate "Month-to-month" users to annual contracts by offering a 10-15% loyalty discount.
2. **Fiber Optic Audit:** Conduct a technical quality-of-service audit for Fiber Optic infrastructure to address potential churn reasons.
3. **Retention Targeting:** Use the model’s risk scores to prioritize outreach from the customer success team, focusing on high-value customers with a churn probability > 70%.

---
*This project is part of my Data Analysis portfolio, demonstrating the bridge between machine learning and business strategy.*
