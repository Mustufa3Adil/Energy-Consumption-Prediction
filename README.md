# Energy-Consumption-Prediction
A machine learning project for forecasting household energy usage using historical data and time series models (LSTM, Linear Regression). Includes data preprocessing, prediction, optimization suggestions, and result visualization using Python.

# ⚡ Energy Consumption Prediction – Final Year Project

This project presents a machine learning-based system for predicting household energy consumption using historical time series data. It aims to help users better understand, forecast, and optimize their energy usage through data-driven insights and visualization.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Pred_Energy_Consumption.ipynb` | Core notebook for data analysis, model training, and prediction |
| `Pred_Energy_Consumption(part2).ipynb` | Continuation for optimization and visualizations |
| `Energy Consumption Prediction.pptx` | Final presentation slides |
| `Energy Consumption Prediction.docx` | Full academic dissertation including diagrams and testing |
| `Energy Consumption Prediction Data Files.rar` | Dataset and supporting input files |

---

## 🎯 Project Objective

- Predict short-term and long-term energy consumption using machine learning models
- Provide optimization tips based on usage trends
- Help reduce electricity bills and promote efficient energy use
- Visualize energy consumption trends for interpretability

---

## ⚙️ Technologies Used

- **Languages**: Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **ML Libraries**: Scikit-learn, Keras/TensorFlow, XGBoost, statsmodels
- **IDE**: Jupyter Notebook (Google Colab)
- **Tools**: Excel/CSV for input, Graphs & Reports for output

---

## 🧪 Prediction Models Applied

- Linear Regression
- Decision Tree Regression
- LSTM (Long Short-Term Memory)
- XGBoost Regression

---

## 📊 Key Features

- 📥 Upload and preprocess .csv/.xlsx datasets
- 🧠 Forecast future energy consumption (7–30 day window)
- 📈 Visualize usage trends and model predictions
- 💡 Optimization tips for energy saving
- ✅ Validations, test cases, and error handling
- 📃 Reports for consumption history, prediction accuracy, optimization suggestions

---

## 📈 Sample Prediction Output

```python
# Predict next 7 days
model.predict(X_future)

# Plot results
plt.plot(actual_values, label='Actual')
plt.plot(predicted_values, label='Predicted')
plt.legend()
