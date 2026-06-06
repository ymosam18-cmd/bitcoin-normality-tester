# bitcoin-normality-tester
# Empirical Evaluation of Normality in Bitcoin Returns

An advanced quantitative framework designed to test the market hypothesis: *Are Bitcoin asset returns normally distributed?* This project leverages historical BTC/USD data to analyze higher-order statistical moments and perform structural normality breakdowns.

## Core Statistical Methodology
The engine runs statistical tests to evaluate the distribution of log returns:
1. **Jarque-Bera Test:** Evaluates if the skewness and kurtosis match a normal distribution.
2. **Shapiro-Wilk Test:** Assesses the null hypothesis ($H_0$) of normality on smaller sample windows.
3. **QQ-Plots & Fat-Tail Analysis:** Visualizes the extreme deviations (leptokurtic behavior) compared to a standard Gaussian curve.

## Key Insights
- **Fat-Tails (Leptokurtosis):** Bitcoin exhibits heavy negative/positive tails, proving traditional Risk management models (like standard Value-at-Risk) underprice black-swan events.
- **Skewness:** High asymmetry during momentum regimes.
  
