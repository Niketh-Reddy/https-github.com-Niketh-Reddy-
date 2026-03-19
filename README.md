--
# Multi-Asset Signal Allocation Engine
 
A quantitative, signal-driven allocation engine for Indian passive
investors. Dynamically allocates across three passive index
instruments using 8 auto-computed signals derived from public data.
 
**Live tool: [Open Allocation Engine](https://niketh-reddy.github.io/)**
 
## Three Instruments
- Nifty LargeMidcap 250 TRI Index Fund (equity)
- Nippon India Gold BeES ETF (gold)
- Nifty 10yr Benchmark G-Sec Index Fund (debt)
 
## Eight Signals
Equity: P/E percentile, LM250 vs 10m MA, EPS 3m trend
Gold: Real yield, Gold vs 10m MA, USD/INR trend
Debt: Yield percentile, CPI 6m trajectory
 
## Backtest Results (Jan 2016 – Feb 2026)
| Strategy | CAGR | Sharpe | Max Drawdown |
|---|---|---|---|
| Dynamic (this tool) | 17.5% | 1.22 | −9.4% |
| Static 60/25/15 | 16.2% | 0.96 | −16.3% |
| 100% Equity | 16.6% | 0.61 | −30.6% |
| 100% Gold | 18.3% | 0.87 | −19.0% |
 
*Not financial advice. Past performance does not guarantee future
results. Backtest does not account for taxes or transaction costs.*
 
## Data Sources
NSE historical indices · MOSPI CPI database · investing.com
 
## Author
Niketh Vangala · CFA · CMT · [LinkedIn] https://www.linkedin.com/in/niketh-vangala/
---
