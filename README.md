# Quantitative Decision Science

**Mathematics · Data Science · Optimization**

I use statistical learning, optimization and quantitative research to study decisions under uncertainty.

数学、数据与决策：从风险估计，到约束下的资源配置，再到时间序列中的风险管理。

![Python: Research](https://img.shields.io/badge/Python-Research-236d91?style=flat-square) ![SQL: Features](https://img.shields.io/badge/SQL-Features-236d91?style=flat-square) ![Optimization: MILP](https://img.shields.io/badge/Optimization-MILP-236d91?style=flat-square)

## Selected Projects

### 01 · Inventory Allocation Optimization — Flagship

**Operations Research & Decision Optimization**

| Research | [Rolling inventory decisions under demand and supply uncertainty](https://github.com/xsm-math/inventory-allocation) |
|---|---|
| Methods | Mixed-integer programming · demand forecasts · paired Monte Carlo · sensitivity analysis |
| Evidence | 144 synthetic episodes: buffered MILP raises mean economic value by 3.06% / 10.31% / 8.33% across three regimes, while aggregate service stays below base stock. |
| Read | [Formulation and results](https://github.com/xsm-math/inventory-allocation#results) · [Paired evidence](https://github.com/xsm-math/inventory-allocation/blob/main/results/network/paired_comparisons.csv) |

### 02 · Credit Risk Modeling

**Statistical Learning & Risk Decision**

| Research | [From credit-card default scores to probability and cost policies](https://github.com/xsm-math/Risk-Modeling) |
|---|---|
| Methods | WOE/IV logistic scorecard · calibrated trees · SQL · grouped evaluation · PSI |
| Evidence | 30,000 historical UCI records; validation-selected calibrated RF has test AUC 0.7917 / KS 0.4580 / Brier 0.1322. Hypothetical 1:5 normalized cost is 0.5387/customer versus WOE 0.5600. |
| Read | [Protocol and results](https://github.com/xsm-math/Risk-Modeling#results) · [Executed metrics](https://github.com/xsm-math/Risk-Modeling/blob/main/reports/credit/test_metrics.csv) |

### 03 · Gold Allocation Research

**Quantitative Research & Risk Management**

| Research | [Trend timing versus volatility sizing in GLD/cash allocation](https://github.com/xsm-math/invest) |
|---|---|
| Methods | Time-series signals · self-financing backtest · transaction costs · rolling selection · block bootstrap |
| Evidence | 2020–2025 volatility targeting: 12.28% CAGR / 15.97% drawdown; trend: 12.87% / 31.10%. Rolling selection did not beat fixed 50% exposure over 2015–2025. |
| Read | [Research and results](https://github.com/xsm-math/invest#results) · [Reference evidence](https://github.com/xsm-math/invest/blob/main/gold-strategy-research/reports/reference/REPORT.md) |

Results are conditional research findings: synthetic operations, a historical credit cohort with a reused split, and retrospective single-asset prices. Each repository documents its data, baselines, negative results, assumptions and reproduction workflow.

## Technical Stack

| Work | Tools and methods demonstrated in these repositories |
|---|---|
| Data and experiments | Python, NumPy, pandas, SQLite SQL, Matplotlib |
| Statistical learning | scikit-learn, XGBoost, WOE/IV, probability calibration, grouped bootstrap |
| Optimization | SciPy/HiGHS MILP, rolling horizon, Monte Carlo policy evaluation |
| Quantitative research | Time-series signals, transaction-cost accounting, walk-forward selection, block bootstrap |
| Reproducibility | Git, configuration files, aggregate CSV evidence, hashes/manifests, numerical validation |

## Research / Interest Areas

Decision science · operations research · statistical learning · risk modeling · time-series research.

**Data → Prediction → Optimization → Decision**: estimate uncertain quantities, translate them into an explicit objective and constraints, then test the decision against transparent baselines.
