# German Credit Risk Classification

This project applies a machine learning classification model to assess credit risk using the **Statlog German Credit dataset** from the UC Irvine Machine Learning Repository. The goal is to predict whether a borrower represents good or bad credit risk based on financial and demographic characteristics.

## Dataset

The data used in this project is the **Statlog (German Credit Data)** dataset, sourced from the UC Irvine Machine Learning Repository.

- Observations: 1,000
- Target variable: Credit risk (good vs bad)
- Features include:
  - Credit history
  - Loan purpose
  - Credit amount
  - Employment status
  - Personal and financial attributes

Categorical variables are encoded numerically to allow for machine learning analysis.

## Overview

The project performs the following steps:

1. Data loading and preprocessing
2. Encoding of categorical variables
3. Exploratory analysis of class distribution
4. Train–test split
5. Credit risk prediction using a Random Forest classifier
6. Model evaluation using accuracy and confusion matrices
7. Hyperparameter tuning for model improvement

## Methodology

A **Random Forest Classifier** is used to model credit risk because it can capture nonlinear relationships and variable interactions.

The model is trained on a subset of the data and evaluated on a holdout test set. Model performance is assessed using:

- Classification accuracy
- Confusion matrix analysis

Hyperparameter tuning is conducted using a randomized search to improve predictive performance.

## Usage

Run the notebook to execute the full analysis with the Jup notebook:
MLModel.ipynb


## Author
Benjamin Raderstorf
