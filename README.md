## Forward Model (Thermal Conductivity Prediction)

This repository provides a **trained forward model** for predicting the thermal conductivity of metals and multi-component alloys from **alloy composition** and **temperature**. The trained model artifacts are **uploaded to this GitHub repo** so that others can directly run inference without retraining.

### Summary

- We compile, to our knowledge, the **largest experimental dataset** with **6,259 data points**, spanning **49 elements** and temperatures from **0 to 1400 K**.
- Using **composition + temperature** as inputs, we train and benchmark multiple regression models and achieve **R² > 0.99** with **RMSE ≈ 6–9 W/m·K**.

### Inputs / Output

**Inputs**
- Alloy composition
- Temperature **T (K)**

**Output**
- Thermal conductivity **κ (W/m·K)**
