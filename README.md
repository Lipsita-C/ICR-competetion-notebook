# ICR-competetion-notebook
Repository for an entry in the ICR - Identifying Age-Related Conditions focusing on Identifying Age-Related Conditions using a machine learning model.
# Age-Related Condition Prediction (ICR) Notebook

![ICR Notebook Image](download.jfif)

## Introduction

Welcome to the Age-Related Condition Prediction (ICR) Notebook. In this notebook, we explore a comprehensive approach to predict whether an individual is susceptible to one of three age-related conditions. We leverage a variety of machine learning models, data preprocessing techniques, and strategies to tackle bias and class imbalance for robust predictions.

## Dataset

The dataset consists of 53 anonymized features, with the "Class" column serving as the target variable. Additionally, we have supplemental metadata that enhances the training dataset.

## Notebook Contents

### 1. Data Preprocessing
We begin by organizing the data into numerical and categorical columns. A data preprocessing pipeline is created to handle data cleaning, imputations, and categorical value transformations to prevent data leakage.

### 2. Outlier Handling
We address outliers to ensure they do not adversely affect model training and pattern recognition.

### 3. Bias Mitigation
To combat bias, we apply resampling and undersampling techniques, allowing the model to make fair and unbiased predictions.

### 4. Class Imbalance
Class weights are employed to counter class imbalance, ensuring each class is fairly represented during model training.

### 5. Confusion Matrix
Confusion matrices are used to fine-tune model probabilities and enhance prediction accuracy.

### 6. Feature Engineering
Feature engineering techniques include log and square transformations to improve model performance, while irrelevant features are pruned to optimize predictions.

### 7. Model Selection
We explore a range of models, including deep learning (Neural Networks), gradient boosting (Light GBM), and CatBoost. A modified Balanced Log Loss function is applied to fine-tune feature weights.

## Getting Started

1. Clone this repository to your local machine.
2. Execute the Jupyter Notebook to delve into the code and detailed explanations.


