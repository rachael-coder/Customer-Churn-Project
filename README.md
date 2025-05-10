# Customer-Churn-Prediction-Project
### Name: Rachael Nyawira

## Project Overview

This project focuses on predicting customer churn in the telecom industry using a real-world dataset. By applying machine learning techniques such as logistic regression and decision trees, the aim is to identify patterns that lead to customer loss. The analysis follows the CRISP-DM methodology and includes data cleaning, exploratory analysis, model building, evaluation, and business recommendations. The final deliverables include a tableau dashboard and a stakeholder-friendly presentation.

## Business Problem

Customer churn is a major concern in the telecommunications industry. It impacts revenue and growth, and retaining existing customers is often more cost-effective than acquiring new ones. The goal is to predict churn early enough so that the company can proactively engage and retain these customers.

## Objectives

Predict whether a customer will churn or not based on certain features.

Build and evaluate a baseline model and a more advanced model.

Recommend the better model.

Translate findings into actionable business insights.

## CRISP-DM Methodology

### 1. Business Understanding

Objective: Reduce customer churn by predicting high-risk individuals.

Value: Increased customer retention results to a higher revenue.

### 2. Data Understanding 

Data Source: Kaggle

Data: bigml_59c28831336c6604c800002a.csv

Rows: 3333  

Features: 20 attributes including:

Demographics(state, area code)

Service usage (day/eve/night minutes, customer service calls)

Plans(international, voice mail)

Churn status(target variable)

Key columns: intentional plan, voice mail plan, total day minutes, customer calls, churn

### 3. Data Preparations(Cleaning)

Dropped all irrelevant features like phone number.

Checked for duplicates and null values(none found).

Converted categorical variables to numerical format.

Scaled numerical features for model compatibility.

### 4. Exploratory Data Analysis(EDA)

Key Questions

a. What proportion of customers churned vs stayed?

b. Which services are most associated with customer 

c. How does customer service call frequency relate to Churn?

Visualizations created in Tableau include:

Churn distributions

Churn by customer service calls

Churn by international/voice mail plans

### 5. Machine Learning Models
Two models were trained and evaluated.

The base model is Logistic Regression Model.

The advanced model is the Decision Tree Model

The better model appears to be the Decision Tree.

The Decision Tree model has a significantly higher accuracy, better precision and also a better F1 score.

Evaluation metrics used: 

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC AUC

### 6. Tableau Dashboard

https://public.tableau.com/app/profile/rachael.nyawira/viz/CustomerChurndashboard_17468769663000/Dashboard1?publish=yes

### 7. Findings and Recommendations

 #### Findings
 
1. There is a low churn rate. The smaller height of the 'True' bar signifies that the overall churn rate within this dataset is relatively low. A large majority of the customers are retained.

There is also a significant class imbalance 

2. Customers without an international plan churn at a lower rate than those with a plan.

The number of customers with the international plan who churn is higher than the number of customers with the international plan who do not churn.

3. Customers who interact more frequently with customer service are at a higher risk of churning.
Customers who have made 3-4 customer service calls are a critical segment to target for churn prevention efforts

#### Recommendation

1. While a low churn rate is generally positive for the business, the significant class imbalance in the dataset needed to be carefully addressed during the model development and evaluation to ensure the building of a predictive model that can effectively identify and help prevent churn.

2. Re-evaluate international plans by:

a. Understanding reasons for high churn rate in international plan users by conducting surveys or analyze the usage patterns and feedback from customers with international plans

b. Consider targeted offers or plan adjustments: Based on the findings, explore offering specialized international plans, discounts, or features that better cater to the needs of international users and improve their satisfaction.

3. Enhance Customer Service by:

a. Improving First Call Resolution: Focus on equipping customer service agents with the knowledge and resources to resolve customer issues effectively during the first interaction.

b.Proactive Outreach for Multiple Callers: Implement a system to identify customers who have contacted customer service multiple  times. Proactively reach out to understand their ongoing issues and offer tailored solutions or support.
