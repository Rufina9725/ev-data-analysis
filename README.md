# 🚗 EV Range Prediction Using Machine Learning

This project predicts the **driving range (in km)** of electric vehicles based on their technical specifications using a Ridge Regression model.

---

## 📊 Project Overview

- **Dataset Size**: 476 electric vehicles
- **Goal**: Predict `range_km` from features like top speed, battery capacity, torque, etc.
- **Target**: `range_km`
- **Features Used**: 11 numerical features
- **Missing Values**: Filled using median
- **Model Used**: Ridge Regression

---

## ⚙️ Model Performance

| Metric             | Value         |
|--------------------|---------------|
| Baseline MAE       | ~85.62 km     |
| Ridge Train MAE    | ~19.91 km     |
| Ridge Test MAE     | ~21.86 km     |

✅ Huge improvement from baseline — reduced error by ~75%

---

## 📈 Visualization

Actual vs Predicted EV Range:





## 🧰 Tools Used

- Python (pandas, numpy)
- scikit-learn (Ridge, pipeline)
- seaborn & matplotlib for visualization
- Git & GitHub for version control






