# 🗽 NYC Taxi Trip Duration Prediction 🚖  
A machine learning project to predict the trip duration of NYC taxi rides using real-world geospatial and time-based data.

---

## 📁 Overview

This project uses a dataset of over **1.4 million taxi rides in NYC** to build and evaluate machine learning models for predicting **trip duration**.

It covers the **end-to-end ML pipeline**:
- Data cleaning & preprocessing
- Feature engineering (distance, time, rush hour flags)
- Outlier handling
- Model training & evaluation
- Feature importance & explainability

---

## 🧠 Objective

> Accurately predict how long a taxi ride will take using factors like pickup time, passenger count, pickup/dropoff locations, and more.

This kind of prediction has real-world use cases in:
- Dynamic pricing
- Route planning
- ETA prediction for ride-sharing apps

---

## 📊 Dataset

- ✅ **Source**: [NYC Taxi Trip Duration](https://drive.google.com/drive/folders/1ehYgf0ziDvse5WwGFz_-ECamMQHtBMVT)
- 💡 **Size**: 1.4M+ rows, 19+ features
- 🔍 **Target**: `trip_duration` 

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Lasso Regression
- Linear Regression
- XGBoost

---

## 🚀 Models Trained

| Model              | MAE     | RMSE    | R² Score |
|-------------------|---------|---------|----------|
| Lasso Regression  | 275.40  | 400.01  | 0.6247   |
| Linear Regression | 275.29  | 399.94  | 0.6248   |
| **XGBoost**        | **187.15** | **287.71** | **0.8058** |

🎯 **Final Model Chosen**: `XGBoost Regressor`  
Due to its high accuracy, ability to handle non-linear data, and better generalization.

---

## 🔍 Feature Importance (XGBoost)

Top features impacting trip duration:
- `trip_distance_km`
- `is_weekend`
- `pickup_hour`
- `is_rush_hour`

Used XGBoost’s `.plot_importance()` method to visualize gain-based feature importance.

---

## 📈 Evaluation Metrics

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**  
- **R² and Adjusted R²**  
- **Cross-Validation**  
- **Hyperparameter Tuning with GridSearchCV**

---

## 📌 Key Learnings

- Hands-on experience with **real-world regression problems**
- Built strong data preprocessing & feature engineering skills
- Learned to evaluate and explain models beyond just accuracy
- Understood how **feature importance** helps in interpretation

---

## ✅ Next Steps (Optional Ideas)

- Deploy with **Streamlit or Flask**
- Use SHAP for local/global interpretability
- Build a real-time prediction dashboard

---

## 📂 Project Structure

