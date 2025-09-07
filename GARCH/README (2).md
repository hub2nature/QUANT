# Volatility Modeling with GARCH Family

This notebook implements **GARCH family models** to capture and forecast **S&P 500 volatility**, essential for risk management and financial analysis.

## Models Used
- **GARCH**
- **EGARCH** (captures asymmetry)
- **GJR-GARCH** (differentiates shock impacts)
- **GARCH-NN** (hybrid deep learning model)

## Workflow
- **Data Loading**: Clean & compute returns
- **EDA**: Plot returns & volatility, test for stationarity
- **Model Fitting**: Estimate parameters for each GARCH model
- **Forecasting**: Out-of-sample evaluation using MAE, MSE, MAPE

## Objective
Find the most accurate and robust model for **S&P 500 volatility forecasting**.

