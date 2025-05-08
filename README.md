# Customer-Churn-Project
## Project Overview

This project focuses on predicting customer churn in the telecom industry using a real-world dataset. By applying machine learning techniques such as logistic regression and decision trees, the aim is to identify patterns that lead to customer loss. The analysis follows the CRISP-DM methodology and includes data cleaning, exploratory analysis, model building, evaluation, and business recommendations. The final deliverables include a tableau dashboard and a stakeholder-friendly presentation.

## Business Problem

Customer churn is a major concern in the telecommunications industry. It impacts revenue and growth, and retaining existing customers is often more cost-effective than acquiring new ones. The goal is to predict churn early enough so that the company can proactively engage and retain these customers.

## Objectives

Predict whether a customer will churn or not using service and behavior data.

Build and evaluate a baseline model and a more advanced model.

Recommend the better model.

Translate findings into actionable business insights.

## CRISP-DM Methodology

### 1. Business Understanding

Objective: Reduce customer churn by predicting high-risk individuals.

Value: Increased customer retention results to a higher revenue.

### 2. Data Understanding 

Source: bigml_59c28831336c6604c800002a.csv

Rows: 3333  Features: 21

Key columns: intentional plan, voice mail plan, total day minutes, customer calls, churn

### 3. Data Preparations(Cleaning)

Dropped all irrelevant features like state, phone number.

Checked for duplicates and null values.

Scaled numerical features for model compatibility.
