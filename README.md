# Stock Predictor - Jupyter Notebook

## Overview
This project is a Stock Predictor developed in Python using Jupyter Notebook. The goal is to analyze and predict stock prices using historical data and machine learning techniques. The project leverages various data science libraries to preprocess data, train models, and visualize results.

## Features
- **Data Extraction:** Fetches historical stock data using the yFinance API, focusing on major companies like NVIDIA.
- **Data Preprocessing:** Includes feature selection, scaling, and transformation of stock price data for model training.
- **Visualization:** Utilizes Matplotlib and Seaborn to create insightful visualizations of stock trends and model predictions.
- **Modeling:** Implements machine learning algorithms, possibly using PyTorch, to predict future stock prices based on historical data.
- **Error Analysis:** Evaluates the model’s performance using metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Development
- **Python**: The programming language used to implement the data extraction, preprocessing, and modeling.
- **Jupyter Notebook**: An interactive environment that allows for code execution and visualization.
- **NumPy & Pandas**: Libraries used for data manipulation and management, particularly for handling time-series stock data.
- **Matplotlib & Seaborn**: Visualization libraries that create plots for data analysis and model predictions.
- **Scikit-learn**: Used for data preprocessing tasks such as scaling, and for evaluating the model's predictive performance.
- **PyTorch**: A deep learning library potentially used for implementing advanced machine learning models.
- **yFinance**: A Python library used to fetch historical stock data from Yahoo Finance.

## How It Works
1. **Data Collection:** Historical stock data is downloaded using the yFinance API.
2. **Preprocessing:** The data is cleaned, scaled, and prepared for training machine learning models.
3. **Model Training:** Machine learning models are trained using PyTorch or other algorithms to predict future stock prices.
4. **Visualization:** The results and trends are visualized using Matplotlib and Seaborn to provide insights into the stock market.
5. **Performance Evaluation:** The model's accuracy is measured using metrics such as MAE and MSE.
