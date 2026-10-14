# Customer Churn Prediction

## Overview
An end-to-end machine learning project that predicts customer churn using historical telecom customer data. The project aims to help businesses identify customers at risk of leaving and prioritize retention efforts.

## Objectives
- Explore customer characteristics and churn patterns.
- Clean and preprocess numerical and categorical features.
- Train and compare multiple classification models.
- Tune the classification threshold to improve churn detection.
- Segment customers into low-, medium-, and high-risk groups.

## Dataset
IBM Telco Customer Churn dataset, containing customer demographics, subscribed services, contract information, billing details, and churn labels.

## Tech Stack
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow
1. Data collection and exploratory data analysis.
2. Data cleaning, missing-value imputation, encoding, and scaling.
3. Model training and evaluation.
4. Business insights, risk segmentation, and recommendations.

## Models Compared
- Logistic Regression
- Decision Tree
- Random Forest
- Soft Voting Ensemble

## Key Results
- Logistic Regression at threshold 0.50: accuracy 80.55%, F1-score 0.604, ROC-AUC 0.8419.
- Threshold-tuned Logistic Regression at threshold 0.35: recall 70.59%, F1-score 0.6147, accuracy 76.51%, ROC-AUC 0.8419.
- Test-set customer risk groups showed observed churn rates of 10.62% for low risk, 39.52% for medium risk, and 71.77% for high risk.

Note: The test set was used for multiple model comparisons. These results are exploratory and should not be interpreted as an unbiased final estimate of generalization performance.

## Business Value
Risk segmentation can help retention teams prioritize customers for outreach, investigate service issues, and evaluate targeted retention campaigns.

## Limitations
- Historical dataset with no guarantee of representing future customers.
- Predictions indicate risk, not the cause of churn.
- Retention recommendations require business validation.
- An untouched holdout evaluation and probability calibration are future improvements.

## How to Run
1. Open the notebooks in Google Colab.
2. Run the notebooks in numerical order.
3. Download or obtain the dataset as described in the first notebook.
4. Follow the preprocessing and model-training steps.
5. Review evaluation metrics and customer risk segmentation.