# Overview
This repository contains scripts for a machine learning project focusing on regression and classification tasks. The project is divided into four main scripts:

## regression_b_CV.py: 
This script performs cross-validation for regression tasks, specifically utilizing k-fold cross-validation to evaluate the performance of regression models. It uses techniques such as linear regression and ridge regression.

## regression.py: 
This script implements various regression techniques and evaluates their performance on a dataset. Specifically, it includes the following methods and tools:

* Linear Regression: Utilizes the ordinary least squares method to fit a linear model to the data.

* Ridge Regression: Implements ridge regression, a technique for regularizing linear regression models to prevent overfitting.

* Grid Search Cross-Validation: Uses grid search to tune hyperparameters and cross-validation to evaluate model performance.


## classification.py: 
This script focuses on classification tasks and evaluates model performance using techniques such as logistic regression and k-nearest neighbors. It also includes a baseline classifier for comparison. Specifically, it includes the following methods and tools:

* Logistic Regression: Implements logistic regression for binary classification tasks.

* K-Nearest Neighbors: Utilizes the k-nearest neighbors algorithm for classification.

* Dummy Classifier: Implements a baseline classifier that predicts the most frequent class in the training data.

* Grid Search Cross-Validation: Utilizes grid search to tune hyperparameters and cross-validation to evaluate model performance.

* McNemar's Test: Conducts McNemar's test to compare the performance of different classifiers.


## regression_b_t-test.py: 
This script conducts t-tests to compare the performance of two regression models using the t-test statistic, confidence intervals, and p-values. Specifically, it includes the following methods and tools:

* T-Tests: Conducts t-tests to compare the performance of two regression models.

* Confidence Intervals: Calculates confidence intervals to estimate the range of values for the population parameter.

* P-Values: Calculates p-values to determine the statistical significance of the results.
