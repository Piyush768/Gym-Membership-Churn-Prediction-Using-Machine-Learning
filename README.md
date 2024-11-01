# Gym Membership Churn Prediction Using Machine Learning

## Project Overview
This project leverages machine learning to predict customer churn within a gym membership context. The goal is to build a model that accurately identifies members at high risk of cancellation. By understanding the key factors behind member attrition, this model provides gym owners with actionable insights to retain customers and enhance engagement.

## Business Problem
High churn rates in the fitness industry can significantly impact revenue and brand reputation. This project aims to:
- Predict which members are likely to churn.
- Understand key drivers influencing member retention.
- Help gym owners develop targeted retention strategies for high-risk customers.

## Data Description
The dataset contains several key attributes relevant to customer behavior and engagement, including:
- **Demographics:** Age, Gender, Location.
- **Contract Details:** Contract length, start date, renewal date.
- **Usage Patterns:** Visit frequency, class attendance, additional charges.
- **Engagement Indicators:** Partner or friend referrals, group visit history, phone engagement.

## Project Structure
- **Data Understanding and Preparation:** Analyzed missing values, conducted EDA, and performed feature engineering.
- **Modeling:** Trained multiple machine learning models (Logistic Regression, Random Forest, XGBoost, and SVM) to predict churn.
- **Evaluation:** Compared models based on Precision, Recall, F1-Score, and AUPRC (Area Under Precision-Recall Curve).

## Evaluation and Results
| Model             | AUPRC | F1   | Precision | Recall |
|-------------------|-------|------|-----------|--------|
| Logistic Regression | 0.932 | 0.852 | 0.848     | 0.856  |
| Random Forest       | 0.955 | 0.883 | 0.886     | 0.881  |
| SVM                 | 0.947 | 0.867 | 0.878     | 0.856  |
| XGBoost             | 0.957 | 0.889 | 0.887     | 0.891  |

The **XGBoost** model demonstrated the best performance, with the highest AUPRC and a balanced F1-Score, making it the recommended model for predicting churn.

## Key Insights and Recommendations
- **Risk Indicators:** Younger members (ages 25-30), low visit frequency, and shorter contract lengths are linked to higher churn rates.
- **Retention Strategies:**
  - **Early Engagement:** Focus on members' first few months.
  - **Flexible Contracts:** Offer more contract options and loyalty programs.
  - **Community Building:** Expand group activities and buddy systems to increase retention.
- **Success Metrics:** Reduced churn rate, higher contract renewals, improved member satisfaction.
