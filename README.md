# Credit Risk Scoring Models applied on https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data 

## Overview

This analysis aims to build a predictive credit scoring model using various financial and demographic variables. The project involves examining distributions, associations, and the significance of different features to understand their impact on credit risk.

## Data Visualization

We utilized histograms, kernel density plots, and box plots to visually explore the relationships between continuous and categorical variables, such as credit amount, purpose of the loan, status of checking account, and employment duration.

## Statistical Analysis

Chi-square tests and eta squared (η²) calculations were conducted to statistically validate the associations observed in the visualizations. The results highlighted significant and non-significant relationships between variables, informing the selection of features for the model.

## Insights

- **Status and Credit History** are strongly associated with credit risk.
- **Purpose of loan** exhibits a variable relationship with credit amounts and risk.
- **Savings and Employment Duration** provide independent information about credit risk.
- **Property, Housing, and Job type** are significantly linked to credit risk.

## Model Building Implications

- Variables with strong associations and higher eta squared values are prioritized in model development.
- Interaction terms are considered to capture complex relationships between features.
- Non-significant relationships indicate independent contributions to the credit risk model.
