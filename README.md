# 📊 Income Classification using Logistic Regression

This project uses a **Logistic Regression** model to classify whether a customer's **Annual Income** is above or below the median, based on various features in the dataset.

## 🧾 Description

The workflow involves:

- Reading and preprocessing the dataset (`train.csv`)
- Removing irrelevant or sensitive columns (like `ID`, `Customer_ID`, `Name`, `SSN`, etc.)
- Defining the **target variable** based on the median of `Annual_Income`
- Handling missing values by dropping incomplete rows
- Encoding categorical variables using one-hot encoding
- Splitting the dataset into **training** and **testing** sets
- Scaling features using `StandardScaler`
- Training a **Logistic Regression** model
- Evaluating the model using:
  - **Classification Report**
  - **ROC AUC Score**

## 🛠️ Tech Stack

- Python
- pandas
- scikit-learn

## 📈 Model Evaluation

- The **classification report** provides precision, recall, F1-score, and support.
- The **ROC AUC Score** evaluates the quality of the model’s probability predictions for binary classification.

## 💡 Objective

To build a simple and interpretable binary classifier that predicts whether a person's income is **above or below the median**, useful in applications such as credit scoring or financial eligibility analysis.
