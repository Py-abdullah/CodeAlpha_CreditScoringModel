# Credit Scoring Model

This project is a machine learning-based credit risk classification system developed as part of the CodeAlpha Machine Learning Internship.

The model uses historical financial and payment data to classify customers into different credit risk categories. The project applies classification algorithms including Logistic Regression, Decision Tree, and Random Forest.

## Project Objective

The objective of this project is to predict an individual's credit risk using historical financial and payment information.

The project focuses on:

- Financial and demographic features
- Historical payment behavior
- Feature engineering
- Machine learning classification
- Model evaluation and comparison

## Dataset

The project uses the **Credit Card Approval Prediction** dataset from Kaggle.

The dataset contains customer application information and historical credit payment records.

### Main Data

**Application Record**

Includes information such as:

- Income
- Gender
- Number of children
- Education
- Family status
- Housing type
- Employment information
- Phone and email information
- Occupation

**Credit Record**

Contains historical monthly credit status information for customers.

The credit status is used to identify customers with higher-risk payment behavior.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Machine Learning Algorithms

The project implements and compares:

- Logistic Regression
- Decision Tree
- Random Forest

## Methodology

The project follows these main steps:

1. Load the application and credit datasets.
2. Understand the dataset structure and features.
3. Check missing values and duplicate records.
4. Clean the data.
5. Create a customer-level target variable from historical credit status.
6. Merge application and credit information.
7. Perform exploratory data analysis.
8. Perform feature engineering.
9. Prepare categorical and numerical features.
10. Split the data into training and testing sets.
11. Train Logistic Regression.
12. Train Decision Tree.
13. Train Random Forest.
14. Compare model performance.
15. Evaluate the models using classification metrics.
16. Generate a confusion matrix.
17. Calculate ROC-AUC.
18. Save the trained model.

## Target Variable

The target variable represents historical credit risk.

Customers with severe historical delinquency records are classified as higher risk, while customers without those records are classified as lower risk.

This project is therefore a **credit-risk classification experiment based on historical payment behavior**, rather than a real bank approval decision system.

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

These metrics are used to compare the classification performance of the different machine learning models.

## Project Files

```text
CodeAlpha_CreditScoringModel/
│
├── Credit_Scoring_Model.ipynb
├── credit_scoring_model.joblib
├── requirements.txt
└── README.md
