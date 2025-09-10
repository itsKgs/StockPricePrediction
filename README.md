# Stock Price Prediction Project

A self-project utilizing **Python**, **Pandas**, **Scikit-learn**, **Statsmodels**, and **PyTorch** for building hybrid forecasting models to predict stock price trends.

---

### Project Status: Ongoing

This project is a work in progress. I am actively building and testing different models and will update the repository with new findings and code.

---

### Key Features

* **Hybrid Forecasting Models**: Combines classical statistical models (ARIMA, SARIMA) with advanced machine learning and deep learning techniques (XGBoost, LSTM) to enhance predictive accuracy.
* **Comprehensive Time Series Analysis**: Includes robust data preprocessing, feature engineering, and a comparative analysis of different forecasting approaches.
* **Performance Evaluation**: Models are evaluated and compared using a suite of metrics, including **RMSE**, **R² score**, **MASE**, and **MAPE**, to ensure a rigorous assessment of forecasting accuracy.

---

### Technologies Used

* **Python**: The core programming language for the project.
* **Pandas**: Used for data manipulation and time series handling.
* **Scikit-learn**: Employed for machine learning models and data preprocessing utilities.
* **Statsmodels**: Utilized for implementing classical statistical time series models like ARIMA.
* **PyTorch**: The deep learning framework for building and training LSTM models.

---

### Methodology

1.  **Data Acquisition**: Historical stock price data is fetched from a reliable source like Yahoo Finance.
2.  **Data Preprocessing**: The raw data is cleaned, normalized, and engineered with relevant features such as moving averages, volatility, and technical indicators.
3.  **Model Development**:
    * **Classical Models**: ARIMA and SARIMA models are trained to capture linear dependencies and seasonality in the time series data.
    * **Machine Learning Models**: XGBoost is used to capture complex, non-linear relationships.
    * **Deep Learning Models**: An LSTM model is designed to recognize long-term dependencies and patterns in the sequential data.
    * **Hybrid Approach**: The project explores combining the predictions of different models to create a more stable and accurate final forecast.
4.  **Model Evaluation**: The performance of each model is rigorously tested on a held-out test set using the specified metrics.

