# Sales Prediction with Random Forest

A regression project that explores sales prediction from historical business data using a Random Forest model.

## Objective

Prepare sales data, engineer predictive features, train a regression model, and evaluate how well historical information can explain sales variation.

## Workflow

1. Data loading
2. Data cleaning
3. Missing-value handling
4. Feature preparation
5. One-hot encoding
6. Train-test split
7. Random Forest training
8. Regression evaluation
9. Business interpretation

## Model

**Random Forest Regressor**

## Reported Results

| Metric | Value |
|---|---:|
| MAE | **221.52** |
| MSE | **509,625.58** |
| RMSE | **713.88** |
| R² | **0.2375** |

The relatively low R² indicates that the current feature set and model explain only part of the variation in sales. This is useful evidence that stronger features, time-aware validation, or different modeling approaches may be required.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Skills Demonstrated

- Regression
- Data preparation
- Feature encoding
- Random Forest
- Model evaluation
- Interpreting imperfect model performance

## Important Limitation

This repository is better described as a **sales prediction baseline** than a complete forecasting system unless the evaluation explicitly preserves temporal order. Traditional random train-test splitting can overstate forecasting performance on time-dependent data.

## Future Improvements

- Use chronological validation
- Add lag and rolling-window features
- Compare Gradient Boosting / XGBoost
- Evaluate seasonality and trends
- Compare with dedicated time-series methods
- Perform hyperparameter optimization

---

**Author:** Manan Paliwal  
B.Tech Computer Science Engineering — Artificial Intelligence & Machine Learning