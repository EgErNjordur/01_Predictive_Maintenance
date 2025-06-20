# 01_Predictive_Maintenance
Predictive maintenance using Scikit-learn

# 🔧 Predictive Maintenance Using Machine Learning

This project builds a machine learning model that predicts equipment failures based on sensor data such as temperature, vibration, and pressure. The goal is to help organizations perform **preventive maintenance** and reduce unplanned downtime.

---

## 📊 Dataset Overview

The dataset simulates readings from industrial equipment:

| Feature          | Description                             |
|------------------|-----------------------------------------|
| `temperature`     | Sensor temperature (°F)                 |
| `vibration`       | Vibration level                         |
| `pressure`        | Internal pressure                       |
| `equipment_type`  | Type of equipment (Pump, Valve, Motor) |
| `equipment_age`   | Age of equipment in years              |
| `failure`         | Target label (1 = failed, 0 = healthy)  |

---

## 🧠 ML Pipeline

1. **EDA** with Matplotlib and Seaborn
2. **Feature Engineering:**
   - Label encoding categorical data
   - Feature scaling using `StandardScaler`
3. **Model Training:**
   - `RandomForestClassifier`
   - 70/30 train-test split
4. **Model Evaluation:**
   - Confusion matrix
   - Precision, recall, F1-score
5. **Model Export:**
   - Saved as `random_forest_model.pkl`

---

## 🛠️ Tools & Libraries
- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Joblib (for model export)

---

## 📂 Project Structure

