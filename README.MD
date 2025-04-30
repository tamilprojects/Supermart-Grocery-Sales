
# Supermart Grocery Sales Analysis

## Overview

This project analyzes and forecasts sales data from Supermart Grocery using exploratory data analysis (EDA) and time series forecasting techniques. The analysis provides insights into sales trends, customer behavior, and the impact of discounts on sales and profit. Additionally, the project uses Facebook's Prophet model to predict future sales trends.

## Features

- Exploratory Data Analysis (EDA) of grocery sales data
- Aggregated analysis by categories, cities, and customers
- Visualization of sales trends, patterns, and correlations
- RFM (Recency, Frequency, Monetary) analysis for customer segmentation
- Time series forecasting using Facebook Prophet
- Insights into sales seasonality and trends

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Facebook Prophet for time series forecasting
- Jupyter Notebook for interactive analysis

## Project Structure

1. **Data Loading and Preprocessing**

   - Load the dataset and clean the data (e.g., handle missing values, format columns).
   - Extract date-related features like year, month, and day.
2. **Exploratory Data Analysis (EDA)**

   - Analyze sales trends by categories, cities, and customers.
   - Visualize correlations between sales, profit, and discounts.
   - Identify top-performing products, cities, and customers.
3. **RFM Analysis**

   - Segment customers based on Recency, Frequency, and Monetary metrics.
   - Identify "best customers" and other customer segments.
4. **Time Series Analysis**

   - Analyze monthly and yearly sales trends.
   - Forecast future sales using Facebook Prophet.
5. **Visualization**

   - Generate plots for sales trends, correlations, and forecast components.

## Results

- **Sales Trends**: Sales are higher during September and December, while January and February show lower sales.
- **Top Performers**: Eggs, Meat, Fish, and Snacks are the top-selling products. Kanyakumari is the top-performing city.
- **Customer Insights**: RFM analysis identified key customer segments, including the "best customers."
- **Forecasting**: Monthly sales forecasts for the next 12 months were generated using Prophet, showing an increasing trend.

## Getting Started

1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn prophet
   ```
