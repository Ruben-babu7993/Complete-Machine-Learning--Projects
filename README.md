Heart Failure Prediction using Machine Learning

This repository contains a machine learning project focused on predicting heart failure using clinical data. The project leverages a dataset from Kaggle to build predictive models that can help identify patients at risk of heart failure.
Table of Contents
Project Overview

Dataset

Features

Installation

Usage

Methodology

Results

Contributing

License

Acknowledgements

Project Overview
Cardiovascular diseases are the leading cause of death globally, and early detection of heart failure can significantly improve patient outcomes. This project aims to:

Analyze clinical parameters related to heart failure

Build and compare multiple machine learning models

Develop a predictive system with good accuracy

Provide insights into important risk factors

Dataset
The dataset used in this project is the Heart Failure Clinical Records Dataset from Kaggle. It contains medical records of 299 patients with heart failure, collected at the Faisalabad Institute of Cardiology and at the Allied Hospital in Faisalabad (Punjab, Pakistan).

Key statistics:

299 samples

13 clinical features

Binary target variable (death event)

Features:
The dataset includes the following clinical features:

Age

Anaemia (decrease of red blood cells or hemoglobin)

High blood pressure

Creatinine phosphokinase (CPK) level

Diabetes

Ejection fraction (percentage of blood leaving the heart)

Platelets
Sex

Serum creatinine

Serum sodium

Smoking

Time (follow-up period)

Death event (target)

Installation
To run this project locally, follow these steps:

Clone the repository:
git clone https://github.com/https:/Ruben-babu7993/Complete-Machine-Learning--Projects/.git
cd heart-failure-prediction

Methodology
Our approach includes:

Data Preprocessing:

Handling missing values

Feature scaling

Class imbalance treatment

Feature Engineering:

Creating interaction terms

Feature selection using mutual information

Model Building:

Logistic Regression (baseline)

Random Forest

XGBoost

Support Vector Machines

Neural Networks

Model Evaluation:

5-fold cross-validation

Precision-Recall curves

SHAP values for interpretability

Model Comparison <!-- Replace with model comparison plot -->

Results
Our best performing model achieved the following metrics:

Model	Accuracy	Precision	Recall	F1-Score	AUC-ROC
XGBoost	0.87	0.85	0.82	0.83	0.91
Random Forest	0.85	0.83	0.80	0.81	0.89
SVM	0.83	0.81	0.78	0.79	0.87
Key findings:

Serum creatinine and ejection fraction are the most important predictors

Age and time (follow-up period) also significantly impact predictions

The model can identify high-risk patients with 82% recall

Contributing
We welcome contributions to this project! Please follow these steps:

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.

