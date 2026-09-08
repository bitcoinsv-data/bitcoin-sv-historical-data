# Bitcoin SV (BSV) Historical Metrics & Data 📊
This repository contains open-source datasets tracking the Bitcoin SV (BSV) network, including historical mining revenue, price trends, and wealth distribution data.
## 🔗 Live Tools & Interactive Calculators
The raw data in this repository powers the interactive tools on our website. For real-time calculations, please use the links below:
* **[Live BSV Miner Revenue Simulator](https://bitcoinsv.it/bsv-miner-revenue-simulator/)** - Compare miner economics across BTC, BCH, and BSV as the subsidy disappears.
* **[BSV Price Predictor & Charts](https://bitcoinsv.it/bsv-price/)** - View live price action and historical trends.
* **[The BSV Top 100 Rich List](https://bitcoinsv.it/rich-list/)** - Track the top 100 wallets and wealth distribution on the network.
## 📂 About the Data
The datasets provided here (`.csv` format) are updated every Monday and are free to use for academic research, crypto journalism, and development.

*(Last updated: September 8, 2026)*

**Included files:**
* `bsv-mining-difficulty-YYYY-MM-DD.csv` — network difficulty and price snapshot per update
* `bsv-rich-list-YYYY-MM-DD.csv` — top 100 BSV addresses by balance per update. Source: the [BananaBlocks](https://bananablocks.com/richlist) rich-list API, which ranks every script type. Snapshots dated 2026-09-08 and later include P2SH (`3...`) addresses; earlier snapshots came from the Bitails rich endpoint, which lists P2PKH (`1...`) addresses only, so a few P2SH holders are absent from those files.
---
*Data provided and maintained by the [bitcoinsv.it](https://bitcoinsv.it) team.*
