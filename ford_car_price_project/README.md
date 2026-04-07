# 🚗 Ford Car Price Prediction

---

## 📌 Project Overview

This project focuses on predicting **car prices** using machine learning.

It includes:
- Data analysis (EDA)
- Feature encoding techniques
- Model training and comparison

---

## 📂 Dataset

- Dataset: Ford Car Price Dataset
- Rows: 17,966
- Features:
  - Model
  - Year
  - Transmission
  - Mileage
  - Fuel Type
  - Tax
  - MPG
  - Engine Size
  - Price (Target)

---

## 🔍 Steps Performed

### 1. Exploratory Data Analysis (EDA)

- Distribution of price
- Correlation heatmap
- Scatter plots (mileage vs price)
- Boxplots for categorical features

---

### 2. Feature Encoding

Two approaches were tested:

#### ✅ One-Hot Encoding
- Applied to categorical features
- Used for main model

#### ⚠️ Label Encoding
- Applied for comparison
- Not ideal for linear regression

---

### 3. Feature Scaling

- StandardScaler applied to numerical features:
  - year, mileage, tax, mpg, engineSize

---

## 🤖 Model Training

### Model Used:
- Linear Regression

### Train-Test Split:
- 80% training, 20% testing

---

## 📈 Model Performance

### 🔥 One-Hot Encoding Model
- R² Score: ~0.84
- Adjusted R²: ~0.84

### ⚠️ Label Encoding Model
- R² Score: ~0.73

---

## 🧠 Key Insights

- One-Hot Encoding performs significantly better than Label Encoding
- Mileage negatively affects price
- Newer cars have higher prices
- Engine size positively impacts price

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 Future Improvements

- Try Random Forest / XGBoost
- Hyperparameter tuning
- Feature importance analysis

---

## 👨‍💻 Author

Shubham Negi