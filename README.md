Credit Risk Prediction

Project Overview

This project uses Machine Learning to predict the credit risk of loan applicants. It classifies customers into two categories: Risk and No Risk, based on their financial and personal information.

The goal is to help understand potential credit risk through data analysis and predictive modeling.

Dataset

The project uses the German Credit Risk dataset.

It contains customer information such as:

Loan Amount

Loan Duration

Credit History

Loan Purpose

Employment Duration

Existing Savings

Age

Housing

Existing Credits Count

Target Variable: Risk

Risk: Applicant is classified as having credit risk.

No Risk: Applicant is classified as having no credit risk.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

Project Workflow

Dataset Loading

Data Exploration and Analysis

Missing Values and Duplicate Checking

Feature and Target Selection

Numerical and Categorical Feature Separation

Data Preprocessing

Train-Test Split

Logistic Regression Model Training

Model Prediction

Model Evaluation

Machine Learning Model

Logistic Regression was used for binary classification.

A preprocessing pipeline was created using:

SimpleImputer for missing values

StandardScaler for numerical features

OneHotEncoder for categorical features

Model Evaluation

The model achieved the following results:

Metric

Score

Accuracy

79.3%

Precision (Risk)

0.74

Recall (Risk)

0.60

F1-Score (Risk)

0.66

Confusion Matrix



Predicted No Risk

Predicted Risk

Actual No Risk

593

72

Actual Risk

135

200

Key Findings

The model achieved 79.3% accuracy on the test dataset.

It correctly identified 200 applicants belonging to the Risk category.

The recall for the Risk category was 0.60, showing that some risky applicants were not identified.

Further model improvement may help identify more risky applicants.

Future Improvements

Experiment with Random Forest and Decision Tree classifiers.

Perform hyperparameter tuning.

Improve Risk class recall.

Compare multiple classification models.

Author

Eman Fatima

Machine Learning Project
