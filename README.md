Telco Customer Churn Analysis & Prediction
Project Overview

This project focuses on analyzing a real-world telecom customer churn dataset to identify key factors influencing customer churn and to build a basic machine learning model for churn prediction.

The goal is to demonstrate the ability to:

Understand and clean real datasets

Perform exploratory data analysis (EDA)

Engineer relevant features

Build and evaluate a machine learning model

Translate technical results into business insights

This project was completed as part of an internship assessment.

Dataset Description

The dataset contains customer-level information including:

Demographics (gender, location)

Service details (internet service, contract type)

Billing information (monthly charges, total charges)

Customer behavior indicators

Churn information

Target Variable:

Churn Value

1 → Customer churned

0 → Customer did not churn

This is a binary classification problem.

Tools & Technologies Used

Programming Language: Python

Libraries:

pandas, numpy (data manipulation)

matplotlib, seaborn (visualization)

scikit-learn (modeling & evaluation)

Environment: Jupyter Notebook

Project Workflow
1. Data Understanding & Cleaning

Loaded the dataset and examined its structure

Identified missing values and calculated missing percentages

Converted Total Charges to numeric format

Removed rows with invalid or missing values (minimal data loss)

Identified numerical and categorical features

Checked for obvious outliers

2. Exploratory Data Analysis (EDA)

Analyzed the distribution of churn vs non-churn customers

Generated basic statistics for numerical features

Created key visualizations:

Target variable distribution

Correlation heatmap

Feature-to-target relationship plots

Documented clear observations from each visualization

3. Feature Engineering

Selected relevant numerical features

Encoded the target variable

Applied feature scaling using StandardScaler

Chose features based on correlation and business understanding

4. Model Building

Split the data into training and testing sets

Built a Logistic Regression model as a baseline classifier

Trained the model and generated predictions

Why Logistic Regression?

Suitable for binary classification

Easy to interpret

Strong baseline for churn prediction problems

5. Model Evaluation

Evaluated the model using:

Accuracy

Precision

Recall

F1-score

Metric Justification:

Recall is especially important in churn prediction, as missing a churner is more costly than contacting a non-churner.

F1-score provides a balance between precision and recall.

Key Insights

Customers with shorter tenure are more likely to churn

Month-to-month contracts show significantly higher churn rates

Higher monthly charges are associated with increased churn

Long-term contracts help reduce customer churn

Business Recommendations

Encourage month-to-month customers to switch to long-term contracts through discounts or benefits

Introduce loyalty programs for customers completing key tenure milestones

Provide targeted offers to customers with high monthly charges

Possible Improvements

Include customer support and complaint data

Add usage behavior metrics (call/data usage trends)

Experiment with advanced models such as Random Forests or Neural Networks

Address class imbalance using resampling techniques

How to Run the Project

Place Telco_Churn_Assignment.ipynb and Task.csv in the same directory

Open the notebook in Jupyter Notebook or JupyterLab

Run cells sequentially from top to bottom

Author

Deep
Aspiring Data Analyst / Machine Learning Enthusiast
