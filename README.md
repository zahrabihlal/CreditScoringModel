# Credit Scoring Model

## Overview

This repository contains code and documentation for creating a credit scoring model. The model is trained on the German Credit dataset, which contains data on 1,000 loan applicants with various financial and personal attributes, as well as their credit risk classification.

## Data Source

The dataset used in this project is the German Credit dataset from the UCI Machine Learning Repository. You can find the dataset [here](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)).

## Preprocessing

The dataset includes both numerical and categorical variables. Categorical variables have been transformed into numerical format using one-hot encoding. The data has been standardized to have a mean of 0 and a standard deviation of 1.

## Modeling

For this project, I initially use a logistic regression model to predict credit risk. The logistic regression model was trained on a training dataset and evaluated on a test dataset. I used various metrics, including classification accuracy, precision, recall, F1-score, and ROC AUC score, to assess the performance of the model.

## Results

The logistic regression model achieved the following results on the test dataset:

- Classification Report:
  
|               | Precision | Recall | F1-Score | Support |
|:-------------:|:---------:|:------:|:--------:|:-------:|
|       1       |    0.84   |  0.88  |   0.86   |   141   |
|       2       |    0.67   |  0.59  |   0.63   |   59    |
|               |           |        |          |         |
|   Accuracy    |           |        |   0.80   |   200   |
|   Macro avg   |    0.76   |  0.74  |   0.74   |   200   |
| Weighted avg  |    0.79   |  0.80  |   0.79   |   200   |


- Confusion Matrix:
  [[124  17]
 [ 24  35]]
- ROC AUC Score:
  0.8208919341266978
## Conclusion

This project serves as a starting point for creating a robust credit scoring model. I utilized a logistic regression model to assess credit risk based on individual characteristics and credit history. This model is one of several that can be used for credit scoring purposes.

As a next step, I plan to explore other machine learning algorithms such as decision trees, random forests, support vector machines, and neural networks to assess their suitability for credit risk modeling. Ultimately, I will choose the model that performs best based on various evaluation metrics, including classification accuracy, precision, recall, F1-score, and ROC AUC score.
