![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/notebooks-Jupyter-orange)

# Time Series Forecasting – Electricity Demand

This project explores hourly electricity demand forecasting using classical
time series features and machine learning models.

## Project structure
- `notebooks/` – step-by-step analysis and modeling
- `data/raw/` – original dataset (included for reproducibility)
- `data/processed/` – cleaned and feature-engineered data

## Workflow
- 01 – Exploratory data analysis
- 02 – Time series cleaning and resampling
- 03 – Feature engineering
- 04 – Baseline modeling with walk-forward validation
- 05 – Final evaluation and discussion

## Modeling approach
- Lag features and rolling statistics
- Linear regression baseline
- Walk-forward validation with daily updates

## Key results
The baseline model captures daily and weekly seasonality and provides a
reasonable benchmark for more advanced approaches.

## Future work
- Non-linear models (Random Forest, Gradient Boosting)
- Multi-step forecasting
- Probabilistic predictions

## Author
Stefano Avanzini
