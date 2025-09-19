Time Series Analysis of Heart Disease Data
This project focuses on using time series analysis to identify trends and patterns in heart disease data, specifically focusing on cholesterol levels. The goal is to demonstrate the ability to process, analyze, and forecast time-dependent health data.

Methodology
Data Exploration and Cleaning: Initial analysis of the dataset revealed relationships between variables, as shown in the Heatmap. This step was crucial for understanding the data structure.

Dimensionality Reduction: Principal Component Analysis (PCA) was applied to reduce the complexity of the dataset. A Scree Plot was used to determine the optimal number of components to retain, ensuring that key information was preserved while simplifying the data.

Time Series Modeling: The cholesterol data was first tested for stationarity using the Augmented Dickey-Fuller (ADF) test. The result showed a p-value of 0.000000, confirming the data is stationary and ready for modeling.

ARIMA Model: An ARIMA(1, 0, 1) model was built and trained to forecast future cholesterol values. The model summary showed that its parameters were statistically significant, indicating a reliable fit.

Key Findings & Results
The model successfully generated a forecast for future cholesterol levels.

The model's performance was evaluated using the Root Mean Squared Error (RMSE), which was 51.5443. This metric provides a quantitative measure of the model's predictive accuracy.

