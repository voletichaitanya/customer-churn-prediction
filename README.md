# Customer Churn Prediction using Machine Learning

## Problem Statement
Customer churn is a major issue in telecom businesses.  
This project predicts whether a customer is likely to churn based on historical usage and contract data.

## Dataset
- Telco Customer Churn Dataset (Kaggle)
- Contains customer demographics, service usage, and churn labels

## Approach
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Encoding (One-Hot Encoding)
4. Model Training and Evaluation

## Models Used
- Logistic Regression
- Random Forest
- XGBoost

## Evaluation Metrics
- Accuracy
- ROC-AUC Score

## Results
| Model | Accuracy | ROC-AUC |
|------|---------|---------|
| Logistic Regression | 0.804 | 0.836 |
| Random Forest | 0.787 | 0.818 |
| XGBoost | 0.782 | 0.826 |

Logistic Regression was selected as the final model based on best ROC-AUC performance.

## Conclusion
The project demonstrates an end-to-end machine learning workflow for customer churn prediction using real-world data.

## Future Improvements
- Hyperparameter tuning
- Feature importance analysis
- Model deployment
