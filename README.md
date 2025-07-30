# Bayesian-ML-Methods-on-US-Inflation

# Project Overview

Forecasting inflation is crucial for monetary policy, investment strategies, and economic planning. In this notebook, we:

- Import and clean CPI and macroeconomic indicators data.
- Engineer relevant features.
- Apply and evaluate several vanilla and bayesian regression models.
- Compare model performance using RMSE and R² metrics.
- Visualize actual vs. predicted CPI values.

# Models Used:

| Model                                   | Description                                                                                   |
|----------------------------------------|-----------------------------------------------------------------------------------------------|
| **Linear Regression**                  | A basic model assuming a linear relationship between features and the CPI target.            |
| **Lasso Regression**                   | Linear regression with L1 regularization; useful for feature selection and sparsity.          |
| **Gaussian Process Regression**        | A non-parametric Bayesian approach that provides probabilistic predictions with uncertainty. |
| **Hidden Markov State Switching Model**| A regime-switching model capturing different inflation dynamics across economic states.      |
| **Sparse Regression with Horseshoe Prior** | A Bayesian regression technique promoting sparsity using the horseshoe prior.             |

# Output

Models are evaluated using:

- **Root Mean Squared Error (RMSE)**

With visualizations such as:

- Actual vs predicted CPI values over time
- Feature importance plots (for the regularised methods)

---

# Use of economic variables:

The economic data used in this project is based on insights and variables outlined in:

> **State Street (2022)**. *The Determinants of Inflation*. Boston: State Street.

This reference served as the conceptual basis for selecting relevant macroeconomic indicators.
