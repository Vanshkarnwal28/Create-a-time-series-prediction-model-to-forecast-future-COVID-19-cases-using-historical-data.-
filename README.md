🧩 Project Overview
This project aims to forecast future COVID-19 cases using historical data through a time-series prediction model. The model applies Linear Regression, a simple yet effective supervised learning algorithm, to understand and project the trend of COVID-19 confirmed cases, specifically for India.

🎯 Problem Statement
Goal: Predict the number of future COVID-19 cases using historical case data with time-series analysis and regression techniques.

🧠 Methodology
Data Acquisition

Use a .csv file containing global COVID-19 case counts.

Data Preprocessing

Extract India’s case data

Convert dates to datetime format

Handle missing values and set time index

Feature Engineering

Transform time into numerical day indices

Create training and testing datasets

Model Selection: Linear Regression

Chosen for its simplicity and ability to capture trends

Fitted on historical data to learn the trend

Prediction

Predict confirmed cases for 30 days into the future

Evaluation

Use metrics: MAE, MSE, RMSE, R² Score

Visualization

Plot actual vs predicted case counts over time

🧪 Model Used
Algorithm: Linear Regression

Library: scikit-learn

Why?: Fast, interpretable, and suitable as a baseline model

🗂️ File Structure
python
Copy
Edit
📁 covid_case_prediction/
├── dataset.zip                        # Contains global confirmed COVID-19 case data
├── covid_case_prediction.ipynb       # Jupyter notebook with full analysis and model
├── README.md                         # Project overview and documentation
📊 Output & Performance Metrics
Mean Absolute Error (MAE): Low value indicates small average errors

Mean Squared Error (MSE): Penalizes larger errors more

Root Mean Squared Error (RMSE): Interpretable in same units as the target

R² Score: Measures how well predictions match actual trend

📈 Visualization
A time-series line chart compares:

Actual historical cases

Predicted future cases

Train-test split point

🛠️ Requirements
Install required libraries using pip:

bash
Copy
Edit
pip install pandas matplotlib scikit-learn
▶️ How to Run
Upload dataset.zip in Google Colab or your local Jupyter notebook

Run the code blocks in sequence

The model will output:

Predicted values

Evaluation metrics

Time-series plot

📚 References
COVID-19 dataset: Our World in Data

Scikit-learn documentation: https://scikit-learn.org/

Pandas documentation: https://pandas.pydata.org/

📌 Future Work
Improve prediction using advanced models like:

ARIMA / SARIMA

Facebook Prophet

LSTM (Recurrent Neural Networks)

Incorporate additional features (mobility data, vaccination rates, etc.)

Handle multiple waves and seasonality

