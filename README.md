PROJECT TITLE
Equity Risk & Return Analysis Using Python

OVERVIEW
This project analyzes the risk and return characteristics of selected
equities using historical market data. The objective is to evaluate
investment performance using standard financial metrics and compare
individual stocks against a market benchmark (NIFTY 50) to support
data-driven investment decisions.

The analysis focuses on both returns and risk, emphasizing risk-adjusted
performance and downside risk, which are critical considerations in
asset management and private investing.

------------------------------------------------------------

DATA SOURCE
Historical daily price data was sourced from Yahoo Finance using the
yfinance Python library. Adjusted prices were used to ensure that stock
splits and dividends were properly accounted for.

Assets analyzed:
- Selected individual equities (e.g., RELIANCE, TCS, INFY)
- Market benchmark: NIFTY 50 Index

Time period:
- January 2019 to present

------------------------------------------------------------

METHODOLOGY

1. Data Collection
   - Downloaded adjusted closing prices for selected stocks and the
     benchmark.
   - Cleaned and aligned data to ensure consistent trading days.

2. Return Calculation
   - Computed daily percentage returns from price data.
   - Annualized daily returns assuming 252 trading days per year.

3. Risk Measurement
   - Calculated annualized volatility to measure return variability.
   - Computed maximum drawdown to assess worst-case peak-to-trough loss.

4. Risk-Adjusted Performance
   - Calculated Sharpe Ratio using a fixed risk-free rate assumption.
   - Compared excess returns relative to risk across assets.

5. Benchmark Comparison
   - Evaluated stock performance relative to the NIFTY 50 index.
   - Assessed whether individual equities outperformed the market on a
     risk-adjusted basis.

6. Visualization
   - Plotted cumulative returns to analyze growth over time.
   - Created risk–return scatter plots to visualize trade-offs between
     risk and reward.

------------------------------------------------------------

KEY METRICS USED
- Daily Returns
- Annualized Returns
- Annualized Volatility
- Sharpe Ratio
- Maximum Drawdown
- Cumulative Returns

------------------------------------------------------------

KEY INSIGHTS
- Higher returns are generally associated with higher volatility,
  confirming the risk–return trade-off.
- Some individual equities outperform the market benchmark on a
  risk-adjusted basis, as indicated by higher Sharpe ratios.
- Maximum drawdown highlights significant differences in downside risk
  between assets, emphasizing the importance of capital preservation.
- Benchmark comparison is essential to distinguish true outperformance
  from overall market movement.

------------------------------------------------------------

TOOLS & TECHNOLOGIES
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Google Colab

------------------------------------------------------------

RELEVANCE TO ASSET MANAGEMENT
This project mirrors real-world asset management analysis by combining
return evaluation, risk measurement, benchmark comparison, and
interpretation of results to support informed investment decisions.

------------------------------------------------------------

AUTHOR
Dhruv Anand
