# SVR-GARCH Volatility Prediction

This repository contains a Jupyter Notebook implementing a volatility prediction model using Support Vector Regression (SVR) combined with a Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model.

## Overview
Volatility forecasting is a critical aspect of quantitative finance, particularly in risk management and algorithmic trading. This project leverages:
- **GARCH Model**: To estimate time-varying volatility in financial time series.
- **Support Vector Regression (SVR)**: To predict future volatility based on historical data.

## Features
- Data preprocessing and feature engineering
- Fitting a GARCH model to estimate conditional volatility
- Training an SVR model for volatility forecasting
- Performance evaluation and visualization

## Installation
To run this notebook, install the required dependencies:

```bash
pip install numpy pandas scipy sklearn arch matplotlib
```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook SVR_GARCH_volatility_prediction.ipynb
   ```
2. Follow the steps in the notebook to preprocess data, train models, and evaluate results.

## Results
The notebook provides visualizations and performance metrics to assess the model's ability to predict future volatility.

## Contributions
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License.

