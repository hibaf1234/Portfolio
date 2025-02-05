# Retail Marketing Analytics

# Python Project

## Overview
This project explores marketing analytics using Python, focusing on retail campaign performance, customer segmentation, and predictive modeling. The analysis is driven by two datasets:
- **Marketing Campaigns Dataset**: Contains information about advertising campaigns across multiple platforms.
- **Marketing Sales Dataset**: Holds transactional data linked to marketing campaigns.

## Key Features
- **Exploratory Data Analysis (EDA)**: Uncovers trends in sales, conversion rates, and click-through rates.
- **Customer Segmentation**: Uses K-Means clustering to categorize customers based on purchasing behavior.
- **Predictive Modeling**: Identifies high-value customers using logistic regression and random forest classifiers.
- **A/B Testing**: Evaluates the statistical significance of different marketing strategies.

## Data Sources
- **Marketing Campaigns Dataset** (`marketing_campaigns_data.csv`): Contains 500 records detailing campaign ID, platform, impressions, clicks, conversions, spend, and targeting parameters.
- **Marketing Sales Dataset** (`marketing_sales_data.csv`): Consists of 100,000 transactions, including customer purchases, discounts applied, and payment methods.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Manipulation)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-learn** (Machine Learning)
- **Statsmodels** (Statistical Analysis)
- **CausalImpact** (Impact Evaluation)
- **SMOTE** (Imbalanced Data Handling)

## Analysis Breakdown
### 1. Data Preprocessing
- Converts date columns to `datetime` format.
- Identifies and removes missing values and duplicates.
- Standardizes numeric features for machine learning models.

### 2. Exploratory Data Analysis (EDA)
- **Sales Trends Over Time**: Visualizes seasonal trends and sales fluctuations.
- **Conversion Rate by Campaign**: Analyzes effectiveness across platforms.
- **Click-Through Rate (CTR)**: Evaluates engagement across different ad campaigns.
- **Return on Ad Spend (ROAS)**: Assesses campaign efficiency and profitability.

### 3. Customer Segmentation
- **K-Means Clustering**: Groups customers into segments based on sales amount and basket size.
- **High-Value Customers**: Identifies the top 10% of customers based on lifetime value.

### 4. Predictive Modeling
- **Logistic Regression**: Predicts high-value customers with SMOTE for class balancing.
- **Random Forest Classifier**: Achieves better performance (78% accuracy) over logistic regression (56%).

### 5. A/B Testing
- Compares average sales between `In-Store` and `Online` purchases using a t-test.
- Findings indicate no significant difference in spending behavior across channels (p-value = 0.53).

## Results & Insights
- **High-Performing Platforms**: Snapchat and Google Ads drive the highest conversion rates.
- **Optimization Opportunities**: Instagram underperforms, suggesting room for improvement.
- **Personalization Strategies**: Customer segmentation enables better marketing decisions.
- **Random Forest Model Outperforms**: More reliable predictions for high-value customers.


## Future Work
- Implement deep learning models for customer prediction.
- Use time-series forecasting to predict future campaign performance.
- Integrate real-time A/B testing methodologies.



