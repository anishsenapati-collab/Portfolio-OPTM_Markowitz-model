# Two-Asset Markowitz Portfolio Model

## Overview
This project implements a **two-asset portfolio optimization model based on the Markowitz Mean–Variance framework**. The model analyzes the risk–return characteristics of a portfolio composed of two ETFs:

- **VOO** – Vanguard S&P 500 ETF  
- **BLV** – Vanguard Long-Term Bond ETF  

Using historical return statistics, the spreadsheet calculates portfolio performance metrics and demonstrates how diversification affects portfolio risk and return.
<img width="600" height="400" alt="efficient_frontier" src="https://github.com/user-attachments/assets/258c3197-7d54-4464-8439-85f65216065d" />


---

## Objective
The goal of this project is to:

- Apply concepts from **Modern Portfolio Theory (MPT)**.
- Analyze how different **asset weight combinations** affect portfolio performance.
- Compute key **risk and return metrics**.
- Identify the **risk-adjusted optimal portfolio** using the **Sharpe Ratio**.

---

## Methodology

The model follows the **Markowitz Mean–Variance Optimization approach**:

1. Calculate individual asset statistics:
   - Mean Return
   - Variance
   - Standard Deviation

2. Compute the **covariance between the assets**.

3. Generate portfolio allocations by varying the **weights of VOO and BLV**.

4. Calculate portfolio metrics for each allocation:

Expected Portfolio Return:

\[
E(R_p) = w_1E(R_1) + w_2E(R_2)
\]

Portfolio Variance:

\[
\sigma_p^2 = w_1^2\sigma_1^2 + w_2^2\sigma_2^2 + 2w_1w_2Cov(R_1,R_2)
\]

5. Evaluate **risk-adjusted performance** using the **Sharpe Ratio**.

---

## Metrics Calculated

The model computes the following portfolio statistics:

- **Mean Return**
- **Variance**
- **Standard Deviation (Volatility)**
- **Covariance**
- **Sharpe Ratio**

These metrics allow comparison of different portfolio allocations and help identify efficient portfolios.

---


<img width="733" height="203" alt="Screenshot 2026-03-09 190540" src="https://github.com/user-attachments/assets/bca6ebaf-3c88-40d9-8f31-58ab0718f58e" />



---

## Key Insights

- Diversification between equities and bonds can **reduce portfolio volatility**.
- Portfolio risk depends not only on individual asset risk but also on **covariance between assets**.
- The **Sharpe Ratio** helps identify the **most efficient portfolio allocation**.
<img width="600" height="300" alt="sharpe_vs_allocation" src="https://github.com/user-attachments/assets/b0179eca-b7d9-4548-961b-7ee92b8ab642" />
<img width="600" height="300" alt="risk_return_comparison" src="https://github.com/user-attachments/assets/cebf02fd-7b6f-4777-a242-5d614594e094" />

  

---

## Tools Used

- **Microsoft Excel**
- **Modern Portfolio Theory (Markowitz Model)**
- Financial risk metrics
