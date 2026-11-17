# Data

Daily prices for Canada’s Big Six banks and the iShares Core S&P/TSX Capped Composite Index ETF (XIC), from January 2006 to December 2025, and the files derived from them.

Source: Yahoo Finance, downloaded with yfinance 1.8.0 in November 2026, unless stated otherwise. For educational purposes only.


## Files

- adj_close_prices.csv: closing prices adjusted for dividends and stock splits, used to compute total returns.
- close_prices.csv: closing prices adjusted for stock splits only.
- dividends.csv: cash dividends per share, recorded on the ex-dividend date.
- tbill_3m_yield.csv: daily yield (% per year) of 3-month Government of Canada Treasury bills, from the Bank of Canada Valet API (series TB.CDN.90D.MID), used as the risk-free rate.
- zeb_adj_close.csv: adjusted closing prices of the BMO Equal Weight Banks Index ETF (ZEB), 2010–2025, used as a real-world comparison.
- monthly_facts.csv: monthly facts used for the AI commentary (Section 6.2), from January 2007 to December 2025: returns of the six-bank portfolio and of XIC over the month and over 12 months, 12-month volatility and its usual level, best and worst bank over 12 months, and the period (development or test).
- review_months.csv: the 20 test months drawn at random (seed 2026) before any commentary was generated, for the manual review defined in the protocol (Section 6.1).
  
## Limitations

- Yahoo Finance records no capital gains distributions for XIC over the period.
