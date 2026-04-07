# 🧠 Machine Learning Projects (Preprocessing + Modeling)

This repository contains multiple real-world datasets where I performed **end-to-end machine learning workflows**, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection (Statistical Methods)
- Model Training & Evaluation

---

## 📂 Projects Included

---

### 🏥 Insurance Cost Prediction

**Type:** Regression (End-to-End ML Pipeline)

#### 🔧 Work Done:
- Data Cleaning & EDA
- Feature Engineering (BMI categories)
- Encoding (Binary + One-Hot)
- Feature Scaling (StandardScaler)
- Feature Selection:
  - Pearson Correlation
  - Chi-Square Test
- Model Training:
  - Linear Regression

#### 📈 Performance:
- R² Score: ~0.80
- Adjusted R²: ~0.79

👉 **Key Insight:** Smoking has the highest impact on insurance charges.

---

### 🚗 Ford Car Price Prediction

**Type:** Regression + Model Comparison

#### 🔧 Work Done:
- Exploratory Data Analysis (EDA)
- Feature Encoding:
  - One-Hot Encoding
  - Label Encoding (for comparison)
- Feature Scaling
- Model Training:
  - Linear Regression

#### 📈 Performance:
- One-Hot Encoding Model:
  - R²: ~0.84
- Label Encoding Model:
  - R²: ~0.73

👉 **Key Insight:** One-Hot Encoding significantly outperforms Label Encoding for linear models.

---

### ❤️ Heart Disease Prediction

**Type:** Classification (Preprocessing Focus)

#### 🔧 Work Done:
- Handling invalid values (0 → mean replacement)
- Target-based EDA
- One-hot encoding
- Feature scaling

👉 **Key Insight:** Data cleaning and feature distribution significantly impact model readiness.

---

### 🦠 COVID-19 Data Analysis (India)

**Type:** Time-Series Data Preprocessing

#### 🔧 Work Done:
- Filtered India-specific data from OWID dataset
- Handled missing values using time-series techniques:
  - Forward fill (ffill)
  - Zero filling (pre-vaccine period)
- Removed redundant features
- Feature selection using correlation
- Feature Engineering:
  - `cases_test_ratio`

👉 **Key Insight:** Testing rate and positivity ratio strongly influence case trends.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## 🚀 What I Learned

- Building **complete ML pipelines**
- Real-world data cleaning techniques
- Feature engineering & transformation
- Statistical feature selection
- Comparing encoding techniques
- Model evaluation and interpretation

---

## 🔜 Next Steps

- Try advanced models:
  - Random Forest
  - Gradient Boosting
- Hyperparameter tuning
- Build pipelines using `sklearn Pipeline`
- Model deployment (Streamlit)

---

## 📌 Project Status

✅ Preprocessing Completed  
✅ Feature Engineering Completed  
✅ Model Training Added  
🔄 Improving models & adding new projects  

---

## 👨‍💻 Author

Shubham Negi