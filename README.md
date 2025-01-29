# 2.-Credit-Card-Fraud-Detection-Using-Machine-Learning

## ABSTRACT
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machine learning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.

## Keywords: Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, Logistic Regression, Random Forest. Logistic Regression using SMOTE technique.

## Overview
With the increasing use of credit cards in daily life, credit card companies must ensure the security and safety of their customers. According to credit card statistics, the number of users worldwide reached 2.8 billion in 2019, with 70% of users owning a single card. Reports of credit card fraud in the U.S. rose by 44.7% in 2020.

There are two primary types of credit card fraud:

1) Identity theft, where a fraudster opens an account under someone else’s name, which increased by 48% in 2020.
2) Unauthorized transactions on an existing account, which rose by 9% in 2020 (Daly, 2021).
   
These alarming statistics highlight the growing need for fraud detection systems. This project aims to address the issue analytically using machine learning techniques to detect fraudulent credit card transactions.

## Project Goals
The primary objective of this project is to detect fraudulent credit card transactions so that customers do not get charged for unauthorized purchases. Fraud detection will be performed using multiple machine learning techniques, and a comparative analysis will be conducted to determine the best-performing model. Various graphs and metrics will be used to evaluate the models, and previous research and techniques will be explored to improve detection accuracy.

Data Source
The dataset was retrieved from an open-source website, Kaggle.com. It consists of transactions made in 2013 by European credit card users over two days. The dataset includes 31 attributes and 284,808 rows.28 attributes are numeric variables that, due to the confidentiality and privacy of the customers, while the remaining three are:

Time: Seconds elapsed between transactions.
Amount: Transaction amount.
Class: Binary variable (1 = Fraudulent, 0 = Non-Fraudulent).

# Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Algorithms Used
Logistic Regression (LR)
Random Forest (RF)
Logistic Regression using SMOTE Technique

# Future Work
There are various ways to enhance the model, such as testing it on different datasets with varying sizes and structures or adjusting the data-splitting ratio to improve performance. Additionally, integrating external data sources, such as telecom data, could improve fraud detection.

# Conclusion
The main objective of this project was to determine the most effective machine learning model for credit card fraud detection. This was achieved by building and evaluating models using Logistic Regression and Random Forest. The Logistic Regression using SMOTE model achieved the highest accuracy, precision, and recall (96%, 98%, and 93%, respectively), making it the most reliable for fraud detection. Implementing such models enhances customer security and improves user confidence in financial transactions.

