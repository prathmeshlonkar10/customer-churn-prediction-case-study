# Customer Churn Prediction Case Study

This project focuses on analyzing and predicting customer churn in a B2B energy services setting. Using a combination of exploratory data analysis, feature engineering, and a powerful XGBoost model, the goal was to identify customers at risk of churn and develop actionable retention strategies based on the model's insights.

## 🔍 Key Steps & Methodology
### 1) 🧼 Data Exploration & Cleaning
- Merged customer metadata with detailed pricing history

- Identified missing values, outliers, and distribution skews

- Used Seaborn and Matplotlib for visual exploration of churn vs. non-churn trends

### 2) ⚙️ Feature Engineering
- Converted and extracted date-based features: activation month, tenure, renewal time, etc.

- Generated derived metrics: `net_margin`, `forecast_cons`, `cons_12m`, etc.

- Encoded categorical features and normalized numerical ones for modeling

- Final feature set contained 30+ engineered features

### 3) 🤖 Predictive Modeling
- Trained and optimized a Random Forest classifier to predict customer churn

- Tuned hyperparameters such as `max_depth`,  and `n_estimators`

- Achieved ~90% test accuracy and strong precision-recall performance

- Identified top churn drivers:

### 4) 📈 Visualization & Business Insights
- Created feature importance plots to interpret model decisions

- Analyzed churn probabilities by customer segment and profit tier

- Proposed a targeted discount strategy (20%) for high-value customers at risk of churn

## ✅ Results & Impact
- Achieved 90% accuracy in predicting churn

- Built an explainable model with interpretable business features

- Enabled targeted interventions to retain high-margin clients

- Demonstrated a practical approach to data-driven retention strategy

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://camo.githubusercontent.com/58bfe5f46be0cf6c7d0b34f17a83ad69250fc9180ef95018eacfd283cdc61c10/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6174706c6f746c69622d3243324437323f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6174706c6f746c6962266c6f676f436f6c6f723d7768697465)
![Scikit-learn](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

