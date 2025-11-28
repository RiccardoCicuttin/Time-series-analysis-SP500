# Time series analysis - SP500
This document reports on the project I carried out during my bachelor's degree in statistics, for the course "business intelligence". 
The main objective was to use the fundamental data analysis tools offered by Python, in order to study return distributions, cross-asset correlations, time-series properties, and to build the main econometric and portfolio models that could highligth key concepts in financial statistics.

On this project I explored the daily **adjusted close prices** of six S&P500 constituents across three sectors:
- **Financials**: Goldman Sachs (GS), Visa (V)  
- **Consumer Discretionary**: Amazon (AMZN), McDonald’s (MCD)  
- **Healthcare**: Eli Lilly (LLY), UnitedHealth (UNH)  

---

##  Main Objectives
- Perform **exploratory data analysis** on daily and log returns.  
- Investigate **correlation dynamics** across different horizons (6M, 1Y, 5Y, 10Y).  
- Test **stationarity** and apply **SARIMA models** on log-prices.  
- Evaluate **CAPM and Fama–French 3-factor regressions** at the monthly frequency.  
- Illustrate **portfolio construction** using:
  - Monte Carlo simulation of random weights,  
  - **Markowitz minimum-variance framework**.

---

##  Methods & Tools
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Time-series**: `statsmodels`, `pmdarima`  
- **Finance/data**: `yfinance`, `getFamaFrenchFactors`  
- **Regression/Optimization**: `statsmodels.api`, `scipy.optimize`

---
