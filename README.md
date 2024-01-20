# Estimating a Risk Factor Model for a Stock with Live Data

## About

Welcome to the "Estimating a Risk Factor Model for a Stock with Live Data" repository! 
This project aims to analyze and estimate risk factors influencing the returns of a stock by employing the Carhart Four-Factor Model. 
The primary objective is to understand how specific factors—market risk, size risk, value risk, and momentum risk—contribute to the overall performance of a stock.

## Project Objective

The key goals of this project include:

1. **Risk Factor Analysis:** Investigate the impact of market movements, company size, value stocks, and momentum on the returns of a selected stock.

2. **Carhart Four-Factor Model:** Implement the Carhart model, an extension of the Fama-French three-factor model, to incorporate momentum as an additional factor. This model provides a comprehensive framework for understanding stock returns.

3. **Machine Learning Implementation:** Utilize the Ordinary Least Squares (OLS) regression algorithm to estimate the coefficients of the Carhart Four-Factor Model. OLS helps quantify the relationship between risk factors and stock returns based on historical data.

## Model Overview

This project utilizes the Carhart Four-Factor Model to estimate risk factors for a stock. The Carhart model builds upon the Fama-French three-factor model by incorporating an additional momentum factor. Here's a brief overview of the factors:

1. **Market Risk (Mkt-RF):** Represents the excess return of the market over the risk-free rate. It measures the overall market movement.

2. **Size Risk (SMB):** Stands for Small Minus Big and captures the historical outperformance of small-cap stocks over large-cap stocks.

3. **Value Risk (HML):** Stands for High Minus Low and represents the historical outperformance of value stocks over growth stocks.

4. **Momentum Risk (MOM):** Captures the momentum or speed of price changes in a stock. It is an additional factor introduced by Carhart.

## Machine Learning Algorithm

The machine learning algorithm used for predicting stock returns is the Ordinary Least Squares (OLS) regression. 
OLS is employed to estimate the coefficients of the Carhart Four-Factor Model, providing insights into the relationship between risk factors and stock returns.

## Implementation

The Python code in [`stock_prediction_code.py`](./code/stocks.ipynb) fetches the required financial data, processes it, and applies the Carhart Four-Factor Model using the OLS regression technique.

## Results and Analysis

The project includes visualizations and results obtained from the model. Check the [`/images`](./images/) directory for screenshots or charts illustrating the performance and predictive capabilities of the Carhart model.

## Tech Stack

- **Python:** Programming language used for data processing and analysis.
- **Pandas:** Python library for data manipulation and analysis.
- **Matplotlib:** Python library for creating visualizations.
- **statsmodels:** Python library for estimating and testing statistical models.
- **pandas_datareader:** Python library for fetching financial data.
- **Jupyter Notebooks:** Used for interactive development and data exploration.

## Usage

To run the project locally and see the model in action, follow the instructions in the "Getting Started" section of this README.

## Contributing

If you are interested in contributing to the development or improvement of the model, please refer to [CONTRIBUTING.md](./docs/CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the [Sravani] License - see the [LICENSE.md](./docs/LICENSE.md) file for details.
