## **Heart Failure Prediction**

This repository contains a project focused on predicting heart failure using a heart failure prediction dataset. The project involves exploratory data analysis (EDA) on the dataset and the implementation of three machine learning models: logistic regression, naive Bayes, and XGBoost. The results indicate that XGBoost is the best model for heart failure prediction.

## Dataset

The heart failure prediction dataset used in this project provides information related to various factors that contribute to heart failure. 
You can download the dataset from [here](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data).

## Exploratory Data Analysis (EDA)

EDA is performed on the heart failure prediction dataset to gain insights into the data and understand its characteristics. This step involves analyzing the distribution of variables, identifying patterns, handling missing values, and preprocessing the data for modeling.

## Machine Learning Models

Three machine learning models are implemented for heart failure prediction:

1. Logistic Regression: A statistical model that uses a logistic function to estimate the probability of an event occurring.
2. Naive Bayes: A probabilistic classifier based on Bayes' theorem with the assumption of independence between features.
3. XGBoost: An implementation of gradient boosted decision trees known for its speed and performance. It is commonly used for regression, classification, ranking, and user-defined prediction problems.

## Results

After evaluating the performance of the machine learning models, it is determined that XGBoost outperforms the other models for heart failure prediction. The following metrics support this conclusion:

- Maximum F1 score
- Maximum accuracy
- Maximum recall value
- Lowest classification error

XGBoost proves to be an effective algorithm for solving heart failure prediction problems, demonstrating superior performance in terms of accuracy and reliability.

## Run Locally

To run this project locally, follow the instructions below:

1. Clone the repository.
2. Download the heart failure prediction dataset from the provided link.
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the EDA and modeling scripts: `python eda.py` and `python model.py`
5. View and analyze the results obtained from the XGBoost model.

Feel free to modify and customize the project to suit your specific needs.
