# 🧠 Machine Learning Data Preprocessing Projects

This repository contains multiple real-world datasets where I performed **complete data preprocessing pipelines** including cleaning, encoding, feature engineering, scaling, and feature selection.

---

## 📂 Projects Included

### 🏥 Insurance Cost Prediction (Preprocessing)

* Data Cleaning & EDA
* Feature Engineering (BMI categories)
* Encoding (Label + One-Hot)
* Scaling (StandardScaler)
* Feature Selection:

  * Pearson Correlation
  * Chi-Square Test

👉 Key Insight: Smoking has the highest impact on insurance charges.

---

### ❤️ Heart Disease Prediction (Preprocessing)

* Handling invalid values (0 → mean replacement)
* Target-based EDA
* One-hot encoding
* Feature scaling

👉 Key Insight: Data cleaning and feature distribution significantly affect prediction readiness.

---

### 🦠 COVID-19 Data Analysis (India) – *New*

* Filtered India-specific data from OWID dataset
* Handled large-scale missing values using time-series techniques

  * Forward fill (ffill) for testing & policy data
  * Zero filling for vaccination data (pre-vaccine period)
* Removed redundant and constant features
* Performed feature selection based on correlation
* Created custom feature:

  * `cases_test_ratio` (cases vs testing insight)

👉 Key Insight: Testing rate and positivity ratio strongly influence case trends.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## 🚀 What I Learned

* Importance of real-world data cleaning
* Handling missing values in time-series data
* Feature engineering and feature interaction
* Statistical feature selection
* Building ML-ready datasets

---

## 🔜 Next Steps

* Feature Engineering (Lag & Rolling features)
* Model building (Regression & Time Series Models)
* Model evaluation (RMSE, Accuracy, etc.)
* Feature importance using ML models

---

## 📌 Project Status

🔄 Actively Updating
(Currently adding preprocessing → next: model training)

---

## 👨‍💻 Author

Shubham Negi
