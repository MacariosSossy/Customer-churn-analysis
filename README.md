# Customer Churn Analysis (Telecom)

## Overview
This project analyzes customer churn behavior in a telecom company and identifies the main factors that influence customer retention.

The objective is to move beyond prediction and provide business recommendations that reduce churn risk.

## Dataset
- 7,043 telecom customers
- Demographic, billing, service, and contract data
- Target variable: customer churn

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Logistic Regression

## Project Workflow

### 1. Data Exploration
- Analyzed churn distribution
- Examined tenure and pricing patterns
- Identified service adoption differences

### 2. Data Preparation
- Handled missing values
- Converted TotalCharges to numeric
- Applied one-hot encoding
- Created modeling dataset

### 3. Modeling
- Logistic regression model
- Train/test split
- Identified churn probability drivers

### 4. Key Insights
- Month-to-month contracts increase churn risk
- Lack of tech support and security correlates with churn
- Electronic check users show higher churn behavior
- Senior customers show slightly higher churn

### 5. Business Recommendations
- Promote long-term contracts
- Bundle security and support services
- Target high-risk billing segments
- Focus retention on early-tenure customers

## Results
Model accuracy: **78.7%**

The model successfully identifies high-risk churn segments and provides actionable business insights.

## Author
Macarios Sossy
