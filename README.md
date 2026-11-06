# Walmart Retail Demand Forecasting

## Project Overview
This project focuses on predicting weekly retail sales using machine learning techniques and historical Walmart sales data.

## Objectives
- Analyze historical Walmart sales data.
- Perform data preprocessing and exploratory data analysis.
- Create temporal and external features.
- Compare multiple machine learning models.
- Identify the best-performing forecasting model.
- Explain model predictions using feature importance and SHAP.
- Analyze forecasting errors and potential sales anomalies.
- Evaluate prediction uncertainty using prediction intervals.

## Dataset
The project uses the Walmart Store Sales Forecasting dataset, which contains historical weekly sales along with store information, department details, holidays, and external factors.

## Models Used
- Linear Regression
- Random Forest
- XGBoost
- LightGBM

## Best Model
XGBoost Regressor with temporal features.

**Evaluation Results:**
- MAE: 1310.84
- RMSE: 2747.14
- WAPE: 8.3%
- R²: 0.9844

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- SHAP

## Project Files
- `Walmart_Demand_Forecasting.ipynb` – Complete project implementation, including preprocessing, EDA, model training, evaluation, explainability, and uncertainty analysis.

## Note
The dataset is not included in this repository. Users should obtain the Walmart Store Sales Forecasting dataset separately and update the notebook's dataset paths before execution.
