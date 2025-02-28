# Customer Retention Analysis
![banner - retention analysis.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/banner%20-%20retention%20analysis.jpg)

## Project Overview

Analyzed customer demographics, account features, and transactions using Microsoft Excel to identify factors driving customer churn and provide insights to improve retention.

## Key Objectives
- Clean and prepare the data to ensure accuracy and consistency.
- Perform exploratory data analysis (EDA) to uncover customer trends and behaviors.
- Identify key differences between churned and retained customers.
- Segment customers to identify high-risk groups for targeted retention efforts.
- Develop actionable insights and recommendations for improving customer retention strategies.

## Key Insights
![churn distribution.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/churn%20distribution.jpg)
![credit score.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/credit%20score.jpg)
![geography.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/geography.jpg)
![gender.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/gender.jpg)
![age.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/age.jpg)
![balance.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/balance.jpg)
![num of products.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/num%20of%20products.jpg)
![activity.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/activity.jpg)
![key churn attributes.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/key%20churn%20attributes.jpg)
![further.jpg](https://github.com/jakejosh6751/Bank-Customer-Retention-Analysis/blob/main/further.jpg)

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
