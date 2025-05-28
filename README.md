# Tail Risk Contagion in International Energy Markets

This repository contains the code, datasets, and report for our research project on **Tail Risk Contagion and Volatility Spillovers** in global energy markets. The study investigates the interactions between green bonds, traditional energy sectors, and sectoral investments under extreme market conditions.

---

## 📘 Abstract

The study explores how extreme market shocks, or "tail risks," propagate across green and traditional energy markets. Leveraging econometric models like **ARMA-EGARCH-Skew-t** and **Quantile Time-Frequency Spillover Analysis**, the findings highlight green bonds' dual behavior—as stabilizers during downturns and risk absorbers during upswings. This research provides valuable insights for policymakers and investors in understanding the dynamics of energy market interconnections.

---

## 📁 Repository Structure

- code/     # Python scripts for data preprocessing and modeling
- data/     # Datasets used in the analysis
- report/     # Final report and visuals
- reference_papers/     # Supporting literature
- README.md     # This file


---

## 🧪 Methodology

1. **Data Collection**: Acquired time-series data from international energy markets and green bond indices.
2. **Modeling**:
   - Used **ARMA-EGARCH-Skew-t** models to capture volatility dynamics.
   - Applied **Quantile Vector Autoregression (QVAR)** for spillover analysis across quantiles.
3. **Analysis**:
   - Investigated tail risk spillovers between traditional and clean energy markets.
   - Analyzed green bonds' role under market stress.

---


## 📈 Key Findings
- Traditional energy sectors (e.g., S&P Energy Index) are major risk transmitters.
Green bonds stabilize markets in downturns but are vulnerable in upswings.
Long-term spillovers dominate due to structural and geopolitical factors.
Tail risks behave asymmetrically in bearish vs. bullish markets.
- **Tail Risks Are State-Dependent**: Spillover effects are amplified during extreme market states.
- **Long-Term Spillovers Dominate**: Tail risk contagion is more pronounced over long-term horizons.
- **Asymmetric Spillover Behavior**: Stronger asymmetry is observed in downside vs. upside shocks.
- **Traditional vs. Clean Energy**:
  - Traditional energy markets are major **risk senders**.
  - Clean energy sectors (solar, geothermal, fuel cell) are **risk receivers** during market stress.

---
## 📊 Data Sources
- MSCI Green Bond Index
- S&P Green Bond Index
- S&P 500 Sector Indices (Energy, Financials, Industrials, Healthcare, Utilities, IT)
- US Economic Policy Uncertainty Index

---

## 📚 References

- Gong, X.-L., Zhao, M., Wu, Z.-C., Jia, K.-W., & Xiong, X. (2023). *Research on tail risk contagion in international energy markets—The quantile time-frequency volatility spillover perspective*. Energy Economics, 121, 106678.  
  👉 [View on RePEc](https://ideas.repec.org/a/eee/eneeco/v121y2023ics0140988323001767.html)

---

## 👨‍💻 Author

- **Siddharth Bisht** – [GitHub Profile](https://github.com/sidbisht)

---


