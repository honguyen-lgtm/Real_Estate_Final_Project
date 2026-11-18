 Real Estate Price Prediction Using Regression Modeling

Project Overview

This project was completed as part of DSC 501 and focuses on predicting residential property sale prices using Python and regression analysis.

The objective was to examine housing characteristics, identify important predictors of property values, and develop statistical models to estimate home sale prices.

Tools and Technologies

- **Python** – Data analysis and predictive modeling
- **Pandas and NumPy** – Data cleaning and manipulation
- **Scikit-learn** – Model evaluation
- **Matplotlib and Seaborn** – Data visualization
- **SHAP** – Model interpretability
- **Jupyter Notebook** – Analysis and documentation

## Project Methodology

### 1. Data Preparation and Exploration

- Explored residential housing data to understand property characteristics.
- Examined relationships between housing features and sale prices.
- Prepared variables for regression modeling.
- Investigated potential outliers and multicollinearity.

### 2. Regression Modeling

Developed and compared five regression models to evaluate how different housing characteristics influence sale prices.

Models were assessed using adjusted R², prediction error, and diagnostic analysis.

### 3. Model Evaluation

The strongest-performing model was Model 5.

| Evaluation Metric | Model 5 Results |
|---|---|
| Adjusted R² | 82.1% |
| Root Mean Squared Error (RMSE) | Approximately $37,396 |

The adjusted R² indicates that the model explained approximately 82.1% of the variation in home sale prices, accounting for the number of predictors.

The RMSE represents the typical magnitude of prediction errors, with larger errors receiving greater weight.

### 4. Feature Importance and Interpretation

SHAP analysis was used to understand which housing characteristics contributed most to model predictions.

Key predictors included:

- **Kitchen Quality** – Quality of kitchen features
- **cOQ** – A feature used in the final regression model
- **cGLA
