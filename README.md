# 🧠💡 Smart Investing: Forecasting Samsung's Market

#### Introduction
Samsung Electronics Co., Ltd. is a major subsidiary of the Samsung Group and a global leader in technology and consumer electronics. Since its inception in 1938, Samsung has grown from a trading company into a multifaceted conglomerate. Samsung Electronics, established in 1969, has become one of the world’s largest manufacturers of smartphones, semiconductors, and electronic devices. This report details the analysis and forecasting of Samsung Electronics' stock prices using historical data since 2000.

#### Data Overview
The dataset comprises records of Samsung Electronics' stock price changes from 2000 onwards, featuring columns such as date, opening price, highest price of the day, lowest price of the day, closing price, adjusted closing price, and trading volume. With 6127 entries, this comprehensive dataset is instrumental in understanding long-term market trends and performing detailed analyses.

#### Data Preparation
The initial step in the analysis involved loading the dataset and preparing the data for analysis. This included:
- Converting the 'Date' column to a datetime format.
- Checking for and handling any missing values to ensure the dataset's completeness and accuracy.

#### Exploratory Data Analysis (EDA)
EDA was conducted to understand the basic characteristics of the data and identify any underlying patterns or anomalies. Key steps included:
- Generating summary statistics to provide an overview of the data distribution.
- Visualizing the closing price over time to identify trends, seasonal patterns, and significant fluctuations.

#### Feature Engineering
To enhance the dataset for modeling, additional features were engineered. This involved calculating moving averages, such as the 50-day and 200-day moving averages, which are common technical indicators used in stock market analysis. These features help smooth out short-term fluctuations and highlight longer-term trends.

#### Modeling
For the purpose of forecasting, two primary models were considered:

1. **ARIMA (AutoRegressive Integrated Moving Average) Model:**
   - The dataset was split into training and testing sets to evaluate the model’s performance.
   - The ARIMA model was fitted on the training data, and forecasts were generated for the testing period.
   - This model is widely used for time series forecasting due to its ability to handle various time series patterns.

2. **Prophet Model:**
   - Developed by Facebook, the Prophet model is designed for forecasting time series data that exhibit strong seasonal effects and several seasons of historical data.
   - The Prophet model was trained on the historical stock prices and used to predict future values.
   - The model's flexibility in handling missing data and outliers makes it suitable for financial time series forecasting.

#### Evaluation
The performance of the forecasting models was evaluated using appropriate metrics, such as Mean Squared Error (MSE), to quantify the accuracy of the predictions. Visualizations comparing the actual stock prices with the forecasted values provided insights into the models’ effectiveness.

#### Forecasting
Future stock prices were forecasted using the trained models. The results were visualized to provide a clear picture of the expected stock price trends. The Prophet model, in particular, allowed for plotting forecast components such as trend, weekly seasonality, and yearly seasonality, offering a detailed understanding of the factors influencing the stock prices.

#### Conclusion
This analysis and forecasting of Samsung Electronics' stock prices provided valuable insights into historical trends and future projections. The use of advanced time series models like ARIMA and Prophet demonstrated robust methodologies for financial forecasting. These models can aid investors and analysts in making informed decisions based on historical data and anticipated market movements. The comprehensive approach, from data preparation to model evaluation, ensures a thorough understanding and reliable forecasting of stock prices.

Dataset Link: https://www.kaggle.com/datasets/mayankanand2701/samsung-stock-price-dataset
