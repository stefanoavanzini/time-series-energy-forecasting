![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/notebooks-Jupyter-orange)

# Time Series Forecasting – Electricity Demand

This project explores hourly electricity demand forecasting using classical
time series features and machine learning models.

## How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/stefanoavanzini/time-series-energy-forecasting
   cd time-series-energy-forecasting
   
   
   ```
   
2. (Optional but recommended) Create a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate  # Linux / macOS
    venv\Scripts\activate     # Windows
    
    
    ```

3. Install the required dependencies:
    ```
    
    pip install -r requirements.txt
    
    
    ```
    
4. Open the notebooks:
    ```
    jupyter notebook
    
    
    ```
    
5. Run the notebooks in order:
The notebooks are self-contained and can be run independently once the dataset is available.

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
