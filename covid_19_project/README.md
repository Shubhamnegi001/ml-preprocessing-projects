# 🦠 COVID-19 Data Analysis & Preprocessing (India)

## 📌 Project Overview

This project focuses on analyzing and preprocessing real-world COVID-19 data for India using the OWID dataset.
The goal is to clean, transform, and prepare the dataset for future machine learning modeling.

---

## 🎯 Objectives

* Understand COVID-19 trends in India
* Perform data cleaning and preprocessing
* Handle missing values effectively
* Select meaningful features for analysis
* Prepare dataset for machine learning models

---

## 📂 Dataset

* Source: Our World in Data (OWID)
* Contains global COVID-19 data including:

  * Cases
  * Deaths
  * Testing
  * Vaccination
  * Government policies

---

## 🛠️ Preprocessing Steps

### 1. Data Selection

* Filtered dataset for India
* Selected relevant columns for analysis

### 2. Handling Missing Values

* Used forward fill (ffill) for time-series data:

  * `new_tests_smoothed`
  * `positive_rate`
  * `stringency_index`
  * `reproduction_rate`
* Filled vaccination data with 0 (before vaccines rollout)

### 3. Dropping Irrelevant Data

* Removed columns with:

  * All missing values
  * No variation (constant columns)
  * Redundant information

### 4. Data Cleaning

* Converted `date` column to datetime format
* Sorted dataset chronologically
* Ensured consistency across all features

---

## 📊 Features Used

* new_cases
* new_deaths
* reproduction_rate
* positive_rate
* new_tests_smoothed
* stringency_index
* new_vaccinations_smoothed

---

## 📈 Skills Applied

* Data Cleaning
* Missing Value Handling
* Feature Selection
* Time-Series Data Processing
* Exploratory Data Analysis (EDA)

---

## 🚀 Next Steps

* Feature Engineering (Lag & Rolling features)
* Model Training (Regression / Time Series Models)
* Model Evaluation
* Visualization of Predictions

---

## 💻 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 Status

🔄 In Progress
(Currently working on preprocessing → next step: model building)

---

## 🤝 Contribution

This is a learning-based project. Feedback and suggestions are welcome!

---

## 📎 Author

Shubham Negi
