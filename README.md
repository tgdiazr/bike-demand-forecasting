# bike-demand-forecasting

🚲 Bike Rental Demand Forecasting
This project aims to develop a robust machine learning pipeline to predict hourly bike rental demand using historical data. By leveraging weather, seasonality, and time-based features, 
we train and evaluate models capable of forecasting short-term demand — critical for operations and capacity planning.

🔍 Project Overview
Objective: Forecast hourly bike rental counts using historical data.

Tools: Python, Google Colab, scikit-learn, pandas, matplotlib

Models Used: Random Forest Regressor

Focus: Time series modeling, feature engineering, model evaluation, and visualization.

📦 Dataset
The data comes from the Bike Sharing Demand competition on Kaggle:

train.csv: Historical hourly data including weather and rental counts.

test.csv: Data for prediction (no rental counts).

sampleSubmission.csv: Format for predictions.

Key Fields:
datetime: Timestamp (hourly granularity)

season, holiday, workingday, weather: Categorical context features

temp, atemp, humidity, windspeed: Environmental variables

casual, registered, count: Target variables (only in train)

📈 Visualizations
Time Series Plot: Rental counts over time to identify patterns and seasonality.

Actual vs Predicted Plot: Visual comparison of model performance on validation data.

🛠 Key Features
Feature engineering with date/time decomposition (hour, day, month, weekday)

Model training and validation using Random Forest

Visualization of prediction accuracy

Ready-to-run in Google Colab

💡 Business Relevance
This project simulates real-world forecasting problems similar to capacity planning at Amazon. Accurate short-term demand forecasting helps:

Optimize staffing and inventory

Improve customer experience

Reduce overcapacity costs

🚀 How to Run
Clone the repo or open notebook in Google Colab

Upload the train.csv file

Run all cells to train and visualize

📚 Skills Demonstrated
Time Series Forecasting

Machine Learning Modeling

Python Data Wrangling

Data Visualization

Business-Oriented Problem Solving
