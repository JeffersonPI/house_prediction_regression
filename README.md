# House Price Prediction Using Machine Learning

Machine Learning regression project for predicting California house prices using Random Forest and XGBoost with preprocessing, hyperparameter tuning, residual analysis, and model evaluation.

---

## Project Overview

This project aims to build a Machine Learning model that can predict median house prices based on housing and demographic features from the California Housing Dataset.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression modeling
- Hyperparameter tuning
- Model evaluation
- Residual analysis
- Feature importance analysis

---

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

## Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## Final Model Performance

| Model | R² Score | RMSE |
|---|---|---|
| Random Forest (Tuned) | 0.815 | 49,600 |
| XGBoost (Tuned) | 0.827 | 48,026 |

Final selected model:
### Tuned XGBoost Regressor

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

## Project Structure

```bash
├── notebook.ipynb
├── dataset.csv
├── xgboost_house_price_model.pkl
├── Link source
└── README.md
```

---

## Project Goal

Support property companies and real estate agents in making more accurate, objective, and data-driven house pricing decisions.

---

## Key Insights

- Location and median income are the most influential factors in house prices.
- XGBoost achieved the best predictive performance.
- Residual analysis shows balanced prediction behavior.
- Prediction errors increase for houses with extreme prices.

---

## Future Improvements

- Add external datasets such as crime rates and school quality.
- Explore Optuna or Bayesian Optimization.
- Deploy model using Streamlit or Flask.
- Perform periodic model retraining.

