# 📈 Stock Market Prediction with Neural Networks

> LSTM-based neural network model for predicting stock price trends.

## 🎯 Problem
Can we predict if a stock will go up or down tomorrow using historical price patterns?

## ✅ What It Does
- Fetches historical OHLCV stock data (via yfinance)
- Trains LSTM model on sliding window sequences
- Predicts next-day closing price direction
- Evaluates with RMSE and directional accuracy

## 🔧 Tech Stack
- **Model:** LSTM (PyTorch / TensorFlow)
- **Data:** yfinance, Pandas
- **Visualization:** Matplotlib, Seaborn

## 📊 Results
| Metric | Score |
|---|---|
| RMSE | [X] |
| Directional Accuracy | [X]% |

## 🚀 Run Locally
```bash
git clone https://github.com/dhxrni/stock-prediction
cd stock-prediction
pip install -r requirements.txt
python train.py --ticker AAPL --epochs 50
```

## ⚠️ Disclaimer
This is a learning project. Do not use for real financial decisions.
```

---
