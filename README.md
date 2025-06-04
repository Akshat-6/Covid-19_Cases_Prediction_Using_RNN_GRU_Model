# Covid-19_Cases_Prediction_Using_RNN_GRU_Model
Time series forecasting of COVID-19 cases in India using RNN-GRU models on real-time data from Kaggle.

🦠 COVID-19 India Case Forecasting with Deep Learning
This project analyzes and forecasts COVID-19 cases in India using Recurrent Neural Networks (RNN), specifically the Gated Recurrent Unit (GRU) model. The analysis is based on real-world time series data from Kaggle.

📂 Dataset

📌 Source: COVID-19 India Dataset - Kaggle
https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset

Contains:

Daily reported COVID cases

State-wise breakdown

Recovered, deceased, confirmed case data

Dates and cumulative data

📊 Project Workflow

Data Loading & Preprocessing

Handled missing/null values

Formatted date columns

Feature selection

EDA (Exploratory Data Analysis)

Trends over time (Confirmed/Recovered/Deceased)

State-wise comparison

Moving averages and visual patterns

Data Transformation

Normalization for neural network training

Time series windowing (look-back creation)

Modeling with RNN-GRU

Built deep learning model using GRU layers

Trained on past COVID-19 trends

Forecasted future cases

Visualization

Predicted vs Actual

Loss curves

Forecast graphs

🛠️ Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

TensorFlow / Keras

GRU (Gated Recurrent Unit)

Sklearn (for scaling and evaluation)

💡 Key Learnings

Practical application of GRU for time series forecasting

Understanding COVID trends using visual EDA

Challenges of epidemic modeling using real-world data


📈 Sample Output

Accurate short-term prediction of COVID-19 confirmed cases

Visualization of training vs prediction

GRU model capturing time-based sequential patterns
