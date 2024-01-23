# Project Name
Gold Stocks Prices Data
## Table of Contents

- [Description](#description)
- [Tasks](#tasks)
- [Database Overview](#database-overview)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

This data set provides a comprehensive record of daily gold prices from January 19, 2014 to January 22, 2024. The data is provided by Nasdaq and includes key financial metrics for each trading day. . The dataset consists of the following columns:
## Tasks

The project involves the following tasks:
### Easy
1. [Task 1](#task-1): Basic Statistics: List basic descriptive statistics for the "Close" column (mean, median, standard deviation).
2. [Task 2](#task-2): Number of unique dates: Check how many unique dates there are in your dataset
3. [Task 3](#task-3): Closes Histogram: Create a closes histogram ("Close" column) using Matplotlib
4. [Task 4](#task-4): Daily Price Change: Add a new "Daily Change" column, representing the daily price change (the difference between "Close" and "Open").
5. [Task 5](#task-5): Average Volume Value: Calculate the average volume value.
### Medium
1. [Task 1](#task-1): Average Monthly Closing Price: Calculate the average closing price for each month.
2. [Task 2](#task-2): Compare opening and closing prices: Create a line chart comparing the opening and closing prices for each date.
3. [Task 3](#task-3): Correlation: Check the correlation between "High" and "Low" using Pandas.
4. [Task 4](#task-4): Average closing price for a given year: Calculate the average closing price for each year.
5. [Task 5](#task-5): Volume over time: Create a line chart showing volume changes over time.
### Hard
1. [Task 1](#task-1): Cumulative Daily Rate of Return: Calculate the cumulative daily rate of return at close and graph it.
2. [Task 2](#task-2): Moving Average: Create a chart with a 50-day moving average of closing prices.
3. [Task 3](#task-3): Cluster analysis: Apply a clustering algorithm (e.g. KMeans) to closing prices, then graph the results.
4. [Task 4](#task-4): Daily Change Histogram: Create a histogram of daily price changes (use the "Daily Change" column).
5. [Task 5](#task-5): Price Forecasting: Use linear regression to forecast closing prices based on other columns (e.g. open, high price, volume) and graph the results.

### Librares to Use 
### Pandas, Matplotlib, Seaborn, Numpy
Pandas: Tasks 1, 2, 4, 6, 8, 9, 11, 13, 14.

Matplotlib: Problems 3, 7, 10, 12, 15.

Seaborn: No quest, but Seaborn can be used to improve charts.

Numpy: Problems 5, 12, 14 (for statistical calculations and data manipulation).

## Database Overview
Data is clean and ready to use.
Date: object dt
Other: float64 
### Example:

Date: A unique date for each trading day recorded. 
Close: The closing price of gold on the relevant date.
Volume: Gold trading volume on the relevant date.
Open: The opening price of gold on the relevant date.
High: The highest recorded price of gold during the trading day.
Low: The lowest price recorded for gold in the trading day.

## Getting Started

Open in Google Colaboratory and in File option use Copy to... ( your choice )

## Usage

Need to import some libs like:
### Basic:
``import pandas as pd``

``import numpy as np``

``import matplotlib.pyplot as plt``

``import seaborn as sns``

### Advanced: 
`` from sklearn.cluster import KMeans ``

`` from sklearn.preprocessing import StandardScaler ``

`` from sklearn.model_selection import train_test_split ``

`` from sklearn.linear_model import LinearRegression ``

`` from sklearn.metrics import mean_squared_error ``

## Contributing

Comments, Forks, Pull Request etc

## License

Apache 2.0
