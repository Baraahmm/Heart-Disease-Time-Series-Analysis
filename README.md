1- Heart Disease Data Analysis & Clustering
This project focuses on performing a comprehensive analysis of heart disease data using unsupervised learning techniques. The goal is to identify underlying patterns and group patients into distinct clusters based on their health metrics, which can be a crucial first step in exploratory data analysis.

Methodology
Data Preprocessing: The project began with loading and cleaning the dataset to ensure its quality for subsequent analysis.

Exploratory Data Analysis (EDA): A Heatmap was used to visualize the correlations between various health attributes, providing key insights into the relationships between different variables.

Dimensionality Reduction: To simplify the dataset and improve model performance, Principal Component Analysis (PCA) was applied. A Scree Plot was then used to determine the optimal number of components to retain.

Patient Clustering: The reduced-dimensionality data was used to perform K-Means Clustering, which groups patients with similar characteristics together.

Key Findings & Results
The project successfully identified distinct patient groups based on multiple health indicators.

The performance of the clustering model was evaluated using the Silhouette Score, a quantitative metric for cluster quality.

****************************************************
2- Time Series Analysis of Heart Disease Data
This project focuses on using time series analysis to identify trends and patterns in heart disease data, specifically focusing on cholesterol levels. The goal is to demonstrate the ability to process, analyze, and forecast time-dependent health data.

Methodology
Data Exploration and Cleaning: Initial analysis of the dataset revealed relationships between variables, as shown in the Heatmap. This step was crucial for understanding the data structure.

Dimensionality Reduction: Principal Component Analysis (PCA) was applied to reduce the complexity of the dataset. A Scree Plot was used to determine the optimal number of components to retain, ensuring that key information was preserved while simplifying the data.

Time Series Modeling: The cholesterol data was first tested for stationarity using the Augmented Dickey-Fuller (ADF) test. The result showed a p-value of 0.000000, confirming the data is stationary and ready for modeling.

ARIMA Model: An ARIMA(1, 0, 1) model was built and trained to forecast future cholesterol values. The model summary showed that its parameters were statistically significant, indicating a reliable fit.

Key Findings & Results
The model successfully generated a forecast for future cholesterol levels.

The model's performance was evaluated using the Root Mean Squared Error (RMSE), which was 51.5443. This metric provides a quantitative measure of the model's predictive accuracy.

