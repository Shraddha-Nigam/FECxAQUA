## FECxAQUA: Volatility & Risk Modeling

This project is a quantitative finance tool built to analyze, forecast, and hedge against market volatility. It moves beyond traditional "Normal Distribution" assumptions to protect portfolios from extreme market events (Fat-Tails) and volatility clustering.

### Project Goals

-Identify Defensive Assets: Screen the NSE for stocks with Beta < 1.0 and high Sortino Ratios.

-Model Extreme Risk: Analyze tail-risk using Extreme Value Theory (EVT) and non-normal distributions (Student-t, Skewed-t).

-Volatility Forecasting: Implement dynamic models like GARCH, EGARCH, and Heston to predict market stress.

-Optimize Hedging: Backtest cost-efficient strategies including Collars, Protective Puts, and Put Butterflies.

### Key Features

-Dynamic Models: GARCH family, HAR-RV, and Regime-Switching models.

-Risk Metrics: Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR).

-Strategy Engine: Automated screening and hedging cost analysis across multiple sectors (Banking, FMCG, IT, etc.).

### Tech Stack

Language: Python

Libraries: yfinance, arch, statsmodels, pandas, scipy
