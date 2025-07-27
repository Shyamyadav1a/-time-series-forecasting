# 📦 Supply Chain Demand Forecasting using XGBoost

This project predicts product sales using machine learning (XGBoost) based on historical sales, calendar events, holidays, and pricing data.

---

## 📁 Project Files

| File                         | Description                            |
|------------------------------|----------------------------------------|
| `usinghypertuning.ipynb`     | Jupyter Notebook with model + visualizations |
| `calendar.csv`               | Calendar dates with event data         |
| `holidays.csv`               | List of holidays used in feature engineering |
| `sales_train_validation.csv` | Historical product sales               |
| `sell_prices.csv`            | Product selling prices                 |
| `xgb_forecast_results.csv`   | Final forecasted sales (model output)  |

---

## 🧠 Model Summary

- **Algorithm:** XGBoost Regressor
- **Features:** Lag values, rolling means, holidays, event flags
- **Evaluation Metrics:** MAE, RMSE, MAPE, R²

---

## 📈 Visualizations

- Actual vs Predicted Sales Plot  
- Real-time forecast line chart  


---

## 🚀 How to Run

### 📌 Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn xgboost
