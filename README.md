# Asian Paints Stock Price Prediction (2021–2023)

A machine learning and deep learning-based system to forecast Asian Paints stock prices using historical data from 2021 to 2023. This project compares traditional ML algorithms (Decision Tree, Random Forest) with advanced deep learning models (LSTM) and provides interactive dashboards for financial data visualization.

## 🚀 Project Overview

This project aims to predict the future stock prices of Asian Paints by leveraging both classic machine learning algorithms and state-of-the-art deep learning techniques. By analyzing historical stock data, the system helps investors and analysts make informed decisions. The project also features interactive dashboards for visualizing predictions and trends.

## 📈 Features

- *Data Collection & Preprocessing:*  
  Acquired and cleaned Asian Paints stock data (2021–2023) from financial APIs/CSV sources.
- *Exploratory Data Analysis:*  
  Visualized trends, moving averages, and seasonality using Pandas, Matplotlib, and Seaborn.
- *Model Building:*  
  - *Decision Tree & Random Forest:* For baseline regression and feature importance.
  - *LSTM Neural Network:* For capturing temporal dependencies and achieving high accuracy in time-series forecasting.
- *Model Evaluation:*  
  Compared models using RMSE and accuracy metrics.
- *Interactive Dashboards:*  
  Built with Plotly and Dash for dynamic visualization of stock trends and predictions.
- *Deployment:*  
  Flask-based web app for easy user access.

## 🗂 Dataset

- *Source:* [NSE/BSE APIs, Yahoo Finance, or CSV files]
- *Period:* January 2021 – December 2023
- *Features:* Date, Open, High, Low, Close, Volume, etc.

## 🛠 Installation

1. *Clone this repository:*
   bash
   git clone https://github.com/Balaji-2001/asian-paints-stock-prediction.git
   cd asian-paints-stock-prediction
   

2. *Install dependencies:*
   bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras plotly dash flask
   

3. *Download and place the stock data CSV in the project directory.*

## 🏃 Usage

### 1. *Train and Evaluate Models*
   bash
   python train_models.py
   
   - Trains Decision Tree, Random Forest, and LSTM models.
   - Outputs accuracy and RMSE for each model.

### 2. *Launch Interactive Dashboard*
   bash
   python dashboard.py
   
   - Opens a Plotly/Dash dashboard to visualize predictions.

### 3. *Run the Web App*
   bash
   python app.py
   
   - Launches a Flask app for user-friendly prediction interface.

## 🧠 Model Architecture

- *Decision Tree & Random Forest:* Standard scikit-learn regressors for baseline and feature analysis.
- *LSTM:*  
  - Input: Windowed time-series data  
  - Layers: LSTM → Dense  
  - Output: Next-day price prediction

## 📊 Results

- *LSTM achieved up to 92% prediction accuracy* on test data.
- Random Forest and Decision Tree provided useful baselines and feature insights.
- Interactive dashboards enabled clear visualization of trends and model performance.

## 🖥 Technologies Used

- *Languages:* Python
- *Libraries:* Pandas, NumPy, scikit-learn, TensorFlow, Keras, Matplotlib, Seaborn, Plotly, Dash, Flask

## 🙏 Credits

- Data: Yahoo Finance / NSE / BSE
- Developed by [Balaji V](https://github.com/Balaji-2001)

*Feel free to fork, contribute, or use this project for learning and research!*

Let me know if you want to include code snippets, sample plots, or further customization!
