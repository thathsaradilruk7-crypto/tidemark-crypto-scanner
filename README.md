# Tidemark — Free Crypto Signal Scanner

A free, open-source market scanner for cryptocurrency traders. Live prices, transparent multi-signal logic, no subscription, no black box.

## Features

- **Live Market Data**: Real-time prices updated every 60 seconds via CoinGecko API
- **Multi-Signal Logic**: 
  - RSI(14) — momentum indicator
  - SMA(20) vs SMA(50) — trend direction
  - Volatility Ratio — squeeze detection
- **Smart Filtering**: Buy signals, Sell signals, Squeeze/breakout watch, or view all
- **Alert Feed**: Real-time notifications when signals change
- **Browser Notifications**: Optional desktop alerts for signal changes
- **Educational**: Fully transparent signal logic, no hidden AI

## How to Use

1. **Open index.html** in any modern web browser
2. **Filter signals** using the chip buttons
3. **Enable notifications** if desired
4. App updates automatically every 60 seconds

## Technical Details

- All calculations run client-side in your browser
- Data from CoinGecko public API (free, no auth)
- Top 30 cryptocurrencies by market cap
- 7 days of hourly price data

## License

MIT License