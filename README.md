# Customer Churn Analysis
Analyzed bank customers' demographics and account features using Microsoft Excel to identify factors driving customer churn, and providing insights to enhance retention efforts.

## Key Insights
![customer churn report_1.jpg](https://github.com/jakejosh6751/Customer-Retention-Analysis/blob/main/customer%20churn%20report_1.jpg)
![customer churn report_2.jpg](https://github.com/jakejosh6751/Customer-Retention-Analysis/blob/main/customer%20churn%20report_2.jpg)

- The majority of customers have not churned, but a significant portion (20%) have.
- Older customers are more likely to churn with a noticeable peak around the forties to sixties.
- Germany's churn rate is double that of France and significantly higher than Spain's, indicating an urgent need for targeted retention.
- Female customers exhibit a higher churn rate, signaling a potential need to address gender-specific preferences.
- Customers with lower credit scores have the highest churn rate.
- Inactive customers have almost double the churn rate of active customers.
- Churn risk increases sharply for high balance customers and remains moderate across mid-tier balances.
- Customers with 2 products are the most stable. Interestingly, customers with 3 or 4 products have higher churn rates.

## Common Attributes of Churners
- Age: Older
- Geography: German
- Gender: Female
- Credit Score: Lowest
- Activity Status: Inactive
- Bank Balance: Highest
- Number of Products: 3 & 4

## Key Retention Strategies
1. Offer loyalty programs with perks like fee waivers and personalized services to retain highvalue customers.
2. Identify and target inactive customers with tailored offers and product recommendations to reduce churn.
3. Promote relevant product bundles to increase engagement and reduce churn linked to product usage. Additional data on specific products would strengthen this analysis.
4. Develop targeted offers and engagement strategies for female customers.

## Churn Prediction Feasibility
Churn can be predicted using machine learning models (e.g., Logistic Regression, Random Forest) with these variables. Factors like age, bank balance, geography, and activity status would likely be strong predictors of churn.

## Techniques & Procedures

#### Data Import and Cleaning:
A dataset containing 13 features, including "Credit Score", "Geography", "Gender", and "Age" among others, with 10,000 records, was imported into Excel as a single table. Upon review, no missing data or duplicate records were identified.

#### Pivot Tables and Calculations:
Pivot tables were created in separate sheets for each feature to analyze impact on customer churn.

The "Show Values As" % of Row Total feature in pivot tables was utilized to calculate churn percentages for categorical features and grouped numerical features.

#### Header & Category Labeling:
For better readability and intuition, feature names and categories were renamed as follows:

- "CreditScore" renamed to "Credit Score."
- "NumOfProducts" renamed to "Number of Products."
- "HasCrCard" renamed to "Has Credit Card."
- "IsActiveMember" renamed to "Active Customer."
- "Exited" renamed to "Churned."
- Binary values ("0, 1") in "Has Credit Card" and "Active Customer" were converted to "No, Yes."
- Binary values ("0, 1") in "Churned" were replaced with "Retained, Churned."

#### Data Exploration and Visualization:
- Pie Chart: Illustrated the proportion of "Retained" vs. "Churned" customers, providing a clear view of customer retention dynamics.
- Bar and Column Charts: Were leveraged to analyze churn contribution—categorical features were broken down by percentage impact on churn, while numerical features were aggregated to highlight their influence on customer attrition.
