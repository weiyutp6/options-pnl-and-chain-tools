# Options P&L and Option-Chain Tools

Small utilities for option payoffs, implied volatility and chain data.

| Notebook | Content |
|---|---|
| `optionsPnLcurve.ipynb` | Expiry P&L for a multi-leg option position, marking P&L at each strike and the breakeven points. |
| `OptionChain.ipynb` | Reads option-chain screenshots with OpenCV and Tesseract OCR, then computes implied volatility (root finding) and Black-Scholes Greeks per strike. |
| `option_non_equilibrium.ipynb` | Pulls an option chain with `yfinance` and compares market prices with model values. |
| `IVchecker.ipynb` | Scans S&P 500 tickers for average at-the-money implied volatility on the nearest expiry. |

Screenshots and market data are not included.

```bash
pip install numpy pandas scipy matplotlib yfinance opencv-python pytesseract beautifulsoup4 lxml tqdm
```

For research and education only. Not investment advice.
