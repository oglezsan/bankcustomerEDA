# bankcustomerEDA
The goal of this research is To identify key factors influencing customer churn and select the best model for predicting customer churn.

## The dataset
The dataset includes customer information such as Credit Score, Age, Tenure, Balance, Number of Products, Credit Card Holding, Active Membership, Estimated Salary, Geography, Gender, and Card Type.

## Models evaluated
Random Forest
Naive Bayes
Decision Tree
K-Nearest Neighbors (KNN)
Ensemble Model: Combined Random Forest and Naive Bayes

### Models performance
Random Forest: Accuracy - 87%, AUC - 87%
Naive Bayes: Accuracy - 82%, AUC - 79%
Decision Tree: Accuracy - 80%, AUC - 71%
KNN: Accuracy - 84%, AUC - 78%
Ensemble Model: Accuracy - 86%, AUC - 85%
Conclusion: Random Forest is the best performing model with the highest accuracy and AUC.

### Key features
Key Features Identified:
Age
Balance
Number of Products
Estimated Salary
Geography
Gender
Insight: The most important features influencing customer churn are Age, Balance, and Number of Products.

### Busines insights
Age:
Older customers tend to churn more.
Action: Implement engagement strategies specifically tailored to older customers, such as personalized offers, senior customer programs, and improved support services.

Balance:
Customers with higher balances are less likely to churn.
Action: Develop loyalty programs or benefits for customers with significant account balances to retain them.

Number of Products:
Customers with more products are less likely to churn.
Action: Encourage customers to use more products through cross-selling and bundling strategies.

Estimated Salary:
Higher salary customers tend to churn less.
Action: Focus retention efforts on customers with lower salaries by providing value-added services and affordable product options.

Geography:
Significant differences in churn rates based on geography.
Action: Develop region-specific retention strategies to address unique needs and preferences.

Gender:
Gender has a significant influence on churn.
Action: Customize communication and engagement based on gender-specific preferences and behaviors.

### Recommended actions
Customer Segmentation: Segment customers based on key features such as age, balance, and number of products to tailor retention strategies.
Personalized Engagement: Use personalized marketing and customer service approaches to improve customer experience and reduce churn.
Loyalty Programs: Develop loyalty programs that reward customers for maintaining higher balances and using multiple products.
Region-Specific Strategies: Implement targeted retention strategies based on geographical differences in churn behavior.
Regular Monitoring: Continuously monitor and update the model to ensure it remains accurate and relevant with new data.

### Next steps
Implementation: Integrate the Random Forest model into the company's CRM system for real-time churn prediction.
Testing: Conduct A/B testing to evaluate the effectiveness of the recommended actions.
Feedback Loop: Establish a feedback loop to refine the model and retention strategies based on customer feedback and new data.

### Conclusion
Summary: The Random Forest model provides the best accuracy and insights into key factors influencing customer churn. By implementing targeted retention strategies based on these insights, the company can effectively reduce churn and improve customer loyalty.
Call to Action: Move forward with the integration and testing of the model, and continuously monitor its performance to ensure ongoing success.