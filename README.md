# Loan Approval Prediction Using Logistic Regression

# Project Overview

This project focuses on building an interpretable Logistic Regression model to predict loan approval based on applicant information such as age, income, credit score, number of dependents, and home ownership. The primary objective is educational: rather than simply training a model and reporting an accuracy score, this project demonstrates the complete Logistic Regression workflow and explains how the algorithm converts applicant features into a probability of loan approval. The project covers data exploration, train-test splitting, feature scaling, model training, probability prediction, classification thresholds, confusion matrix analysis, precision, recall, F1-score, ROC-AUC, Log Loss, and interpretation of model coefficients and odds ratios.

# Objective

The objective is to understand how Logistic Regression works in practice, from preparing the dataset to generating and interpreting loan approval probabilities. The project also demonstrates why different evaluation metrics are necessary when assessing a binary classification model.

# Dataset
The dataset contains 1,000 loan applications with five input features:

* age — Applicant age
* income — Applicant income
* credit_score — Applicant credit score
* dependents — Number of dependents
* home_owner — Home ownership indicator
* The target variable is:
* loan_approved = 1 → Approved
* loan_approved = 0 → Not Approved

The dataset contains no missing values and is intentionally small so that the focus remains on understanding the machine-learning concepts rather than computational complexity.

# Methodology

The project follows this workflow:

Dataset
   ↓
Exploratory Data Analysis
   ↓
Feature & Target Selection
   ↓
Train/Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Probability Prediction
   ↓
Classification
   ↓
Model Evaluation


A Scikit-learn pipeline is used to combine StandardScaler and LogisticRegression, ensuring that preprocessing is performed consistently between training and testing data.

# This project provides practical understanding of:

* Binary classification
*Linear combination of features
* Sigmoid function
* Probability prediction
* Classification threshold
* Odds and log-odds
* Logistic Regression coefficients
* Odds ratios
* Maximum Likelihood Estimation
* Log Loss
* Feature scaling
* Confusion matrix
* Precision
* Recall
* F1-score
* ROC-AUC

# Model Performance

The Logistic Regression model was evaluated on the test dataset using multiple metrics:

* Metric	Score
* Accuracy	86.00%
* Precision	90.00%
* Recall	92.31%
* F1 Score	91.14%
* ROC-AUC	93.95%
* Log Loss	0.2511


The model achieved a ROC-AUC of 0.9395, indicating strong ability to distinguish between approved and non-approved applications on this test set.


# Key Learning

The central idea demonstrated in this project is:

Applicant Features
        ↓
Linear Combination
        ↓
Sigmoid Function
        ↓
Approval Probability
        ↓
Classification Threshold
        ↓
Loan Approval Prediction

Logistic Regression models the log-odds of the positive class as a linear combination of the input features and converts that value into a probability using the sigmoid function.

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

# Disclaimer

This project is created for educational and machine-learning practice purposes only. The model is not intended to be used for actual loan approval, credit decisions, or financial decision-making. The dataset is small and the reported performance represents only the evaluated test split.
