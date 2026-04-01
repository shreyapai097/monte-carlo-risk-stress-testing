# Monte Carlo Portfolio Risk & Stress Testing

## Overview
This project models portfolio risk using Monte Carlo risk simulation under multiple scenarios

## Key Features
- Simulation of portfolio returns under:
  - Normal conditions
  - Volatility shocks
  - Drawdown crisis
  - Combines stress
- Tail risk estimation using VaR and Expected Shortfall (95%, 99%)
- Stress regime identification using VaR/ES breaches
- Analysis of clustering and frequency of extreme losses

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## Key Insights
- Risk is significantly higher under stress regimes
- Tail risk increases non-linearity (ES >> VaR)
- Stress events cluster rather than occurring independently
