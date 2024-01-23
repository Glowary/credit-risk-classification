# Credit Risk Classification Project

This project focuses on developing machine learning models for credit risk classification based on historical lending data. The goal is to predict the creditworthiness of borrowers, distinguishing between low-risk `0` and high-risk `1` loans.

## Files
- `credit_risk_classification.ipynb`: Jupyter Notebook containing the code for data preparation, model development, and evaluation.
- `lending_data.csv`: Dataset file with historical lending activity.

## Process
Data Splitting and Preprocessing
Step 1: Read Data into Pandas DataFrame
Step 2: Create Labels and Features
Step 3: Check Label Balance
Step 4: Split Data into Training and Testing Sets

Logistic Regression Model with Original Data
Step 1: Fit Logistic Regression Model
Step 2: Save Predictions
Step 3: Evaluate Model Performance
Step 4: Model Analysis

Logistic Regression Model with Resampled Data
Step 1: Resample Data with RandomOverSampler
Step 2: Fit Logistic Regression Model with Resampled Data
Step 3: Evaluate Resampled Model Performance
Step 4: Resampled Model Analysis

## Method
- Logistic Regression: Applied Logistic Regression as the primary classification algorithm.
- Random OverSampler: Utilized Random OverSampler from the imbalanced-learn library to address class imbalance in the training data.


## Results
<image 1>
<image 2>

## Summary
The model with resampled data outperforms the original imbalanced model in terms of accuracy, precision, and recall for both healthy and high-risk loans. The oversampled model is more balanced and provides a higher level of confidence in predicting credit risk. The imbalanced model might be biased towards predicting healthy loans, leading to potential financial risks for the lending company. The oversampled model is the preferred choice for minimizing the risk of approving high-risk loans.
