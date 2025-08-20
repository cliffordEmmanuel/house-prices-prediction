# Predicting House Prices Using Regression Models

**Objective:**
To evaluate the performance of linear vs ensemble regression methods in predicting house prices using the King County housing dataset.

**Methods:**

* Applied **Multi-Linear Regression (MLR)** and **Random Forest Regression (RFR)**.
* Dataset: 21,613 housing records with numerical and categorical features.
* Models trained across multiple random states (10-folds).
* Evaluation metrics: RMSE, MSE, MAE, and R² score.

**Results:**

* **Random Forest Regression** consistently outperformed MLR with:
  * Lower average RMSE (147,967 vs 203,625).
  * Lower MAE (76,995 vs 114,196).
  * Higher R² (0.84 vs 0.70).
* RFR captured **non-linear relationships, feature interactions, and outliers** better than MLR.
* MLR provided interpretability but underperformed on accuracy.

**Insights:**
* **Random Forest is more robust** for complex, non-linear domains like housing prices.
* MLR remains useful when interpretability is prioritized.
* Future work: explore **feature engineering, dimensionality reduction, and ensemble stacking**.

