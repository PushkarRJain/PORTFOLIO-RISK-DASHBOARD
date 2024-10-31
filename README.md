# REALTIME PORTFOLIO RISK DASHBOARD 

Calculate VaR using the Interactive Dashboard: 

This module provides an easy-to-use Python class, `VaR`, for calculating Value-at-Risk (VaR) using three different methods: Historical, Parametric, and Monte Carlo simulation.

Developed a Python-based model to calculate Historical and Parametric Value at Risk (VaR) using real-time market data, 
enhancing portfolio risk management and market risk analysis.

Created a Streamlit interface allowing users to input tickers, portfolio weights, and parameters for dynamic risk assessment. 

Designed a VIX Calculator to estimate asset volatility using options data, improving volatility forecasting and market insight. 

## 🚀 Features:

1. **Historical VaR Calculation**: This method uses the actual distribution of historical returns to estimate VaR.
2. **Parametric VaR Calculation**: Also known as the variance-covariance method. It assumes returns are normally distributed.
3. **Monte Carlo Simulation**: Generates a large number of random portfolio returns and then determines an empirical distribution.

<img width="862" alt="image" src="https://github.com/user-attachments/assets/ca7eb949-b546-496f-909c-4f2316d040df">

var_model = VaR(ticker=['AAPL', 'MSFT'], 
                start_date='2020-01-01', 
                end_date='2022-01-01', 
                rolling_window=252, 
                confidence_level=0.95, 
                portfolio_val=1000000, 
                simulations=1000)
