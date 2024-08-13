Project Description: Customer Churn Prediction and Analysis

Objective:
The primary objective of this project was to develop predictive models to identify customers at high risk of churn and to analyze key factors influencing customer retention. By leveraging advanced statistical techniques and machine learning algorithms, we aimed to provide actionable insights and strategic recommendations to enhance customer retention and optimize revenue.

Data Overview:
The dataset used for this analysis encompasses a comprehensive range of customer information from a telecommunications company. The key attributes include:

Customer Tenure: Duration of the customer's relationship with the company.
Contract Type: Type of contract agreement (e.g., month-to-month, one year, two years).
Payment Method: Method used for billing (e.g., electronic check, mailed check, bank transfer).
Monthly Charges: The monthly fee charged to the customer.
Total Charges: Total amount billed to the customer over their tenure.
Internet Service: Type of internet service subscribed to (e.g., DSL, fiber optic, no internet).
Online Security, Tech Support, Device Protection: Additional services subscribed to.
Senior Citizen: Indicator of whether the customer is a senior citizen.

Methodology:
Exploratory Data Analysis (EDA): Conducted to understand the distribution and relationships of the data variables, identify missing values, and uncover patterns that might influence churn.

Model Development:
Linear Discriminant Analysis (LDA) and Quadratic Discriminant Analysis (QDA) were employed to classify customers based on churn risk.
Decision Trees, Random Forests, and Gradient Boosting Machines (GBM) were used to capture complex interactions between features and churn.
Logistic Regression and Naive Bayes models were applied for comparison and validation purposes.

Model Evaluation:
Evaluated models based on metrics such as AUC (Area Under the Curve), accuracy, and ROC curves.
Optimized thresholds to balance false positives and false negatives.

Key Findings:
Model Performance: Logistic Regression and Naive Bayes models demonstrated superior performance with higher AUC values and accuracy, indicating better predictive capabilities.
Significant Factors: Key predictors of churn included customer tenure, monthly charges, contract type, and internet service. Specifically, customers with month-to-month contracts and higher monthly charges exhibited higher churn rates.
Customer Segmentation: Analysis revealed that customers on electronic check payment methods and those with fiber-optic internet services had higher churn rates.

Recommendations:
Customer Retention Strategies: Focus on retaining customers with short tenures and those on month-to-month contracts by offering incentives for longer-term commitments.
Pricing Adjustments: Review and adjust pricing strategies to address the churn associated with high monthly charges.
Service Improvement: Enhance service quality and customer support to reduce churn rates among fiber-optic internet users and electronic check payers.
Loyalty Programs: Implement a tiered loyalty program to offer personalized discounts and rewards based on customer spending and tenure.
Financial Impact
Predicted Loss: Monthly revenue loss from at-risk customers was estimated at $25,765.10, with a potential churn revenue loss of $16,104.94.
Incentive Scheme Proposal: A tiered loyalty program with an estimated cost of $80,000 could generate additional revenue of $200,000, leading to a net benefit of $420,000.
