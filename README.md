# Credit Risk Prediction

This GitHub repository contains a project focused on credit risk prediction using machine learning models. The goal of this project is to develop and compare different machine learning models to predict credit risk, specifically whether a borrower is likely to default on their financial obligations. The project involves data preprocessing, visualization, feature engineering, model building, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data](#data)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Models](#models)
  - [Logistic Regression](#logistic-regression)
  - [Random Forest](#random-forest)
  - [XGBoost](#xgboost)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Introduction

Credit risk is the likelihood that a borrower will fail to make timely payments and default on their financial obligations. It is a critical concern for financial institutions, including banks, venture capital firms, asset management companies, and insurance corporations, among others. The ability to predict credit risk accurately is essential for managing and minimizing potential financial losses.

This project explores the use of machine learning models to predict credit risk based on various borrower attributes and financial data. It involves building, training, and evaluating different models to assess their effectiveness in classifying borrowers as either likely to default (1) or not likely to default (0).

## Project Overview

This project follows a structured approach to credit risk prediction:

1. **Data Collection**: The dataset used for this project is obtained from Kaggle and contains various features related to borrowers, loans, and credit risk outcomes.

2. **Data Preprocessing**: Data preprocessing involves handling missing values < style color='red'> (no data removed  rather susbtitute missing value with suitable replacemnt, used KNN imputation) </>, converting categorical variables into numerical representations, and splitting the data into training and testing sets.

3. **Exploratory Data Analysis (EDA)**: EDA includes visualizing the dataset to understand its distribution, relationships between variables, and identifying potential patterns or trends.

4. **Model Building**: Three machine learning models are used for credit risk prediction: Logistic Regression, Random Forest, and XGBoost. These models are trained on the training data and tested on the testing data.

5. **Model Evaluation**: Model performance is evaluated based on accuracy, precision, recall, F1-score, and ROC-AUC. Confusion matrices and classification reports are generated for each model.

6. **Conclusion**: The project concludes by comparing the performance of the three models and selecting the most suitable model for credit risk prediction based on the evaluation metrics.

## Data

The dataset used in this project contains various columns, including borrower attributes (e.g., age, income, employment length), loan details (e.g., loan amount, interest rate), and credit risk outcome (loan status).

## Project Structure

The project structure is organized as follows:

- `credit_risk_dataset.csv`: The dataset used for credit risk prediction.
- `README.md`: This readme file providing an overview of the project.
- `credit_risk_prediction.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, visualization, model building, and evaluation.
- `images/`: Directory containing images generated during data visualization and model evaluation.

## Usage

To use this project, you can follow these steps:

1. Clone this GitHub repository to your local machine.
2. Open the `credit_risk_prediction.ipynb` Jupyter Notebook to explore the code and execute it step by step.
3. Make sure you have the necessary Python libraries installed (e.g., pandas, numpy, scikit-learn, xgboost) by using `pip install`.

## Models

### Logistic Regression

Logistic regression is a classic binary classification model used for credit risk prediction. It provides an initial baseline for the project's evaluation.

### Random Forest

Random Forest is an ensemble learning model known for its ability to handle complex datasets and provide robust predictions. It is used to improve predictive accuracy.

### XGBoost

XGBoost (Extreme Gradient Boosting) is a gradient boosting algorithm known for its high performance and effectiveness in classification tasks. It is used to assess whether it outperforms other models.

## Evaluation

The performance of each model is evaluated using various metrics, including accuracy, precision, recall, F1-score, and ROC-AUC. Visualizations such as confusion matrices and ROC curves are provided to assess model performance.

## Conclusion

This project aims to develop a reliable credit risk prediction model to assist financial institutions in making informed lending decisions. By comparing the performance of different machine learning models, we can determine which model is best suited for the task and potentially improve credit risk assessment processes.
