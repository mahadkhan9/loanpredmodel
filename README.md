# Overview

## 1. Problem
The primary business challenge was to identify the best candidates for personal loan offers, enabling the bank to optimize marketing spend and increase loan uptake. The goal was to leverage customer data to predict which customers are most likely to accept a personal loan, thereby enhancing the bank's profitability and customer targeting efficiency.

## 2. Approach Taken
We employed a data-driven approach using logistic regression since our prediction variable was personal 'loan' which is a binary variable. 
The process involved:
1. Data Collection and Cleaning: Ensuring data quality by handling missing values and irrelevant features.
2. Feature Engineering: Transforming and encoding features to capture meaningful patterns.
3. Model Development: Building a logistic regression model with regularization to prevent overfitting.
4. Hyperparameter Tuning: Optimizing model parameters to enhance performance.

## 3. Process
1. Data Preprocessing: We conducted exploratory data analysis, then encoded categorical variables and applied (log and power) transformations to manage skewness.
2. Model Training: The dataset was split into training and testing sets, and logistic regression was applied.
3. Evaluation: The model was evaluated using metrics like accuracy, precision, and ROC AUC.
4. Feature Importance Analysis: We analyzed the impact of each feature on loan acceptance to gain business insights.

## 4. Results
The model achieved a high AUC score of 0.958, indicating excellent discriminative power. Key features influencing loan acceptance included CD accounts, education level, and account types. The model's precision and recall were balanced to ensure effective targeting of potential loan acceptors. Customers with CD (Certificate of Deposit) accounts and higher education levels are more likely to accept loans, guiding targeted marketing strategies.

*Note: The model was based on data analysis, demographic factors, and understanding of the financial sector.*
