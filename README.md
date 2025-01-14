# Forecasting Surface Air Temperature in the Philippines Using Meta-Modeling of Time Series and Neural Network Approaches with Climate Scenario Validation

### Overview  
In this study I investigated surface air temperature trends in the Philippines (1901–2100) through statistical and machine learning methods. Combining ARIMA, SARIMA, and Long Short-Term Memory (LSTM) models, a meta-model integrates their strengths for enhanced forecasting accuracy. I validated the findings against Shared Socioeconomic Pathway (SSP) climate scenarios to ensure reliability.

### Key Objectives  
1. Forecast temperature trends using statistical (ARIMA, SARIMA) and deep learning (LSTM) models.  
2. Develop a meta-model combining SARIMA and LSTM via linear regression stacking.  
3. Validate predictions against SSP climate scenarios.  

### Methods  
- **Data Source**: Climate Knowledge Portal, World Bank.  
- **Techniques**: Differencing for stationarity, time series decomposition, Building Time Series models such as ARIMA and SARIMA, Building RNN-LSTM model, stacking meta-modeling.  
- **Validation**: SSP scenarios (low to high emissions) for future climate alignment.

### Results  
- **Meta-Model Performance**:  
  - MSE: 0.03  
  - RMSE: 0.20  
  - MAPE: 0.46%  
  - R²: 0.55  
- **Comparison**: Outperformed individual SARIMA and LSTM models, aligning closely with SSP2-4.5 pathways.  

### Key Takeaways  
- **Strengths**: Combines statistical and machine learning techniques for robust forecasting.  
- **Limitations**: Lack of high-resolution data (e.g., seasonal variations) and additional predictors (e.g., humidity).  

### Additional Reading  
For a detailed explanation of this study, read the article:  
[Advanced Climate Forecasting of Philippine Surface Air Temperatures Through the Year 2100 Using Meta-Modeling Approaches](https://medium.com/@abraham.prosia0707/advanced-climate-forecasting-of-philippine-surface-air-temperatures-through-the-year-2100-using-9a0335c6bb77).

### Citation  
**Author**: Abraham Prosia  

