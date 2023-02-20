# **Time series forecasting**
**A simple tutorial**

Time series forecasting is a method used to predict future values based on historical data. It is a crucial tool for businesses, governments, and researchers to plan and make informed decisions. Time series forecasting can be used in various applications, including weather forecasting, financial forecasting, and demand forecasting. It enables organizations to identify trends and patterns, estimate future demand, and plan for future events.

There are several methods for time series forecasting, including statistical methods, machine learning algorithms, and artificial neural networks. Statistical methods, such as exponential smoothing and ARIMA, are widely used to forecast time series data. These methods rely on historical data and mathematical models to predict future values. On the other hand, machine learning algorithms, such as decision trees and random forests, can be used to analyze complex patterns and relationships in the data. These algorithms can handle large volumes of data and can automatically learn and adapt to changing patterns.

Forecasting using machine learning is gaining popularity due to its ability to handle complex and large datasets. Machine learning algorithms, such as neural networks, deep learning, and support vector machines, can identify complex patterns and relationships in the data that are difficult to detect using traditional statistical methods. Machine learning models can analyze multiple factors simultaneously and can handle large datasets with high dimensionality. Moreover, these models can be trained to adapt to changing patterns and make accurate predictions even when faced with noisy and incomplete data.

In this project, we analyze three time series and then, develop different forecasting models for each one. These datasets are: <br>

**Dataset 1:** The monthly data of 'New Privately-Owned Housing Units Started: Total Units' available [here](https://fred.stlouisfed.org/series/HOUSTNSA). <br>
**Dataset 2:** The daily data of `DELI` sales for store number 1 from the 'Store Sales - Time Series Forecasting' on Kaggle website available [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/code?competitionId=29781&sortBy=voteCount) <br>
**Dataset 3:** The daily data of the logarithem of the Bitcoin 'Close' price extracted from the 'Yahoo Finance' repository.

The following figure shows the line graphs of the time series.
![Image](timeseries.png)


The time series are first analuzed in `data_analysis.ipynb`. One-step ahead forecasting models are developed in `forecasting_1stepAhead.ipynb`. 

The sections of `data_analysis.ipynb` are: <br>

1. Quick Look at Data <br>
---- 1.1. Datasets <br>
---- 1.2. Visualizing data <br>
---- 1.3. Checking some statistics <br>
---- 1.4. Train-Test splitting <br>
2. More Visualizations <br>
---- 2.1. Seasonal Plots <br>
---- 2.2. Seasonal Subseries Plots <br>
---- 2.3. Periodogram <br>
---- 2.4. Lag Plots <br>
---- 2.5. Autocorrelation Plots  <br>
3. Time Series Decomposition <br>
4. Classical Decomposition <br>
5. STL Decomposition <br>
---- 5.1. Time Series Decomposition <br>
---- 5.2. Trend and Seasonality Strengths <br>


The sections of `forecasting_1stepAhead.ipynb` are: <br>

0. Importing Datasets <br>
 Defining Some Functions <br>
1. Benchmark Models <br>
2. Linear Regression Method <br>
3. Hybrid Forecasting with Residuals <br>
4. ARIMAX Method <br>
5. Recurrent Neural Networks (RNN) <br>
6. Long Short-Term Memory (LSTM) Networks <br>
----- 6.1. Vanilla LSTM <br>
----- 6.2. Stacked LSTM <br>
----- 6.3. Bidirectional LSTM <br>
7. Gated Recurrent Unit (GRU) <br>


