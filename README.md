# Warehouse and Retail Sales Analysis

This project analyzes warehouse and retail sales data using various machine learning models to predict retail sales.

## Dataset

The analysis uses the `Warehouse_and_Retail_Sales.csv` dataset containing:
- Item information (codes, descriptions, types)
- Supplier details
- Sales data (retail sales, warehouse sales, retail transfers)
- Temporal information (year, month)

## Analysis Steps

1. **Data Exploration**
   - Visualization of top 10 item descriptions
   - Distribution of item types
   - Analysis of top suppliers
   - Yearly retail sales trends

2. **Data Preprocessing**
   - Handling missing values
   - One-hot encoding of categorical variables
   - Feature standardization
   - Dataset splitting (80% train, 20% test)

3. **Models Implemented**
   - Ridge Regression
   - Decision Tree
   - Gradient Boosting
   - XGBoost
   - LightGBM
   - CatBoost

## Model Performance

The following models were evaluated using R² score:
- Ridge Regression
- Decision Tree Regressor
- Gradient Boosting Regressor
- XGBoost
- LightGBM
- CatBoost

Performance metrics for each model include:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Model Accuracy

## Requirements

- Python 3.12
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- lightgbm
- catboost

## Results

The analysis includes visualizations of:
- Item frequency distributions
- Supplier analysis
- Sales trends
- Model performance comparisons