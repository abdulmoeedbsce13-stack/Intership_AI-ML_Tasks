# 📈 Task 3: Apple Stock Price Prediction using Random Forest

## 📌 Objective
The goal of this task is to analyze historical stock price data for Apple (AAPL), visualize trends and relationships, and build a predictive model using a **Random Forest Regressor** to forecast the next day's closing price.

---

## 📂 Dataset Used

- **Name:** Apple Stock Data (AAPL)
- **Source:** Yahoo Finance via `yfinance` API
- **Time Period:** 2022-01-01 to 2024-12-31
- **Description:** Historical stock data including Open, High, Low, Close prices, and Volume. Additional technical indicators like moving averages, daily returns, and volatility are calculated for modeling.

---

## 🔧 Tools and Libraries

- `yfinance` – to download real-time stock data  
- `pandas`, `numpy` – for data manipulation  
- `matplotlib`, `seaborn`, `plotly` – for visualization  
- `scikit-learn` – for model training, scaling, and evaluation  
- `joblib` – to save/load the model  

---

## 📊 Tasks Performed

✅ Downloaded AAPL stock data using `yfinance`  
✅ Visualized:
- Closing Price Trend
- Candlestick Chart
- Volume Over Time
- Feature Correlation Heatmap
- Moving Averages

✅ Engineered Features:
- 7-day and 21-day Moving Averages
- Daily Returns
- 7-day Rolling Volatility

✅ Prepared target variable (`Next_Close`) for prediction  
✅ Scaled features using `StandardScaler`  
✅ Trained a **Random Forest Regressor**  
✅ Evaluated model using:
- Mean Squared Error (MSE)
- R² Score  
✅ Compared **Actual vs Predicted** prices using line plot  
✅ Saved and reloaded model for future predictions  
✅ Predicted next closing price for new input data  

---

## 📈 Sample Visuals

🔹 **Closing Price Trend**  
Line plot showing price changes over time.

🔹 **Candlestick Chart**  
Interactive Plotly chart for OHLC view.

🔹 **Volume Plot**  
Visualizes trading activity trends.

🔹 **Heatmap**  
Correlation matrix between technical indicators.

🔹 **Moving Averages**  
Highlights short and mid-term trends.

🔹 **Prediction Plot**  
Compares actual vs predicted closing prices.

---

## 🧠 Key Insights

- Daily returns and moving averages help capture trends and momentum.
- Random Forest Regressor provided accurate predictions with good R².
- Feature scaling significantly improves model performance.
- Model generalizes well on unseen data.
- Saved model and scaler can be reused for real-time predictions.

---


---

## ✅ Completion Checklist

- [x] Data Downloaded  
- [x] EDA Completed  
- [x] Feature Engineering  
- [x] Model Trained  
- [x] Model Evaluated  
- [x] Visualizations Plotted  
- [x] Future Prediction Made  
- [x] Model Saved  

---

## 🔗 Credits

- **Data Source:** [Yahoo Finance - AAPL](https://finance.yahoo.com/quote/AAPL)
- **Library:** [`yfinance`](https://pypi.org/project/yfinance/)
- **Internship Program:** AI/ML Engineering Internship – DevelopersHub Corporation

