# Pairs-Trading

This repository is dedicated to exploring **pairs trading** strategies — a form of statistical arbitrage where two historically correlated assets are traded based on the divergence and convergence of their price relationship. The goal is to learn, experiment with models, and attempt to develop a profitable strategy.

## 📘 Project Overview

The project is built in a modular fashion using Python classes and Jupyter Notebooks, focusing on:

- Generating trading **signals** based on asset price relationships
- Applying **strategies** that act on those signals
- **Backtesting** the strategy on synthetic or real data

This forms a base for developing and testing various pairs trading models using real-world or simulated price series.

**Note:** The current implementation is intentionally simplified and may suffer from overfitting and look-ahead bias. These issues are known and will be addressed in future iterations as part of the learning and development process.

## 🧠 Learning Goals

- Understand the intuition and mathematics behind pairs trading
- Learn to implement signal-based strategies in code
- Apply backtesting techniques and performance analysis
- Eventually integrate more complex statistical models and real data

## 📂 Files

- `main.ipynb`: Contains the core implementation of the framework and a working example with a moving average-based signal.
- Additional files to be added as the project evolves.

## ⚙️ Technologies Used

- Python 3.x
- `pandas`, `numpy` for data manipulation
- `matplotlib` for visualization

Install dependencies with:

```bash
pip install pandas numpy matplotlib
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/pairs-trading.git
   cd pairs-trading
   ```

2. Launch Jupyter and run the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

## 📈 Planned Features

- Cointegration tests (e.g. Engle-Granger, Johansen)
- Z-score or Bollinger-band style signal generation
- Real price data integration (e.g. via `yfinance`)
- Risk management features (position sizing, stop-loss)
- Performance tracking and parameter tuning

## 📄 License

MIT License

---

*This is a personal learning project — contributions or feedback are welcome as I iterate toward a more robust pairs trading framework.*
