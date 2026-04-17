# Monte Carlo Simulation for Portfolio Market Risk Estimation

## Overview

This project applies Monte Carlo simulation to estimate portfolio market risk.  
It extends a previous historical risk analysis by simulating thousands of possible future return scenarios.

The goal is to evaluate potential losses and compute key risk measures such as Value-at-Risk (VaR) and Expected Shortfall (ES).

---

## Motivation

Traditional risk models rely on historical data, but financial markets are uncertain.  
Monte Carlo simulation allows us to model future scenarios and better understand potential extreme losses.

---

## Methodology

### 1. Data Preparation
- Historical price data
- Log return computation
- Equal-weight portfolio construction

### 2. Parameter Estimation
- Mean (μ) and volatility (σ) estimated from historical returns
- Assumption: returns follow a normal distribution

### 3. Monte Carlo Simulation
- 10,000 simulated return scenarios
- Generation of future portfolio returns using random sampling

### 4. Risk Measures
- Value-at-Risk (VaR 95% and 99%)
- Expected Shortfall (ES)

### 5. Visualization
- Histogram of simulated loss distribution
- VaR thresholds highlighted

---

## Key Results

- Monte Carlo simulation provides a probabilistic view of future losses  
- VaR estimates loss thresholds under extreme scenarios  
- Expected Shortfall captures tail risk beyond VaR  
- Results depend strongly on model assumptions  

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---



