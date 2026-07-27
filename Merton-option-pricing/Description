# Option Pricing under Merton’s Jump-Diffusion Model: A Finite Difference Approach

## Academic Project
* **Degree Program:** MSc in Mathematical Finance
* **Institution:** ISEG - Lisbon School of Economics & Management
* **Author:** Charalampos Koukouritakis & Academic Proyect Team

---

## Executive Summary
This project delivers a high-precision numerical solver for pricing European call options under Merton's Jump-Diffusion model. The core objective was to solve the underlying Partial Integro-Differential Equation (PIDE) by combining spatial Finite Differences (FD) with a second-order Backward Differentiation Formula (BDF2) time-stepping scheme, and to benchmark the results against closed-form analytical solutions.

---

## Key Achievements & Methodological Highlights

* **PIDE Numerical Engine:** Formulated and implemented a full discretization scheme to handle non-local integral jump terms, solving the resulting sparse systems efficiently using `scipy.linalg`.
* **High-Order Time Stepping:** Implemented a BDF2 scheme to achieve temporal stability and maintain a second-order convergence rate $O(k^2)$.
* **Analytical Validation:** Developed Merton's exact infinite-series pricer based on weighted Black-Scholes call evaluations to benchmark numerical accuracy.
* **Rigorous Error Analysis:** Conducted comprehensive numerical diagnostics, verifying spatial $O(h^2)$ and temporal $O(k^2)$ convergence in $L^\infty$-norm, alongside local pointwise error profiling at the strike.

---

## Technical Stack & Applied Concepts
* **Programming & Tools:** Python 3.10+, NumPy, SciPy (`scipy.linalg`, `scipy.stats`), Matplotlib.
* **Quantitative Concepts:** Stochastic Calculus, Jump-Diffusion Processes, Partial Integro-Differential Equations (PIDEs), Numerical Linear Algebra, Finite Difference Methods, BDF2 Scheme, Option Pricing & Derivatives Valuation.

---

## Core Analytical Outputs
The implementation performs automated validation tests and produces three primary quantitative diagnostics:
1. **Option Price Profile:** Numerical option values vs. intrinsic payoff at maturity across a range of spot prices.
2. **Pointwise Error Distribution:** Absolute error profile mapped across the log-price space $x = \ln(S)$, centered at strike $x_K$.
3. **Convergence Analysis:** Log-log error plots demonstrating joint and isolated spatial $O(h^2)$ and temporal $O(k^2)$ convergence against theoretical limits.
*
