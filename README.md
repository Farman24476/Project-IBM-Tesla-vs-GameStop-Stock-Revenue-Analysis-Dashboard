# Tesla-vs-GameStop-Stock-Revenue-Analysis-Dashboard

This project showcases a simple yet effective workflow for retrieving, analyzing, and visualizing historical stock price data and quarterly revenue figures for two publicly traded companies—**Tesla (TSLA)** and **GameStop (GME)**. The project uses Python libraries like `yfinance`, `pandas`, and `matplotlib` to create time-series plots and explore financial trends. This structure serves as a foundation for building more advanced, interactive financial dashboards.

---

## Project Objectives

- Collect long-term stock price data from Yahoo Finance using the `yfinance` API
- Integrate quarterly revenue data into structured financial time series
- Visualize company performance trends through clear and informative plots
- Provide a baseline framework for extending into a dashboard-based interface

---

## Features

- Fetches complete historical stock price data (`Open`, `High`, `Low`, `Close`, `Volume`)  
- Adds custom quarterly revenue data as a complementary financial metric  
- Generates line plots of stock price movement over time  
- Demonstrates how to combine third-party APIs with structured business data  
- Serves as a reusable pattern for analyzing any public company stock

---

## Tools and Libraries

- **Python 3.x**
- [yfinance](https://pypi.org/project/yfinance/): for downloading stock data
- [pandas](https://pandas.pydata.org/): for data manipulation and transformation
- [matplotlib](https://matplotlib.org/): for time-series visualization

---

## Getting Started

To run the project on your local machine:

### 1. Install Dependencies

```bash
pip install yfinance pandas matplotlib
