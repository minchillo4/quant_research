# Financial Machine Learning Research

**Author:** Lucas Minchillo  
**Focus:** Financial ML, Model Evaluation, Quantitative Research

---

## Overview

This repository is a **research-oriented monorepo** focused on applying
machine learning to financial time series.It will grow incrementally as new research topics are added.

---

## Current Content

### 📓 Walk-Forward Modeling (Baseline)

- **Notebook:** `000-walk-forward.ipynb`
- Demonstrates:
  - Walk-forward training and evaluation
  - Expanding vs rolling windows
  - Logistic regression as a baseline model
  - Evaluation using expected log return

This notebook serves as the **foundation** for all future experiments
in this repository.

---

## Research Roadmap

The following topics will be added as separate notebooks over time:

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
