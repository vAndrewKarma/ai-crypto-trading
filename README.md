# ai-crypto-trading

## Project Overview
**ai-crypto-trading** is a Python-based project designed to develop an AI-driven cryptocurrency trading bot focused on **short trading** strategies. The bot will operate in real-world conditions using historical and real-time crypto market data, primarily through the `ccxt` library.

## Objectives
- Build a **real-world trading bot** that executes short positions on major cryptocurrencies like BTC and ETH.
- Implement and evaluate different **technical analysis indicators** and **AI-based strategies** using experiment notebooks.
- Use **1-minute historical crypto transaction data** from **2013 to 2023** for training and backtesting.
- Develop a production-ready model and prepare it for **publication/deployment**.

## Key Technologies
- **Python** – core programming language
- **ccxt** – unified API for multiple crypto exchanges
- **pandas-ta** – technical indicators
- **Jupyter Notebooks** – experimentation and prototyping
- **NumPy / pandas** – data manipulation and analysis
- **matplotlib / seaborn** – visualization
- **scikit-learn / TensorFlow (optional)** – machine learning


## Folder Structure (Planned)
ai-crypto-trading/
├── data/ # 1-minute data from 2013-2020
├── notebooks/ # Jupyter experiments and strategy tests
├── src/
│ ├── indicators/ # Custom TA indicators
│ ├── strategies/ # Strategy logic modules
│ ├── backtest/ # Backtesting engine
│ ├── risk/ # Risk management logic
│ ├── trading/ # Live/paper trading interface using ccxt
│ └── utils/ # Helpers, logging, config mgmt
├── models/ # Trained model exports
├── tests/ # Unit and integration tests
├── requirements.txt
└── README.md

## Notes
- The primary exchange interface will be **Binance** via `ccxt`.
