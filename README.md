Project Overview
This project focuses on predicting the future closing prices of a stock index (e.g., Dow Jones Industrial Average - ^DJI) using an LSTM-based deep learning model. The system performs end-to-end operations — from historical data preprocessing, model training, and future price prediction to performance evaluation and visualization.

Features
Data cleaning and preprocessing
Time series visualization of actual historical data
LSTM-based forecasting model
Generation of future predictions (both actual and noisy versions)
Error evaluation using MAE, RMSE, and MAPE
Interactive comparison of actual and forecasted data
Expandable framework for different stock indices


Project Structure

├── Forecasting.ipynb # Evaluating results and creating interactive plots
├── README.md                    # Project overview and instructions
└── requirements.txt             # List of required Python libraries

Technologies Used
Python 3.x
Pandas
NumPy
Scikit-learn
Keras / TensorFlow
Plotly (for interactive graphs)


How to Run the Project
Clone the repository:
[https://github.com/Debarjya17/llm-based-stock-prediction/edit/main/README.md](https://github.com/Debarjya17/llm-based-stock-prediction)

Install the required libraries:
pip install -r requirements.txtOpen the Jupyter notebooks and execute the code sequentially

📊 Results
The LSTM model was able to forecast stock prices for 6 months into the future.

Random noise simulation provided a more realistic view of possible market fluctuations.

The evaluation metrics (MAE, RMSE, and MAPE) demonstrated good model performance.

🎯 Objectives
To forecast future stock prices based on historical data.

To evaluate prediction accuracy using quantitative error metrics.

To create a robust, expandable stock price prediction framework.

🧠 Contributions
Built a complete LSTM prediction pipeline.

Added random noise to simulate real-world prediction scenarios.

Performed comprehensive evaluation and visualization.

Designed a flexible structure for future research or enhancements.
