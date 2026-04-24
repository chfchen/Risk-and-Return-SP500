**Title:**
**Risk and Return: A Data-Driven Statistical Analysis of the S&P 500**
  
**Hypotheses:**
  1. Higher investment risk does not consistently correspond to higher realized returns
  2. Time aggregation and diversification reduce risk and stabilize returns
  3. SPY daily returns approximately follow a normal distribution

**Objectives:**
  1. To statistically investigate the dynamic risk-return relationship using historical data
  2. To study the effects of time aggregation and diversification on the portfolio risk-return relationship
  3. To evaluate how different return distribution assumptions affect the estimation of downside risk (Value at Risk)

**Data Source:**
  1) Daily adjusted prices of SPDR S&P 500 ETF Trust from 1994 to 2024
  2) Selected S&P 500 component stocks from 2005 to 2024

**Risk and Return Measurements:**
  1) Prices: Adjusted closing prices
  2) Returns: Daily, annual, and multi-year (CAGR)
  3) Risk: Standard deviation of daily returns scaled by the square-root-of-time rule

**Methods:**
  1) Descriptive statistics and correlation analysis, for both time-series and cross-sectional
  2) Distribution fitting: Normal distribution, t-distribution, Gaussian mixture models (two-component)
  3) Statistical testing: Q–Q plots, Jarque-Bera (JB) test, Anderson-Darling (AD) tests
  4) Value at Risk (VaR) estimation
  5) Monte Carlo simulation
  6) Outlier Effect: Isolation Forest outlier detection

**Analysis Tools:**
  1) Python
  2) Microsoft Excel

**Research Findings**
1) “High risk, high return” is not a universal rule. Across individual stocks and short-term horizons, risk primarily increases uncertainty rather than returns. Correlations are regime-dependent: positive during stable/bull markets but negative during bear markets.
2) Diversification and time horizon change correlations. Monte Carlo simulations and long-term data show that diversification and time aggregation substantially reduce return dispersion and stabilize outcomes, with diminishing marginal benefits as portfolio size increases.
3) Financial returns deviate from normality due to heavy tails and skewness. Using normal distributions underestimates downside risk, while Student 's-t and GMM provide more accurate tail-risk estimates.

**Limitations & Bias:**
1) This research only analyzes S&P 500 stocks that remained listed throughout the study period. This causes survivorship bias, as “failed” companies are excluded from the sample set. Therefore, the observed risk-return relationship may not fully represent the broader universe of U.S. stock market.

