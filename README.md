# Boston_Housing_ML_BigData_Analysis



This project presents an end-to-end analytical workflow on the Boston Housing dataset, combining exploratory data analysis, regression modeling, binary classification, and cross-validation techniques.  
The notebook was developed to study the relationship between socio-economic, environmental, and structural variables and housing prices, using a data-driven approach that integrates both machine learning and big data concepts. [file:31]

## Project Overview

The notebook is structured as a complete analytical pipeline that includes:
- Exploratory Data Analysis (EDA) and descriptive statistics
- Correlation analysis and feature interpretation
- Simple and multiple linear regression
- Residual analysis and model diagnostics
- Binary classification derived from the target variable
- Comparison of multiple classification algorithms
- Cross-validation and performance evaluation across feature sets [file:31]

## Dataset

The project uses the **Boston Housing** dataset from the **ISLP** package.  
The target variable is `medv`, representing the median value of owner-occupied homes, while the predictors include socio-economic, environmental, and structural attributes such as `lstat`, `rm`, `ptratio`, and `nox`. [file:31]

## Methods

### Regression
The regression section includes:
- Simple Linear Regression using `lstat` as predictor
- Multiple Linear Regression with selected and full feature sets
- Evaluation through R², MSE, and RMSE
- Residual analysis with scatter plots, histograms, and QQ-plots [file:31]

### Classification
The classification section transforms the continuous target into a binary label based on the training-set median threshold.  
The following models are tested and compared:
- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN) [file:31]

### Validation
To ensure robustness, the notebook applies:
- Train/test split
- K-Fold Cross-Validation for regression
- Stratified K-Fold Cross-Validation for classification
- Comparative evaluation using AUC, LogLoss, Accuracy, confusion matrices, and classification reports [file:31]

## Key Results

The analysis highlights that:
- `lstat` is one of the strongest individual predictors of house prices
- combining multiple variables significantly improves regression performance
- the feature set `lstat + rm + ptratio` provides strong classification results
- classification models reach high discriminative performance, with AUC values around 0.93–0.95 for the best configurations [file:31]

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- scikit-learn
- statsmodels
- ISLP [file:31]

## Repository Purpose

This notebook is intended as a portfolio project demonstrating practical skills in:
- data exploration
- statistical modeling
- machine learning workflows
- performance evaluation
- model comparison
- professional notebook structuring for analytical tasks [file:31]
