# Diabetes Prediction Expert System & Machine Learning Models

This repository contains a **hybrid system** for predicting diabetes using both an **expert system** based on predefined medical rules and **machine learning models** (XGBoost, LightGBM, CatBoost).

---

## Project Overview

This project demonstrates:

1. **Expert System**: A rule-based system that calculates a risk score for diabetes based on glucose level, BMI, insulin, age, blood pressure, skin thickness, and genetic predisposition.
2. **Machine Learning Models**: Three supervised learning models trained on the same dataset:
   - **XGBoost**
   - **LightGBM**
   - **CatBoost**
3. **Evaluation**: Accuracy and classification reports are printed for all models and the expert system. The expert system also provides detailed logs of triggered rules for each patient.

---

## Dataset

- Source: [Diabetes Dataset]([https://raw.githubusercontent.com/abieniek03/Diabetes-Prediction-Expert-System/refs/heads/main/diabetes.csv](https://www.kaggle.com/datasets/saurabh00007/diabetescsv))
- Features include:
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`
- Target:
  - `Outcome` (0 = Healthy, 1 = Diabetes)
