Credit Limit Prediction using Machine Learning
#  Project Overview

This project focuses on predicting credit card credit limits using machine learning. By analyzing customer spending and repayment behavior, we developed models that can help financial institutions automate credit limit decisions, improve risk management, and enhance the customer experience.

# Dataset & Preprocessing

1.Exploration & Cleaning

Analyzed dataset structure, types, and distributions.

Handled missing values in:

MINIMUM_PAYMENTS → Median imputation

CREDIT_LIMIT → Mean imputation

# Feature Engineering

Created impactful features such as:

Monthly Average Purchases

Credit Limit Utilization Ratio

Payment-to-Balance Ratio

Scaling

Standardized numerical features to normalize ranges.

# Modeling Approach

We developed and benchmarked two regression models:

 Linear Regression (baseline)

 Random Forest Regressor (ensemble model)

 Training & Evaluation

Data split: 80% training / 20% testing

Metrics used: MAE, MSE, RMSE, R²

📈 Results

Linear Regression:

R² ≈ 0.60 → Limited predictive accuracy

Random Forest Regressor:

R² = 0.97 → Explains 97% of variance in credit limits


✅ On average, the Random Forest model’s predictions were highly accurate and significantly outperformed Linear Regression.

📊 Visualizations

Exploratory Analysis: Static visualizations (Matplotlib/Seaborn) for feature insights

Model Comparison: Interactive Plotly charts showing predicted vs. actual credit limits

🏆 Conclusion

Random Forest Regressor proved to be highly effective for credit limit prediction.

Demonstrated strong predictive power, robust feature engineering, and clear communication of results through visualizations.

Potential real-world application in credit risk management and automated decision-making systems.

📂 Project Structure
├── data/                # Dataset (raw & processed)
├── notebooks/           # Jupyter notebooks (EDA, modeling, evaluation)
├── src/                 # Source code (feature engineering, model scripts)
├── visuals/             # Static & interactive visualizations
└── README.md            # Project documentation

🔮 Future Enhancements

Incorporate gradient boosting models (XGBoost, LightGBM)

Perform hyperparameter tuning for Random Forest

Deploy as an API / Web App for real-time predictions

✍️ Developed with Python (Pandas, Scikit-learn, Matplotlib, Seaborn, Plotly)
