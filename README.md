# Tail-risk-contagion-in-international-energy-market
This repository contains the code, data, and report for our research project on Tail Risk Contagion and Volatility Spillovers in the global energy markets, focusing on the interplay between green bonds, traditional energy sectors, and sectoral investments.

📄 Abstract
The study explores how extreme market shocks, or "tail risks," propagate across green and traditional energy markets. Leveraging econometric models like ARMA-EGARCH-Skew-t and Quantile Time-Frequency Spillover Analysis, the findings highlight green bonds' dual behavior—as stabilizers during downturns and risk absorbers during upswings. This research provides valuable insights for policymakers and investors in risk mitigation and sustainable finance.

🔍 Research Objectives
Analyze volatility spillovers between green bonds and sectoral indices.
Quantify tail risk contagion under extreme market conditions.
Evaluate dynamic and asymmetric risk spillovers over different time horizons.
Identify net transmitters and receivers of risk across financial sectors.

📈 Methodology
Volatility Modeling: ARMA-EGARCH-Skew-t model to estimate time-varying volatility and capture tail behavior.
Spillover Framework: Quantile VAR model with frequency decomposition to assess shock transmission across markets.
Time Horizons: Short-term (1–5 days), Medium-term (5–20 days), and Long-term (>20 days) frequency bands.

🧠 Key Insights
Traditional energy sectors (e.g., S&P Energy Index) are major risk transmitters.
Green bonds stabilize markets in downturns but are vulnerable in upswings.
Long-term spillovers dominate due to structural and geopolitical factors.
Tail risks behave asymmetrically in bearish vs. bullish markets.

📊 Data Sources
MSCI Green Bond Index
S&P Green Bond Index
S&P 500 Sector Indices (Energy, Financials, Industrials, Healthcare, Utilities, IT)
US Economic Policy Uncertainty Index

🛠️ Tools & Technologies
Python, R
Econometrics packages for GARCH, EGARCH, QVAR modeling
Time-frequency decomposition techniques
Network analysis and heatmaps for spillover visualization
