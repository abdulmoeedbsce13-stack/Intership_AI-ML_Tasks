# 🧠 AI/ML Internship Tasks

This repository contains all tasks completed as part of my **AI/ML Engineering Internship** at **DevelopersHub Corporation**. Each task explores a unique aspect of machine learning including **data analysis**, **classification**, and **regression-based prediction** using real-world datasets.

---

## 📁 Tasks Overview

| Task No. | Task Name                        | Model Used                     | Type         | Output                             |
|----------|----------------------------------|--------------------------------|--------------|------------------------------------|
| Task 1   | Iris Dataset Exploratory Analysis| N/A (EDA only)                 | Data Analysis| Visual insights of iris features  |
| Task 2   | Heart Disease Prediction         | Logistic Regression            | Classification| Disease Risk (Yes/No)              |
| Task 3   | Apple Stock Price Prediction     | Random Forest Regressor        | Regression   | Next day’s closing stock price    |

---

## 🌸 Task 1: Iris Dataset Exploratory Analysis

### 🎯 Objective:
Perform **Exploratory Data Analysis (EDA)** on the Iris flower dataset to understand patterns and relationships between flower features.

### 📚 Dataset:
- **Name:** Iris Dataset
- **Source:** Built-in `seaborn` dataset
- **Features:** sepal_length, sepal_width, petal_length, petal_width, species

### 📦 Tools:
- `pandas`, `seaborn`, `matplotlib`

### 📊 Output:
- Scatter plot (sepal length vs width by species)
- Histograms of all numeric features
- Box plots to detect outliers

### 🧠 Insights:
- No missing values
- Clear separation of *setosa*
- Partial overlap between *versicolor* and *virginica*

---

## ❤️ Task 2: Heart Disease Prediction

### 🎯 Objective:
Predict whether a patient has heart disease using features like age, cholesterol, and heart rate.

### 📚 Dataset:
- **Name:** heart.csv
- **Source:** UCI Heart Disease Dataset
- **Features:** age, sex, cp, chol, thalach, oldpeak, slope, etc.

### 📦 Tools:
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `joblib`

### 🧠 Model:
- Logistic Regression

### ✅ Evaluation:
- Accuracy, Confusion Matrix, ROC-AUC, Classification Report

### 📊 Output:
- ROC Curve
- Confusion Matrix
- Feature Importance Bar Chart

### 💾 Saved Files:
- `heart_disease_model.pkl`
- `scaler.pkl`

---

## 📈 Task 3: Apple Stock Price Prediction

### 🎯 Objective:
Use historical Apple (AAPL) stock data to predict the **next day's closing price** using technical indicators.

### 📚 Dataset:
- **Source:** Fetched via `yfinance` API
- **Period:** Jan 2022 – Dec 2024
- **Features:** Open, High, Low, Volume, Daily Return, MA_7, MA_21, Volatility

### 📦 Tools:
- `yfinance`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- `scikit-learn`, `joblib`

### 🧠 Model:
- Random Forest Regressor

### ✅ Evaluation:
- Mean Squared Error (MSE)
- R² Score
- Visual comparison (Predicted vs Actual Prices)

### 📊 Output:
- Candlestick Chart
- Volume Trends
- Feature Correlation Heatmap
- Predicted vs Actual Closing Prices

### 💾 Saved Files:
- `aapl_rf_model.pkl`
- `aapl_scaler.pkl`

---

## 🛠️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/AI-ML-Internship-Tasks.git
cd AI-ML-Internship-Tasks

# Navigate to a specific task
cd task_2_heart_disease_prediction

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn yfinance plotly joblib

# Open notebook
jupyter notebook heart_disease_analysis.ipynb


👤 Author
Abdul Moeed
AI/ML Intern – DevelopersHub Corporation
GitHub: @abdulmoeed13-stack
