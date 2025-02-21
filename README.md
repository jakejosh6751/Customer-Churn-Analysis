# Bank Customer Retention Analysis

## Project Overview

Loss of existing customers is a significant challenge for banks and other businesses, as it directly impacts profitability and long-term growth. Understanding the factors driving churn is crucial for developing targeted retention strategies that can enhance customer satisfaction and reduce attrition rates.

This project focuses on analyzing customer demographics, account features, and transactional behaviors using Microsoft Excel to uncover patterns associated with customers at risk of leaving the bank. By identifying these factors, we aim to provide actionable insights to help improve customer retention efforts.

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
![gender.jpg]()
![age.jpg]()
![balance.jpg]()
![num of products.jpg]()
![activity.jpg]()
![key insights.jpg]()
![further.jpg]()
![recommendations.jpg]()

## Recommendations

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
