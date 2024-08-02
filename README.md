# Diamond Price Prediction

## Overview
This project focuses on predicting diamond prices using various machine learning models.

## Table of Contents
1. [Data Discovery](#data-discovery)
2. [Data Visualization and Analysis](#data-visualization-and-analysis)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Building](#model-building)
5. [Model Evaluation](#model-evaluation)

## Data Discovery
- Dataset contains 43,152 instances
- Features include both numerical and categorical attributes
- Key attributes: carat, cut, color, clarity, depth, table, price, x, y, z

## Data Visualization and Analysis
- Histogram plots for numerical attributes
- Correlation matrix using heatmap
- Pair plots for relationship between attributes
- Reg plots for identifying outliers
- Count plots for categorical data distribution
- Violin plots for price distribution across categorical features

## Data Preprocessing
- Feature engineering: created 'volume' feature
- Ordinal encoding for categorical features
- Outlier handling
- Feature scaling using StandardScaler
- Pipeline creation for preprocessing steps

## Model Building
Models implemented and their RMSE scores:
1. Linear Regression (Baseline): 1181.90
2. Polynomial Regression (degree=3): 636.26
3. Decision Tree Regressor: 747.31
4. Random Forest Regressor: 530.64
5. KNN Regressor: 650.64
6. XGBoost Regressor: 509.54 (Best model)

## Model Evaluation
- Best model: XGBoost Regressor
- Final RMSE on test data: 538.39

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, xgboost

## Usage
1. Clone the repository.
2. Install required libraries.
3. Run the Jupyter notebook or Python script.
