Telco Customer Churn Analysis and Prediction
Project Overview

This project analyzes a real-world telecom customer churn dataset to extract meaningful insights and build a basic machine learning model to predict customer churn.

The objective of this project is to demonstrate the ability to:

Understand and clean real-world data

Perform exploratory data analysis (EDA)

Engineer relevant features

Build and evaluate a machine learning model

Translate analytical results into business-oriented insights

This project was completed as part of an internship assessment.

Dataset Description

The dataset contains customer-level information related to:

Customer demographics

Services subscribed

Billing and payment details

Contract information

Churn indicators

Target Variable

Churn Value

1 → Customer churned

0 → Customer did not churn

This is a binary classification problem.

Tools and Technologies Used

Programming Language: Python

Libraries:

pandas, numpy – data manipulation

matplotlib, seaborn – data visualization

scikit-learn – machine learning and evaluation

Environment: Jupyter Notebook

Project Workflow
1. Data Understanding and Cleaning

Loaded the dataset and inspected its structure

Identified missing values and calculated the percentage of missing values per column

Converted Total Charges to numeric format

Removed rows with missing or invalid values (minimal data loss)

Identified categorical and numerical features

Checked for obvious outliers in numerical columns

2. Exploratory Data Analysis (EDA)

Analyzed the distribution of churned vs non-churned customers

Generated basic statistics such as mean and median

Created meaningful visualizations:

Churn distribution

Correlation heatmap

Feature vs target relationship plots

Documented clear observations from each visualization

3. Feature Engineering

Selected relevant numerical features for modeling

Encoded the target variable

Scaled numerical features using StandardScaler

Performed feature selection based on correlation and business understanding

4. Model Building

Split the dataset into training and testing sets

Built a Logistic Regression model as a baseline classifier

Trained the model and generated predictions

Why Logistic Regression?

Suitable for binary classification

Easy to interpret

Provides a strong baseline for churn prediction

5. Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

F1-score

Metric Justification:

Recall is important in churn prediction because missing a churned customer is more costly than contacting a non-churned customer

F1-score provides a balanced measure of model performance

Key Insights

Customers with short tenure are more likely to churn

Month-to-month contracts have the highest churn rate

Higher monthly charges are associated with increased churn

Long-term contracts significantly reduce churn risk

Business Recommendations

Encourage customers on month-to-month contracts to switch to long-term plans using discounts or incentives

Introduce loyalty programs for customers who complete key tenure milestones

Target high-risk customers with personalized retention offers

Additional Data That Could Improve the Model

Customer support and complaint history

Usage behavior trends (data usage, call frequency)

Payment behavior and billing issues

Network and service quality metrics

Customer engagement data

How to Run the Project

Place Telco_Churn_Assignment.ipynb and Task.csv in the same directory

Open the notebook using Jupyter Notebook or JupyterLab

Run all cells sequentially from top to bottom

Author

Deep
Aspiring Data Analyst and Machine Learning Enthusiast

Final Note
