# Credit-Card-Fraud-Detection

This project focuses on developing a machine learning solution for detecting credit card fraud. The goal is to build a model that can accurately identify fraudulent transactions and distinguish them from legitimate ones.

## Overview

Credit card fraud is a significant concern in the financial industry, causing substantial financial losses for both individuals and businesses. The objective of this project is to employ machine learning techniques to create a robust fraud detection system. Various models, such as logistic regression, decision tree, random forest, AdaBoost, gradient boosting, and XGBoost, were evaluated to identify the most effective approach.

## Dataset

The project utilizes a dataset containing credit card transaction data. This dataset consists of a large number of transactions, including both legitimate and fraudulent ones. The dataset is highly imbalanced, with a small percentage of fraudulent transactions compared to legitimate ones. The dataset is not provided in this repository due to its sensitive nature, but it can be obtained from reputable sources or credit card companies.

## Models

Different machine learning models were trained and evaluated for the credit card fraud detection task. These models include logistic regression, decision tree, random forest, AdaBoost, gradient boosting, and XGBoost. After thorough experimentation, it was determined that the XGBoost model performed the best in terms of fraud detection accuracy.

## Data Preprocessing

Due to the imbalanced nature of the dataset, techniques such as Synthetic Minority Over-sampling Technique (SMOTE) were used to address the class imbalance problem. SMOTE helps balance the classes by creating synthetic samples of the minority class. Additionally, missing value imputation was performed using the K-nearest neighbors (KNN) algorithm to handle incomplete data points.

## Implementation Details

The project is implemented using Python programming language and popular libraries such as pandas, scikit-learn, XGBoost, and others. The code for data preprocessing, model training, evaluation, and result analysis is provided in the Jupyter notebooks included in the repository.


## Results

The XGBoost model demonstrated the highest accuracy in detecting credit card fraud among the evaluated models. The use of SMOTE for class imbalance correction and KNN for missing value imputation helped enhance the performance of the model.

