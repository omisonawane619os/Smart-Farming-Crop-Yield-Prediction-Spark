# 🌾 Smart Farming Crop Yield Prediction using PySpark

This project implements an **end-to-end Big Data Machine Learning pipeline** using **Apache Spark (PySpark)** to analyze smart farming data and predict **crop yield per hectare**.  
It includes data cleaning, feature engineering, regression modeling, clustering, and export of results for **Tableau visualization**.

---

## 🚀 Project Overview

Modern agriculture generates large volumes of sensor and environmental data.  
This project demonstrates how **Spark MLlib** can be used to:

- Process agricultural datasets efficiently
- Predict crop yield using multiple ML models
- Identify patterns through clustering
- Export results for business intelligence tools (Tableau)

---

## 🧠 Machine Learning Models Used

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosted Trees (GBT)** ✅ *(Best performing model)*

---

## 🛠️ Tech Stack

- **Python 3**
- **Apache Spark (PySpark)**
- **Spark MLlib**
- **Pandas**
- **Tableau (for visualization)**

---

## 📂 Dataset

**File:** `Smart_Farming_Crop_Yield_2024.csv`

The dataset contains agricultural and environmental data such as:

- Region
- Crop Type
- Soil Type
- Irrigation Type
- Soil Moisture
- Temperature
- Rainfall
- Humidity
- Fertilizer Usage
- Crop Yield (Target Variable)

> ⚠️ Column name variations are automatically handled in the pipeline.

---

## ⚙️ Project Structure

