# ML for Finance - Exploring Advanced Financial Modeling Techniques

## Authors
Amber Walker and Clarice Mottet

## Date
May 2024

## Overview
This project evaluates various methods for financial modeling and prediction using the EWMA-based variance, causality analysis, and predictive analysis of the S&P 500. We employed techniques such as Neural Networks and Gaussian Processes to forecast financial indicators.

## Contents

1. **EWMA Based Variance**
   - Calculated log daily returns and EWMA-based variance using Python.
   - Compared EWMA-based variance with historical volatility.

2. **Causality Analysis**
   - Performed Granger causality tests on weekly and monthly data.
   - Evaluated correlations and volatility spill-over among different market indices.

3. **Predictive Analysis of S&P 500**
   - Used historical data (1927-2021) to forecast S&P 500 using Neural Networks and Gaussian Processes.
   - Conducted preprocessing, feature engineering, and feature selection.

4. **Baseline Model: ARMA(p,q)**
   - Built ARMA models for continuous targets (price and return) to serve as baseline forecasts.

5. **Gaussian Process Setup, Tuning, and Forecast**
   - Tuned various kernels using Grid Search and cross-validation for optimal performance.
   - Achieved high accuracy in predicting price, returns, and market direction.

6. **Neural Network Setup, Tuning, and Forecast**
   - Tuned hyperparameters for Neural Networks.
   - Compared performance with Gaussian Processes and ARMA models.

7. **Results & Discussion**
   - Analyzed performance metrics for different models.
   - Gaussian Process model demonstrated superior performance in most tasks.

## Conclusion
Our Gaussian Process model showed the strongest performance, particularly in predicting the log of the index and returns. The flexible kernel choice of GP provided an edge in handling financial time series predictions.

## Figures
- EWMA Method Comparison
- Causality Analysis for Log Daily Returns and Volatility
- Comparison between FTSE and N225
- Correlation Analysis
- Log of Index and Returns Plot Comparison
- Direction Scatter Plot Comparison
