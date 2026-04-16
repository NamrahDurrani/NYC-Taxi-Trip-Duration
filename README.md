# NYC-Taxi-Trip-Duration
Two ensemble models were trained and evaluated: 
# Random Forest and XGBoost.

# 1. Random Forest Results
| Dataset    | RMSE   | MAE    | R²     |
| ---------- | ------ | ------ | ------ |
| Train      | 161.96 | 95.93  | 0.9201 |
| Validation | 257.21 | 168.22 | 0.7978 |
| Test       | 259.12 | 169.47 | 0.7975 |

# 2. XGBoost Results
| Dataset    | RMSE   | MAE    | R²     |
| ---------- | ------ | ------ | ------ |
| Train      | 253.06 | 166.04 | 0.8048 |
| Validation | 255.48 | 167.65 | 0.8005 |
| Test       | 257.77 | 169.08 | 0.7996 |

# Best Model: XGBoost

XGBoost achieved the best overall performance with:

Highest test R² score (~0.80)
Lower generalization gap between train and test
More stable and reliable predictions
