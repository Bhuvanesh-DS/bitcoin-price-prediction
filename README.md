# 🪙 Bitcoin Price Prediction

Predicting Bitcoin closing prices using historical market data and Machine Learning regression techniques.

---

## 📌 Problem Statement

Bitcoin prices are highly volatile and influenced by multiple market factors. This project builds a Machine Learning model to predict the **closing price** of Bitcoin using features like Open, High, Low, Adjusted Close, and Volume from historical BTC-USD data.

---

## 📊 Dataset

- **Source:** Yahoo Finance (BTC-USD historical data)
- **File:** `BTC-USD.csv`
- **Features used:** `Open`, `High`, `Low`, `Adj Close`, `Volume`
- **Target:** `Close` price

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading & preprocessing |
| NumPy | Numerical operations |
| Scikit-learn | ML model & evaluation |
| Matplotlib | Visualization |
| Jupyter Notebook | Development environment |

---

## ⚙️ Methodology

1. **Data Loading** — Loaded BTC-USD CSV, parsed dates
2. **Preprocessing** — Handled missing values, set Date as index
3. **Feature Engineering** — Selected Open, High, Low, Adj Close, Volume as features
4. **Train-Test Split** — 80/20 split (no shuffle — time-series order preserved)
5. **Feature Scaling** — StandardScaler applied to training and test sets
6. **Model Training** — Linear Regression model
7. **Evaluation** — MAE, MSE, RMSE, R² Score
8. **Visualization** — Actual vs Predicted price plot
9. **Future Prediction** — Sample input prediction

---

## 📈 Model Performance

| Metric | Score |
|---|---|
| MAE | *(update with your value)* |
| RMSE | *(update with your value)* |
| R² Score | *(update with your value)* |

---

## 📁 Project Structure

```
bitcoin-price-prediction/
├── bitcoin_assignment.ipynb   ← Main Jupyter notebook
├── BTC-USD.csv                ← Dataset (add this file)
├── requirements.txt           ← Python dependencies
└── README.md                  ← Project documentation
```

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/Bhuvanesh-DS/bitcoin-price-prediction.git
cd bitcoin-price-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook bitcoin_assignment.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
jupyter
```

---

## 🔮 Future Improvements

- [ ] Add LSTM deep learning model for better time-series forecasting
- [ ] Integrate Prophet for trend + seasonality decomposition
- [ ] Build a Streamlit dashboard for live predictions
- [ ] Add more technical indicators (RSI, MACD, Bollinger Bands)

---

## 👤 Author

**Bhuvanesh S**
📍 Bengaluru, India
📫 bhuvanesh9602@email.com
🔗 [LinkedIn](https://l1nk.dev/7ppsxgs) | [GitHub](https://github.com/Bhuvanesh-DS)

---

*Part of my Data Science portfolio — built during internship at First Quadrant Labs*
