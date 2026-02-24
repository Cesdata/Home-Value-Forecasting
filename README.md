# House Price Insights: Advanced Regression & Feature Impact 🏠

This project provides a deep dive into real estate valuation by analyzing **81 distinct features** (from structural details to neighborhood quality) to predict house prices and, more importantly, understand the drivers of market value.

---

## 🎯 Project Objectives
* **Predictive Modeling:** Build a high-performance regression model to forecast house prices.
* **Feature Interpretability:** Identify which of the 81 variables (e.g., Year Built, Total Basement Square Footage, Neighborhood) most significantly impact the final price.
* **Automated Pipelines:** Implement a robust Scikit-Learn pipeline for seamless data preprocessing and feature selection.

---

## 🚀 Run it on Google Colab

You can access and execute the complete interactive analysis here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Cesdata/House-Price-Insights-Modeling/blob/main/House_Price_Analysis.ipynb)

---

## 🛠️ Tech Stack & Techniques
* **Language:** Python 3.x
* **Key Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`, `LightGBM`, `Category Encoders`.
* **Feature Engineering:** * `CatBoostEncoder` for high-cardinality categorical variables.
    * `SimpleImputer` & `StandardScaler` for numerical data consistency.
* **Feature Selection:** `Recursive Feature Elimination (RFE)` using a Random Forest estimator to distill the 81 features down to the 40 most impactful ones.
* **Model:** `GradientBoostingRegressor` for optimized predictive power.

---

## 📊 Pipeline Architecture
The project follows a modular "Pipeline" approach to ensure reproducibility and prevent data leakage:
1.  **Numerical Transformer:** Median imputation + Standard Scaling.
2.  **Categorical Transformer:** Frequentist imputation + CatBoost Encoding.
3.  **Feature Selection:** RFE reduces dimensionality to the top 40 features.
4.  **Final Regressor:** Gradient Boosting trained on selected features.

---

## 📫 Contact
**Cesdata** - [Insert your LinkedIn Profile Link Here]
