#  **Zillow Sales Trend Analysis**


## **Project Overview**

This project focuses on analyzing Zillow sales data from 2018 to February 2024 to uncover underlying trends and make future predictions for the U.S. housing market. By applying advanced analytical methods such as ARIMA, K-Nearest Neighbors (KNN) Regressor, and Convolutional Neural Network (CNN) models, this project offers insights into the factors influencing housing value trends and provides data-driven recommendations for real estate stakeholders.

## **Data Sources**

- **Zillow Sales Data**:
- Obtained from the official Zillow platform, including property trends, market insights, and historical sales data from 2018 to February 2024.

## **Key Objectives**

1. **Identify key factors influencing housing value trends** over time.
   
2. **Develop accurate forecasts** for future movements in the housing market.
   
3. **Provide actionable insights** for real estate investors, homeowners, and other stakeholders to navigate the real estate landscape effectively.

## **Analysis Overview**

### **1. Data Preparation and Cleaning**

- **Data Acquisition**: Zillow sales data was obtained from Zillow’s official website, focusing on property trends and sales insights.
  
- **Data Cleaning**: The dataset was cleaned to address missing values and ensure accuracy. A temporal focus was applied, limiting the analysis to data from 2018 to February 2024 to enhance the relevance of insights.

### **2. Time Series Analysis**
- **Techniques**: Time series analysis was conducted using ARIMA and KNN Regressor models to forecast future housing market trends.
- **Insights**: The analysis identified significant trends and seasonal patterns in Zillow sales data, providing a solid foundation for forecasting future housing values.

## **Exploratory Data Analysis (EDA)**
- **Trends in House Values (2018-2023)**: Identified a gradual increase in house values until 2019, followed by a period of stability and slight decline until 2023, providing a basis for forecasting future market trends.
- **Top 10 States by Total Sales Prices (2018-2023)**: Analyzed the top-performing states, with California holding the highest sales prices, followed by other key states like New York and Texas.
- **New York Region Sales Data**: Highlighted New York City as a dominant player in the real estate market, driven by high demand and diverse housing options.

## **Methods**

### **1. ARIMA Model**

- Applied the ARIMA model for time series forecasting on Zillow sales data, assessing the stationarity of the data using the Augmented Dickey-Fuller (ADF) test.
- **Insights**: The model successfully identified consistent trends in housing prices over time, making it suitable for predictive analysis.

### **2. K-Nearest Neighbors (KNN) Regressor**

- Developed a KNN Regressor model to predict housing prices based on historical data.
  
- **Model Evaluation**:
Performance was evaluated using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with an MAE of 6.56 and RMSE of 10.04, indicating good predictive accuracy.

### **3. Convolutional Neural Network (CNN)**

- Implemented a CNN model using Keras to conduct time series forecasting for 2023 and 2024.
  
- **Results**: The CNN model achieved an accuracy of 99.09% on the test dataset, providing highly accurate predictions for future housing trends.

## **Conclusion and Future Scope**

This project provides valuable insights into the dynamics of the U.S. housing market, offering stakeholders critical guidance for investment decisions. The analysis demonstrates the utility of advanced forecasting techniques in real estate market analysis. Future work could focus on expanding the analysis to include more granular data and applying other advanced machine learning models for improved predictions.
