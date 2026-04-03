# ✈️ Airline Fare Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting airline ticket prices using machine learning techniques.  
It explores how factors such as travel date, airline, source/destination, and stops influence ticket pricing.

The goal is to build a **robust regression pipeline** that captures both linear and non-linear relationships in airfare data.

---

## 🎯 Objectives
- Perform data preprocessing and feature engineering on real-world flight data  
- Train and evaluate multiple regression models  
- Compare model performance and identify the best approach  
- Understand pricing patterns and feature impact  

---

## 🧠 Approach

### 1. Data Preprocessing
- Handled missing values and inconsistent formats  
- Converted date/time features into meaningful numerical representations  
- Encoded categorical variables (airline, route, etc.)  

---

### 2. Feature Engineering
- Extracted:
  - Journey day and month  
  - Departure and arrival times  
  - Duration of flights  
- Created structured features for better model learning  

---

### 3. Model Training
Tested multiple models:

- Linear Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  

---

### 4. Model Evaluation
- Used metrics such as:
  - RMSE (Root Mean Squared Error)  
  - R² Score  

👉 Random Forest achieved the best performance, highlighting the **non-linear nature of airline pricing**.

---

## 📊 Key Insights
- Airline pricing is highly **non-linear**  
- Time-related features (departure, duration) significantly affect price  
- Ensemble models outperform linear models  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- scikit-learn  
- Matplotlib / Seaborn  

---

