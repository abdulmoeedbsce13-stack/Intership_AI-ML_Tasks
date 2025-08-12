# 🫀 Task 2: Heart Disease Prediction using Logistic Regression

## 📌 Objective
The goal of this task is to perform Exploratory Data Analysis (EDA), clean the dataset, build a **Logistic Regression** model, evaluate its performance, and make predictions on heart disease diagnosis using patient features.

---

## 📂 Dataset Used

- **Name:** Heart Disease Dataset  
- **Source:** CSV file (`heart.csv`)  
- **Description:** This dataset contains medical records for 303 patients with attributes like age, sex, cholesterol levels, and more. The target variable indicates the presence (`1`) or absence (`0`) of heart disease.

---

## 🔧 Tools and Libraries

- `pandas` – for data loading and inspection  
- `numpy` – for missing value handling  
- `matplotlib` – for plotting and charts  
- `seaborn` – for advanced visualizations  
- `scikit-learn` – for model building and evaluation  
- `joblib` – for saving and loading the trained model

---

## 📊 Tasks Performed

✅ **Loaded the Dataset** using `pandas.read_csv()`  
✅ **Cleaned the Dataset:**  
- Replaced `?` with `NaN`  
- Converted object columns to numeric  
- Removed rows with missing values  

✅ **Performed EDA and Visualizations:**  
- Target variable distribution  
- Age vs heart disease histogram  
- Correlation matrix  
- Pair plots of selected features  

✅ **Built and Trained a Logistic Regression Model**  
✅ **Evaluated the Model:**  
- Confusion matrix  
- Accuracy score  
- Classification report  
- ROC-AUC score and ROC curve  

✅ **Extracted Feature Importance**  
✅ **Predicted Heart Disease Risk for New Patients**  
✅ **Saved the Model and Scaler using `joblib`**

---

## 📈 Sample Visuals

🔹 **Count Plot (Target Variable)**  
Shows the distribution of patients with and without heart disease.

🔹 **Age-wise Distribution**  
Histogram showing how age relates to heart disease presence.

🔹 **Correlation Heatmap**  
Displays relationships between all numerical features.

🔹 **Pair Plot**  
Helps visualize clusters and relationships across selected features.

🔹 **ROC Curve**  
Measures model performance based on tradeoff between TPR and FPR.

🔹 **Feature Importance Bar Plot**  
Shows which features most strongly influence the model.

---

## 🧠 Key Insights

- The dataset had missing values marked as `?`, which were cleaned.
- Logistic Regression showed good separation ability.
- `thalach`, `cp`, and `oldpeak` were among the most influential features.
- ROC-AUC score provides a strong indication of the model's performance.
- The model can be reused by saving it using `joblib`.

---


## ✅ Completion Checklist

- [x] Dataset Loaded  
- [x] Data Cleaned  
- [x] EDA Completed  
- [x] Logistic Regression Model Trained  
- [x] Evaluation Done (ROC, Accuracy, CM)  
- [x] Prediction on New Patient  
- [x] Model Saved  

---

## 🔗 Credits

- **Dataset Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Internship Program:** AI/ML Engineering Internship – DevelopersHub Corporation

