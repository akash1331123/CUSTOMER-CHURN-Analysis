# Customer Churn Analysis
This project focuses on analyzing customer churn within the telecom industry. Customer churn occurs when customers discontinue their service with a company. This is a critical business issue as it is much more expensive to acquire new customers than to retain existing ones. By predicting which customers are likely to churn, telecom companies can take proactive measures to retain them.

#Objective
The primary goal of this analysis is to explore customer data to understand churn patterns and answer key business questions, such as:
What percentage of customers are churning, and what percentage remain active?
Are there patterns in customer churn based on demographic factors like gender?
How does the type of service influence churn behavior?
Which services and features are most profitable?
What are the key factors contributing to customer churn?

#Dataset
The dataset contains detailed information about:
Customers who left in the last month (churn label)
Services each customer signed up for (e.g., phone, internet, security, etc.)
Customer account information (e.g., contract type, payment method, monthly charges)
Customer demographics (e.g., age, gender, dependents, and partners)

#Key Insights
Churn Rate: 26.6% of customers switched providers, with minimal gender difference.
Contract Type: Month-to-Month contracts saw the highest churn, while longer-term contracts had lower churn rates.
Payment Method: Electronic check users showed higher churn rates, while customers using automatic transfers or mailed checks were more stable.
Service Type: Fiber optic users had higher churn, potentially indicating dissatisfaction.
Customer Profile: Single customers and senior citizens were more likely to churn.
Service Features: Lack of online security, paperless billing, and tech support increased churn likelihood.
Monthly Charges: Higher monthly charges, especially for new customers, were associated with increased churn.

#Modeling & Performance
Multiple machine learning models were used to predict churn, with the Random Forest Classifier achieving the best accuracy of 81.37%. The model effectively identifies at-risk customers, allowing businesses to focus on retention efforts.

#Conclusion
Understanding customer churn and its underlying causes is key to improving retention strategies. By predicting churn and addressing the needs of high-risk customers, businesses can maintain profitability and grow their customer base.
