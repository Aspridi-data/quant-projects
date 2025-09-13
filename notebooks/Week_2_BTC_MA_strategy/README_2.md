\# BTC Moving Average (MA) Strategy



\## Project Goal

Implement a simple Moving Average crossover trading strategy on Bitcoin (BTC-USD) and backtest it to compare against a buy-and-hold approach.



\## Strategy Logic

\- Compute two moving averages of BTC price:

&nbsp; - \*\*Short-term MA:\*\* 20 days

&nbsp; - \*\*Long-term MA:\*\* 50 days

\- Generate trading signals:

&nbsp; - \*\*Buy\*\* when short MA > long MA

&nbsp; - \*\*Sell\*\* otherwise

\- Apply the signals to compute strategy returns.

\- Compare cumulative returns and Sharpe ratio against buy-and-hold.



\## Results

\- \*\*Cumulative returns chart:\*\* see `BTC\_MA\_strategy.ipynb` for plots.

\- \*\*Sharpe ratio of MA strategy:\*\* `X.XX` (replace with your output after running notebook)

\- \*\*Key observations:\*\*

&nbsp; - The MA strategy reduces exposure during some drawdowns.

&nbsp; - Buy-and-hold sometimes outperforms during strong bull runs.

&nbsp; - Strategy performance depends on moving average parameters (20/50 used here).



\## How to Run

1\. Clone the repository.

2\. Open `BTC\_MA\_strategy.ipynb` in Jupyter Notebook.

3\. Ensure BTC CSV files are in the `../data/` folder or use `load\_btc\_csv()` to fetch the latest BTC data.

4\. Run all cells to reproduce results.



\## Files

\- `BTC\_MA\_strategy.ipynb` — Notebook with code, plots, and backtest.

\- `README_2.md` — This file with project explanation.





