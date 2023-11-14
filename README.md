# Diabetes Prediction Project

## Overview

This project implements a Linear Regression algorithm using the Scikit-learn module in Python to predict the progression of diabetes. The dataset is obtained from Stanford University's Machine Learning Repository.

## Dataset

- **Data Source:** Diabetes Dataset
- **Dataset Description:** [Seminal Paper]([link_to_seminal_paper](https://hastie.su.domains/Papers/LARS/diabetes.data))

## Tasks

### 1. Predict 'y' using a single feature of 'X' (in the entire dataset)

Find the best feature from 'X' for predicting 'y'.

#### Output:

- Model’s coefficients (slope, y-intercept)
- Linear Regressor Model (graph) plotting
- Mean Square Error (MSE)

### 2. Predict 'y' using a pair feature of 'X' (in the entire dataset)

Find the best pair feature from 'X' for predicting 'y'.

#### Output:

- Model’s coefficients (slope, y-intercept)
- Linear Regressor Model (graph) plotting
- Mean Square Error (MSE)

### 3. Predict 'y' using all (10) features of 'X' (in the entire dataset)

#### Output:

- Model’s coefficients
- Mean Square Error (MSE)

### 4. Compute training MSE and validation MSE

Fit the regressor on all features for different training set sizes.

**Training Set Sizes:**
- n_train = 20
- n_train = 50
- n_train = 100
- n_train = 200

#### Output:

- Training MSE and Validation MSE for each training set size.

### Extra Credit: XGBoost Model

Create a model using the XGBoost library and compare its results with the linear regressor (tasks 1-4).

#### Output:

- Comparison of results between Linear Regressor and XGBoost models.

