🌦️ Weather Data Analyzer

This project processes historical weather data to identify climate trends and visualize key metrics such as temperature, humidity, and rainfall. It also forecasts future temperature trends using Linear Regression.

 Analyze past climate data & forecast future temperature trends using Python, Matplotlib, and Scikit-learn.

💻 Features

 Line Chart – Visualize temperature trends over the years

 Bar Chart – Show total annual rainfall

 Scatter Plot – Explore relationship between temperature and humidity

 Forecasting – Predict future temperature using Linear Regression

 Model Evaluation – MSE & RMSE metrics for model accuracy

Plots are created using Matplotlib and Seaborn.

🧠 Predictive Modeling

Model Used: Linear Regression (sklearn.linear_model)

Target Variable: Temperature

Features Used: Year

Evaluation Metrics:

MSE: 27.24
RMSE: 5.22

🚀 Getting Started

Prerequisites

Install required libraries:

pip install -r requirements.txt

How to Run

Using Jupyter Notebook:

jupyter notebook notebooks/weather_analysis.ipynb

Using Python Script:

python main.py

Make sure dataset.csv is placed inside the data

🧩 Future Enhancements

Seasonal & monthly trend analysis

Incorporate additional weather metrics (e.g., wind speed, pressure)

Use advanced models (Random Forest, LSTM)

Build an interactive web dashboard using Plotly Dash 
