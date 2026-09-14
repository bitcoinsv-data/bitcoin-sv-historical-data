# Bitcoin SV (BSV) Historical Metrics & Data 📊
This repository contains open-source datasets tracking the Bitcoin SV (BSV) network, including historical mining revenue, price trends, and wealth distribution data.
## 🔗 Live Tools on bitcoinsv.it
These datasets are weekly snapshots of the same on-chain sources behind the live tools on our website. For current figures, use the tools directly:
* **[BSV Top 100 Rich List](https://bitcoinsv.it/rich-list/)** - Top 100 addresses by balance, wealth concentration and top-10 distribution chart.
* **[BSV Miner Revenue Simulator](https://bitcoinsv.it/bsv-miner-revenue-simulator/)** - Miner economics across BTC, BCH and BSV as the block subsidy shrinks.
* **[BSV Price and Market Data](https://bitcoinsv.it/bsv-price/)** - Live BSV price, chart and market data.
* **[BSV Live CoinMarketCap Ranking](https://bitcoinsv.it/bsv-coinmarketcap-ranking/)** - Daily-updated position of BSV in the top 100 by market cap.
* **[BSV Energy Consumption](https://bitcoinsv.it/bsv-energy-consumption/)** - Measured network energy use per block and per transaction, with the method published.
* **[BSV Satoshi Converter](https://bitcoinsv.it/bsv-satoshi-converter/)** - Sats to BSV and USD at the live rate.

## 📦 Other Repositories
* **[bsv-energy-consumption](https://github.com/bitcoinsv-data/bsv-energy-consumption)** - Energy measurement data and methodology behind the energy page.
* **[bsv-paper-wallet](https://github.com/bitcoinsv-data/bsv-paper-wallet)** - Offline, single-file BSV paper wallet generator.

## 📂 About the Data
The datasets provided here (`.csv` format) are updated every Monday and are free to use for academic research, crypto journalism, and development.

*(Last updated: September 14, 2026)*

**Included files:**
* `bsv-mining-difficulty-YYYY-MM-DD.csv` — network difficulty and price snapshot per update
* `bsv-rich-list-YYYY-MM-DD.csv` — top 100 BSV addresses by balance per update. Source: the [BananaBlocks](https://bananablocks.com/richlist) rich-list API, which ranks every script type. Snapshots dated 2026-09-08 and later include P2SH (`3...`) addresses; earlier snapshots came from the Bitails rich endpoint, which lists P2PKH (`1...`) addresses only, so a few P2SH holders are absent from those files.
---
*Data provided and maintained by the [bitcoinsv.it](https://bitcoinsv.it) team.*
