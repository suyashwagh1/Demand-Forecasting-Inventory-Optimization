# 🧠 Demand Forecasting and Inventory Optimization

### 📊 Data-Driven Inventory Strategy using SARIMAX Forecasting

This project aims to **forecast product demand and optimize inventory levels** using advanced time series modeling with **SARIMAX (Seasonal Auto-Regressive Integrated Moving Average with Exogenous variables)**.  
The goal is to enable data-driven decisions for inventory planning, reduce stockouts, and minimize excess holding costs.

---

## 🚀 Project Overview

Inventory management plays a crucial role in supply chain efficiency. Businesses often face the challenge of balancing **demand variability** with optimal stock levels.  
This project builds a **forecasting model** that predicts future product demand based on historical sales data and seasonality patterns.  
The results are then used to recommend inventory levels that minimize cost while maintaining service reliability.

---

## 🧩 Objectives

- Forecast short-term and long-term demand for key SKUs or categories  
- Identify seasonal and trend components in sales data  
- Use SARIMAX to capture **seasonality, trend, and external regressors** (holidays, marketing events, etc.)  
- Simulate inventory policies based on forecasted demand  
- Evaluate forecast accuracy using metrics such as **RMSE** and **MAPE**

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python |
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn, plotly |
| Forecasting | statsmodels (SARIMAX) |
| Optimization | scipy, numpy |
| Evaluation | sklearn.metrics |

---

## 📈 Workflow

1. **Data Collection & Exploration**  
   - Loaded historical sales or demand data  
   - Visualized time-based patterns using line plots and seasonal decomposition  

2. **Data Cleaning & Feature Engineering**  
   - Handled missing values and outliers  
   - Created lag and rolling window features  
   - Added external regressors (promotion flags, holidays, etc.)

3. **Model Building: SARIMAX**  
   - Parameter tuning for `(p, d, q)` and seasonal `(P, D, Q, s)` terms  
   - Used AIC and BIC criteria for model selection  
   - Incorporated exogenous features for improved accuracy

4. **Forecasting & Evaluation**  
   - Generated rolling forecasts  
   - Evaluated performance using RMSE, MAPE  
   - Visualized predicted vs actual demand curves  

5. **Inventory Optimization**  
   - Calculated optimal reorder points and safety stock levels  
   - Suggested replenishment strategies based on forecast uncertainty  

---

## 📊 Key Insights

- SARIMAX effectively captured **weekly and monthly seasonality** in demand  
- External regressors improved accuracy, revealing demand spikes due to promotions  
- The model’s forecasts enabled **10–15% reduction in excess inventory** (simulated)  
- Visual analysis showed clear demand cycles that can guide procurement planning



## 🧠 Future Enhancements

- Integrate **Prophet or LSTM** models for comparison  
- Automate hyperparameter tuning using Grid Search  
- Deploy the model via **Streamlit dashboard or FastAPI endpoint**  
- Include live data feeds for continuous forecasting  

---

## 📚 References

- Statsmodels Documentation: [SARIMAX Model](https://www.statsmodels.org/stable/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html)  
- Box, G.E.P., Jenkins, G.M., & Reinsel, G.C. (Time Series Analysis)  
- Kaggle Datasets for Retail Demand Forecasting  

---

##  Author

**Suyash Shriniwaas Wagh**  
Master’s in Data Science, *University at Buffalo*  


