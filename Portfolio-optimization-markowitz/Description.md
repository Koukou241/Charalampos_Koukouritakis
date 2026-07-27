# Empirical Portfolio Optimization: Markowitz vs. Global Minimum Variance (GMV)

## Academic Project
* **Degree Program:** MSc in Mathematical Finance
* **Institution:** ISEG - Lisbon School of Economics & Management
* **Authorship:** Charalampos Koukouritakis & Academic Project Team

---

## Executive Summary
This project evaluates the empirical performance and robustness of classical portfolio allocation strategies under market uncertainty. Specifically, it contrasts the **Markowitz Mean-Variance (Tangency) Portfolio** with the **Global Minimum Variance (GMV) Portfolio**. 

The study highlights the impact of estimation risk in expected asset returns and demonstrates how parameter uncertainty degrades out-of-sample Sharpe ratios, making the GMV portfolio a more resilient empirical alternative.

---

## Key Achievements & Methodological Highlights
* **Optimization Framework:** Formulated and implemented matrix-based quadratic programming models to construct optimal asset weights subject to budget and short-selling constraints.
* **Estimation Risk Analysis:** Quantified the sensitivity of the Markowitz frontier to mean-return estimation error, demonstrating how parameter noise leads to extreme portfolio weights and out-of-sample degradation.
* **Backtesting Engine:** Built a backtesting pipeline in Python to track performance metrics over time, including cumulative growth, annualized volatility, maximum drawdown, and risk-adjusted return profiles.
* **Empirical Validation:** Confirmed that minimizing total portfolio variance without estimating mean returns yields superior stability and lower drawdown across diverse market conditions.

---

## Technical Stack & Applied Concepts
* **Programming & Tools:** Python 3.10+, NumPy, SciPy (`scipy.optimize`), Pandas, Matplotlib.
* **Quantitative Concepts:** Modern Portfolio Theory (MPT), Mean-Variance Optimization, Efficient Frontier, Global Minimum Variance (GMV), Sharpe Ratio, Risk-Adjusted Returns, Estimation Risk, Backtesting.

---

## Core Analytical Outputs
The execution pipeline generates comparative visual diagnostics:
1. **Cumulative Returns Profile:** Out-of-sample growth trajectories comparing Markowitz, GMV, and benchmark allocations.
2. **Efficient Frontier & Weight Distribution:** Asset weight allocations showcasing the stability of GMV versus the concentration risk in Tangency portfolios.
3. **Risk & Drawdown Metrics:** Rolling volatility and drawdown analysis highlighting downside protection.
