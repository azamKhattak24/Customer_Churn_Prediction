# Customer Churn Prediction

## Project Overview

Customer churn refers to customers discontinuing a company’s services. Predicting churn is a critical business task, particularly in banking and subscription-based industries, where retaining existing customers is more cost-effective than acquiring new ones.

This project applies data analysis and machine learning techniques to predict customer churn using demographic, financial, and behavioral attributes.

---

## Dataset Description

The dataset contains customer information with the following features:

- CreditScore – Customer’s credit score
- Geography – Country of residence
- Gender – Male or Female
- Age – Customer age
- Tenure – Number of years with the bank
- Balance – Account balance
- NumOfProducts – Number of bank products used
- HasCrCard – Credit card ownership (0/1)
- IsActiveMember – Activity status (0/1)
- EstimatedSalary – Estimated annual salary
- Exited (Target) – Customer churn status (1 = churned, 0 = retained)

---

## Project Workflow

### 1. Data Loading and Exploration

- Load and inspect the dataset using Pandas
- Analyze data types, missing values, and distributions
- Identify numerical and categorical features

### 2. Data Preprocessing

- Encode categorical variables using one-hot encoding
- Scale numerical features using standardization
- Split data into training and testing sets

### 3. Exploratory Data Analysis

- Analyze churn distribution
- Study relationships between features and churn
- Examine correlations and class imbalance

### 4. Model Building

The following model is implemented:

- Logistic Regression

Model training includes:

- Feature scaling
- Hyperparameter tuning
- Training on the processed dataset

### 5. Model Evaluation

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Results

After experimenting with multiple linear and ensemble models, **Logistic Regression** achieved the most stable performance.

Final evaluation results:

- **Accuracy:** 81%
- **Recall (Churn Class):** 75%
- **F1-score:** Approximately 60%

These results indicate that the model is effective at identifying customers likely to churn, with a good balance between false positives and false negatives.

---

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
