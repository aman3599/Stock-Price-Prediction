# Stock Price Prediction using Linear Regression

This project implements stock price prediction using linear regression techniques. The model predicts stock prices based on features like open, high, and low prices using historical stock data.

## Project Overview

The notebook demonstrates the following steps:
1. **Data Collection**: Stock data for Facebook (META) is fetched using the `yfinance` library, covering multiple years.
2. **Data Preprocessing**: The data is cleaned by removing unnecessary columns such as 'Dividends' and 'Volume'.
3. **Linear Regression Model**: 
   - **Normal Equation**: Used to compute the optimal weights (coefficients) for the linear model.
   - **Gradient Descent**: A method to iteratively find the optimal weights by minimizing the cost function.
4. **Model Training**: The model is trained using both the normal equation and gradient descent.
5. **Model Evaluation**: The performance is evaluated based on the Mean Squared Error (MSE).

## Files

1. **`code.ipynb`**: The main Jupyter notebook containing the code for the stock price prediction model, including data collection, preprocessing, model training, and evaluation.

## Setup

To run this project, you need the following Python libraries:
- `yfinance`
- `pandas`
- `numpy`
- `sklearn`
- `matplotlib`

You can install them via pip:

```bash
pip install yfinance pandas numpy scikit-learn matplotlib
