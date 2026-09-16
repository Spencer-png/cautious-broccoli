# Market Signal Pro — GitHub Pages Edition

This version is designed to work as a static GitHub Pages site.

## Setup

1. Create a new GitHub repository.
2. Upload **`index.html`** and **`README.md`** to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.
7. Wait for GitHub Pages to publish the site.

There is no Python server, Node server, database, Docker container, or API key required.

## Data sources

- Crypto: Binance public REST market-data API.
- Stocks/ETFs: Stooq public daily CSV endpoint.

Stock/ETF data is daily in this no-backend version. Crypto supports the interval selector.

## Included

- Candlestick-style price chart
- EMA 21/50/200 overlays
- RSI 14
- MACD histogram
- ATR 14
- Bollinger Bands in the signal engine
- 20-bar breakout/breakdown logic
- Volume confirmation
- LONG / SHORT / NEUTRAL signal
- Confidence score
- Client-side backtesting
- Browser alerts
- Responsive dark dashboard

## Important

This is an educational market-analysis tool. A LONG or SHORT signal is an algorithmic output, not a guarantee or financial advice.

Because the application is static, browser-side alerts only run while the page is open. Server-side alerts that work while your browser is closed would require a backend or external automation service.
