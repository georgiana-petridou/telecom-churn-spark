# telecom-churn-spark
Customer churn analysis and predictive modeling for monthly charges using Spark SQL and MLlib.

# Telecom Customer Churn & Monthly Charge Prediction

## Overview
A comprehensive data analysis and machine learning project using **Apache Spark** to understand customer behavior in the telecommunications industry and predict monthly charges.

## Key Features
- **Data Engineering**: Implemented data cleaning strategies, including **Median Imputation** for missing numerical values and feature engineering (e.g., `NUM_SERVICES`, `IS_LONG_TENURE`).
- **Business Insights**: Utilized **Spark SQL** to identify churn patterns. Found that customers with month-to-month contracts have a 53.21% churn rate compared to 13.65% for two-year contracts.
- **Machine Learning**: Developed a **Spark ML Pipeline** using a **Decision Tree Regressor** to predict `MONTHLY_CHARGES` based on customer profiles.

## Tech Stack
- **Engine**: Apache Spark (PySpark)
- **Library**: Spark MLlib, Spark SQL
- **Algorithm**: Decision Tree Regressor
- **Environment**: Google Colab

## Model Performance
- **RMSE**: 7.86 €
- **R²**: 0.41
The model is suitable for "what-if" scenarios and dynamic pricing simulations.
