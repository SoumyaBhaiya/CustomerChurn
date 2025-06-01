# 🛍️ Customer Churn Prediction - Superstore Dataset

This project analyzes customer churn using the [Superstore dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). We define churn behavior, engineer features, train predictive models, interpret them, and provide actionable business insights.

---

## 📁 Dataset

- **Source**: Kaggle - Superstore Dataset
- **Structure**: Transaction-level data including sales, customers, products, and shipping info.
- **Target Variable**: `Churn` (engineered) — 1 if the customer hasn't purchased in the last 6 months, else 0.

---

## 🧠 Project Objectives

1. Define churn and engineer features per customer.
2. Train multiple models:
   - Logistic Regression
   - Random Forest
   - XGBoost
3. Evaluate models using AUC-ROC and classification metrics.
4. Interpret models using SHAP and feature importance.
5. Provide business suggestions to reduce churn.
6. Export results for visualization in Tableau

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`
  - `scikit-learn`, `xgboost`
- **Visualization**: Tableau

