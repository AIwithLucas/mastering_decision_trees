## Objective: Mastering Decision Tree Classifier

### 1. Theoretical Mastery

    - Gini Impurity, Entropy and Information Gain
    - Splitting criteria - maximize info gain / minimize gini impurity

### 2. Algorithmic Implementation

    - Decision Tree Classifier from scratch
    - Decision Tree Classifier with libraries

### 3. Performance Analysis

    - Accuracy: proportion of correctly predicted labels
    - Confusion Matrix: TP, FP etc.
    - Precision, Recall, F1 Score - performance in imbalanced dataset
    - ROC-AUC Curve

## Objective: Mastering Decision Tree Regressor

### 1. Theoretical Mastery

    - Variance Reduction (SSE partitioning)

### 2. Algorithmic Implementation

    - Decision Tree Regressor from scratch
    - Decision Tree Regressor with libraries

### 3. Performance Analysis

    - Mean Squared Error
    - R-squared score: how well tree explains variability

## Advanced Tree Techniques

    ### 1 Ensemble Methods
        - Random Forest
        - Gradient Boosting

    ### 2 Optimization Techniques
        - Hyperparameters tuning
        - Regularization

# Lending Club Loan Dataset

The Lending Club Loan dataset provides comprehensive loan information issued between 2007 and 2015. This dataset is widely used for credit risk modeling and loan performance analysis. Below is a summary of the dataset, its features, and potential uses.

## Dataset Overview

- **Dataset Size:** 10,000 rows (sampled from the complete dataset)
- **Number of Features:** 53
- **Target Variable:** `loan_status` (categorical, representing the status of loans such as Fully Paid, Charged Off, etc.)

## Features and Descriptions

| Feature                     | Data Type | Description                                                                    |
| --------------------------- | --------- | ------------------------------------------------------------------------------ |
| `emp_title`                 | String    | Job title of the borrower.                                                     |
| `emp_length`                | Integer   | Length of employment in years.                                                 |
| `state`                     | String    | Borrower's state of residence.                                                 |
| `homeownership`             | String    | Homeownership status: Rent, Own, or Mortgage.                                  |
| `annual_income`             | Float     | Annual income of the borrower.                                                 |
| `verified_income`           | String    | Income verification status.                                                    |
| `debt_to_income`            | Float     | Debt-to-income ratio.                                                          |
| `annual_income_joint`       | Float     | Combined income for joint applications.                                        |
| `verification_income_joint` | String    | Income verification status for joint applications.                             |
| `debt_to_income_joint`      | Float     | Debt-to-income ratio for joint applications.                                   |
| `delinq_2y`                 | Integer   | Number of delinquencies in the last 2 years.                                   |
| `months_since_last_delinq`  | Integer   | Months since the last delinquency.                                             |
| `earliest_credit_line`      | Date      | Date of the borrower’s earliest reported credit line.                          |
| `inquiries_last_12m`        | Integer   | Number of credit inquiries in the last 12 months.                              |
| `total_credit_lines`        | Integer   | Total number of credit lines in the borrower’s credit history.                 |
| `open_credit_lines`         | Integer   | Number of currently open credit lines.                                         |
| `total_credit_limit`        | Float     | Total credit limit across all credit lines.                                    |
| `total_credit_utilized`     | Float     | Amount of credit used as a percentage of the total credit limit.               |
| `num_collections_last_12m`  | Integer   | Number of collections in the last 12 months.                                   |
| `loan_purpose`              | String    | Purpose of the loan (e.g., Debt Consolidation, Credit Card, Home Improvement). |
| `loan_amount`               | Float     | Amount of the loan.                                                            |
| `term`                      | String    | Loan term in months (e.g., 36 months, 60 months).                              |
| `interest_rate`             | Float     | Interest rate of the loan.                                                     |
| `installment`               | Float     | Monthly payment amount.                                                        |
| `grade`                     | String    | Grade assigned to the loan based on credit risk.                               |
| `sub_grade`                 | String    | Sub-grade for more granular risk assessment.                                   |
| `loan_status`               | String    | Loan status (e.g., Fully Paid, Charged Off, Late).                             |
| `paid_total`                | Float     | Total amount paid by the borrower.                                             |
| `paid_principal`            | Float     | Principal amount paid by the borrower.                                         |
| `paid_interest`             | Float     | Interest amount paid by the borrower.                                          |
| `paid_late_fees`            | Float     | Late fees paid by the borrower.                                                |

## Use Cases

- Credit risk modeling
- Predictive analysis of loan performance
- Exploratory data analysis of borrower behavior and loan trends

## Source

The dataset was sourced and adapted from Lending Club public loan records, and additional details can be found in repositories and publications about credit risk modeling using this dataset.
