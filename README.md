# Portfolio Risk Modeling, VaR Validation & Stress Testing

## Overview
This project develops a portfolio risk framework using Historical, Parametric, and Monte Carlo Value-at-Risk (VaR) models to evaluate tail risk under normal and stressed conditions. The analysis includes model validation, statistical diagnostics, and stress testing aligned with market risk management practices.

## Key Features
- Constricted an equal-weight portfolio equity index, technology stock, and gold ETF data:
- Implemented and compared
  - Historical VaR
  - Parametric (Variance-Covariance) VaR
  - Monte Carlo VaR
- Estimated tail risk using:
  - Value-at-Risk (95%, 99%)
  - Expected Shortfall
- Performed VaR Backtesting using:
  - Kupiec Proportion of Failures test
  - Christoffersen Independence Test
- Evaluated model assumptions through:
  - Normality tests
  - Volatility clustering analysis
  - ARCH effects
  - Correlation breakdown scenarios
  - Combined crisis stress scenarios
- Simulated stress portfolio losses using Monte Carlo simulations under crisis covariance structures
  
## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, yFinance

## Key Insights
- Parametric VaR underestimates risk during periods of elevated volatility and fat tails
- Expected Shortfall captures extreme downside risk more effectively than VaR
- Correlations increase significantly during a crisis, reducing diversification benefits
- VaR vreaches exhibit clustering, highlighting volatility persistence and model limitations
- Stress scenarios produce substantially higher tail losses than normal market conditions
- Stress events cluster rather than occurring independently
