# Financial Machine Learning Research

**Author:** Lucas Minchillo  
**Focus:** Financial ML, Model Evaluation, Quantitative Research

---

## Overview

This repository is a **research-oriented monorepo** focused on applying
machine learning to financial time series. It will grow incrementally as new research topics are added.

---

## Current Content

### 📓 Walk-Forward Modeling

- **Notebook:** `000-walk-forward.ipynb`
- Demonstrates:
  - Walk-forward training and evaluation
  - Expanding vs rolling windows
  - Logistic regression as a baseline directional model
  - Evaluation using expected log return (EV)

This notebook serves as the **foundation** for all future experiments
in this repository.

---

### 📓 Linear Regression for Factor Investing

- **Notebook:** `001-linear-regression.ipynb`
- Demonstrates:
  - Estimating Apple's market beta (β) via CAPM OLS regression
  - Working with real historical price data instead of simulated data
  - Building and cleaning a factor regression dataset (excess returns)
  - Interpreting alpha, beta, residuals, and R²
  - Model diagnostics and rolling beta / time-series stability analysis
  - The CAPM Security Market Line

This notebook builds the statistical foundation for multifactor models
(Fama–French, Carhart) covered in later notebooks.

---

### 📓 Fama-French Factor Model

- **Notebook:** `002-fama-french-factor-model.ipynb`
- Demonstrates:
  - Downloading Fama-French three-factor data (market, size, value) plus risk-free rate
  - Downloading the momentum factor
  - Merging factor return series and aligning with Apple's monthly returns
  - Running an OLS factor model regression with a constant (alpha)
  - Extracting factor exposures (betas), alpha, and idiosyncratic risk

---

## Research Roadmap

The following topics will be added as separate notebooks over time:

- **Multifactor Models**
  - Carhart four-factor and Fama-French five-factor extensions
- **Feature Engineering**
  - Returns, volatility, momentum, and regime features
- **Feature Selection**
  - Stability analysis
  - Information coefficient
  - Redundancy and decay
- **Model Evaluation**
  - Profit-based metrics
  - Statistical significance
  - Model decay and robustness
- **Trading Strategy Creation**
  - Signal translation
  - Transaction costs
  - Position sizing and risk management

Each topic will build on the previous ones while keeping notebooks
self-contained and reproducible.

---

## Design Philosophy

- Research-first, not production-first
- Explicit and readable code
- Clear separation between:
  - **Model**
  - **Evaluation**
  - **Strategy**
  - **Live Implementation**

---

## Disclaimer

This repository is for **educational and research purposes only**.
It does not constitute financial advice or a production-ready trading system.
