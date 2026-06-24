# 💳 UPI Transactions Data Analysis & Dashboard (2024)

## 📌 Project Overview

This project focuses on cleaning, transforming, and analyzing UPI transaction data for the year 2024. The goal is to build a structured dataset and create an interactive dashboard that provides meaningful insights into transaction patterns, fraud detection, and user behavior.

---

## 🎯 Objectives

* Clean and preprocess raw UPI transaction data
* Ensure data consistency and accuracy
* Perform feature engineering for deeper analysis
* Detect anomalies and outliers
* Build an interactive dashboard for insights

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy) – Data cleaning & preprocessing
* **Power BI** – Dashboard & visualization
* **Excel/CSV** – Data storage

---

## 🔄 Data Cleaning & Processing

The dataset undergoes multiple preprocessing steps:

* Renaming columns to standardized format (snake_case)
* Converting timestamps to proper datetime format
* Handling categorical and boolean variables
* Validating time-based fields (hour, day, weekend)
* Ensuring data integrity (no duplicates, valid values)

---

## ⚙️ Feature Engineering

New features created to enhance analysis:

* **Time-based features**: time_of_day, month, quarter
* **Transaction segmentation**: amount buckets
* **Behavioral insights**: same_bank transactions
* **Weekend/weekday classification**

---

## 📊 Outlier Detection

* Used **IQR (Interquartile Range)** method
* Outliers are flagged, not removed
* Helps identify unusual or high-value transactions

---

## 📈 Dashboard Insights

The Power BI dashboard provides:

* Transaction trends over time
* Fraud detection patterns
* Bank-wise and device-wise usage
* User demographics analysis
* Peak transaction time insights

---

## ✅ Key Highlights

* Clean and structured dataset
* Scalable preprocessing pipeline
* Real-world fintech use case
* Insightful and interactive dashboard

---

## 🚀 Conclusion

This project demonstrates how raw financial data can be transformed into meaningful insights using data cleaning, feature engineering, and visualization techniques. It is useful for understanding digital payment behavior and detecting anomalies in UPI transactions.

---

## 📂 Future Improvements

* Machine learning model for fraud prediction
* Real-time data pipeline
* Advanced analytics (customer segmentation, prediction models)

---

## 👤 Author

**Ansh Pal**

