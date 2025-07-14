# NYC Taxi Trip Duration Prediction 🗽🚕  
> A regression-based machine learning project using real-world taxi ride data from New York City.

![Taxi Image](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/NYC_Taxi_YellowCab.jpg/640px-NYC_Taxi_YellowCab.jpg)

---

## 📌 Project Overview

This project focuses on building machine learning models to **predict the duration of NYC taxi trips** based on historical ride data. By applying data cleaning, exploratory data analysis (EDA), and regression algorithms, we aim to understand what factors most influence trip time and build a model that can estimate it accurately.

---

## 🧠 Problem Statement

> "Can we accurately predict NYC taxi trip duration using ride-specific features like pickup time, passenger count, and vendor ID?"

With millions of daily rides, efficient trip time estimation is critical for customer satisfaction, fleet optimization, and route planning. This project aims to build a regression model that minimizes error and supports intelligent transportation decisions.

---

## 📂 Dataset

- **Source**: NYC Taxi & Limousine Commission (TLC)  
- **Format**: CSV  
- **Size**: ~50,000 records  
- **Key Features**:
  - `pickup_datetime`, `dropoff_datetime`
  - `passenger_count`, `vendor_id`
  - `trip_duration` (Target Variable)

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Scikit-learn
- XGBoost
- GridSearchCV
- Google Colab

---

## 📊 Exploratory Data Analysis (EDA)

The EDA was structured using the **UBM rule**:
- **U**nivariate Analysis
- **B**ivariate Analysis
- **M**ultivariate Analysis

15+ insightful charts were created to discover:
- Rush hour patterns
- Impact of passenger count
- Weekend vs weekday trends
- Vendor-specific behaviors

---

## 🤖 ML Models Used

| Model             | R² Score | RMSE (in seconds) |
|------------------|----------|------------------|
| Linear Regression| 0.7923   | ~297.5           |
| Lasso Regression | 0.6154   | ~404.9           |
| XGBoost Regressor| **0.7923** | **~297.5**       |

✅ **XGBoost performed the best**, showing excellent generalization after hyperparameter tuning.

---

## 📈 Evaluation Metrics

- **MAE** (Mean Absolute Error)
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score**
- **Adjusted R²**

---

## ✅ Conclusion

This project demonstrates how historical ride data can be turned into actionable intelligence using machine learning. The XGBoost model achieved strong performance, and with further enhancements (e.g., incorporating weather or traffic data), the model could become even more impactful for real-time systems.

---

## 🚀 Future Improvements

- Add external data like traffic, weather, and geolocation routes
- Use deep learning models like LSTM for time-series prediction
- Deploy the model as an API using Flask or FastAPI

---

## 📌 Project Status

✅ Completed and functional  
📈 Ready for portfolio showcase  
🧠 Open to future enhancements

---

## 👩‍💻 Author

**Srishti Singhal**  
_Data Science Enthusiast | B.Tech CSE_  
📧 [srishtisinghal6125@gmail.com]  
🔗 [(https://www.linkedin.com/in/srishti-singhal-601ab1277/)]

---

## ⭐ Star this repo if you found it helpful!  
