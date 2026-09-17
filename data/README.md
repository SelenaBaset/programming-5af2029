# Data

## fund_prices.csv

Daily prices for an investment fund, 2020 to 2025, 1565 business days.

| column | type | description |
|---|---|---|
| `date` | text, `YYYY-MM-DD` | business day |
| `price` | number | closing price |

**This series is simulated, not real market data.** It was generated so that the shape of the
series is realistic: a steady trend with a sharp drawdown and recovery early in the sample.
It is fine for teaching, but do not present it as a real instrument, and replace it with a real
series if you would rather students worked with one.
