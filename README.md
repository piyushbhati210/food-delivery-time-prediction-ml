# 🍔 Food Delivery Time Prediction 🚀

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-green)
![Model](https://img.shields.io/badge/Best%20Model-XGBoost-success)

---

## 📌 Project Overview
This project builds a **machine learning regression model** to predict food delivery time (in minutes) using real-world delivery data.

📉 Late delivery → customer dissatisfaction  
📈 Accurate prediction → better user trust  

---

## 🎯 Objective
- Perform EDA & data preprocessing  
- Engineer meaningful features (distance, time)  
- Train multiple ML models  
- Compare performance using MAE, RMSE, R²  
- Select best model for prediction  

---

## 📊 Dataset Information
- 📦 Train Records: **45,593**
- 📦 Test Records: **~11,000**
- 🔢 Features: **12**
- 🎯 Target: `Time_taken (min)`

---

## ⚙️ Feature Engineering

### 📍 1. Distance (Haversine Formula)
- Calculated using latitude & longitude  
- Converts raw GPS → real-world distance (km)

### 🕒 2. Order Hour
- Extracted from time column  
- Helps capture peak-hour delays  

---

## 🧠 Machine Learning Models

| Model | MAE | RMSE | R² Score |
|------|-----|------|---------|
| Linear Regression | 5.63 | 7.05 | 0.43 |
| Decision Tree | 3.46 | 4.38 | 0.78 |
| Random Forest | 3.21 | 4.06 | 0.81 |
| ⭐ XGBoost | **3.17** | **3.98** | **0.8195** |

🏆 **Best Model: XGBoost**

---

## 📈 Model Pipeline
1. Data Loading  
2. Data Cleaning  
3. Feature Engineering  
4. Encoding & Scaling  
5. Train/Test Split (80/20)  
6. Model Training  
7. Evaluation (MAE, RMSE, R²)  
8. Prediction  

---

## 🔍 Key Insights
- 🚦 Traffic density strongly affects delivery time  
- 📍 Distance is a top predictor  
- ⭐ Delivery ratings influence performance  
- 🌙 Peak hours increase delivery time  
- 🌦 Weather impacts delays  

---

## 📊 Visualizations
- Delivery time distribution (Histogram)  
- Distance vs Delivery Time (Scatter)  
- Traffic vs Time (Bar chart)  
- Feature importance (Random Forest)  
- Actual vs Predicted (XGBoost)  

---

## 🛠 Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- XGBoost  

---

## 📂 Project Structure
