# Customer Churn Analysis
Analyzed bank customers' demographics, account features, and transactions using Microsoft Excel to identify factors driving customer churn, and providing insights to enhance retention efforts.

## Key Insights
![customer churn report_1.jpg](https://github.com/jakejosh6751/Customer-Retention-Analysis/blob/main/customer%20churn%20report_1.jpg)
![customer churn report_2.jpg](https://github.com/jakejosh6751/Customer-Retention-Analysis/blob/main/customer%20churn%20report_2.jpg)

- Older customers are more likely to churn with a noticeable peak around 40s - 60s.

## Recommendations
![recommendations.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/recommendations.jpg)

## Techniques & Procedures

#### Data Extraction:
A dataset containing 13 features, including "Credit Score," "Geography," "Gender," and "Age," among others, with 10,000 records, was imported into Excel as a single table. Upon review, no missing data or duplicate records were identified.

#### Pivot Tables:
Pivot tables were created in separate sheets for each feature to analyze relationships with customer churn.

#### Data Cleaning Process:
Feature names and categorical values were standardized as follows:

- "CreditScore" renamed to "Credit Score."
- "NumOfProducts" renamed to "Number of Products."
- "HasCrCard" renamed to "Has Credit Card."
- "IsActiveMember" renamed to "Active Customer."
- "Exited" renamed to "Churned."
- Binary values ("0, 1") in "Has Credit Card" and "Active Customer" were converted to "No, Yes."
- Binary values ("0, 1") in "Churned" were replaced with "Retained, Churned."

#### Calculations:
The SUM function and division formulas were utilized to calculate churn percentages for categorical features based on aggregated values from pivot tables.

#### Data Exploration and Visualization:
- Pie Chart: Displayed the distribution of "Retained" and "Churned" customers.
- Conditional Formatting with Data Bars: Applied to illustrate the percentage contribution to churn for distinct categorical feature records.
- Histogram: Visualized the age distribution for both churned and retained customers.
