# Kyphosis-Disease-Prediction.-
Kyphosis disease prediction using Neural Networks model and XGBoost model 

In the "Kyphosis disease prediction and Imbalanced Data" project, the objective was to develop a predictive model to identify the presence or absence of kyphosis, a medical condition. The dataset used in the project, named "Kyphosis.csv," contained imbalanced data, making it challenging to build an accurate model.

The "Kyphosis.csv" dataset, initially imbalanced, underwent preprocessing steps including SMOTE oversampling, label encoding, and feature scaling. It was then split into training and testing sets for model evaluation. Two models were considered: a Fully Connected Neural Network (FCNNs) built from scratch using PyTorch and an XGBoost model with hyperparameter tuning via GridSearchCV. After training and evaluation, the XGBoost model outperformed the FCNN, achieving 96% accuracy compared to the FCNN's 85%. This project showcased handling imbalanced data and binary classification, selecting XGBoost as the optimal model for predicting kyphosis in a medical context.
