# Predictive Maintainance


The Automated Manufacturing State Prediction project aims to predict the state of an automated manufacturing unit based on data from 25 sensors. The project utilizes advanced predictive techniques and sensor data to optimize machinery functionalities and ensure reliable operations.

The project involved a comprehensive analysis of sensor data, feature engineering techniques, data preprocessing, and model selection. By employing bi-directional LSTM with transpose transformations, an outstanding accuracy of 96.6% was achieved.

The project demonstrates the effectiveness of advanced models in accurately predicting the state of the automated manufacturing unit based on sensor data.

The project was conducted by a team of engineers and data scientists with expertise in machine learning, time series analysis, and manufacturing. The team used a variety of open-source tools and libraries, including Python, NumPy, Pandas, Scikit-learn, Matplotlib, and TensorFlow.

The project was conducted in three phases:

# EDA (Exploratory Data Analysis): 
The team performed extensive exploratory data analysis (EDA) to gain insights into the dataset. The EDA involved visualizing sensor data, identifying trends, and examining the distribution of different states. Correlation plots were generated using libraries such as plotly, seaborn, and matplotlib to understand the interdependencies among sensors and their relationship with the final state.

# Feature Engineering and Data Preprocessing:
To enhance the predictive power of the models, several feature engineering techniques were employed. Seasonality decomposition was performed to extract trends and patterns from the time series data. Transformations like moving average and Naive Bayes were applied to capture relevant information. Additionally, the dataset was transformed by transposing it to create a 10-minute window frame and converting the (10,25)-shaped dataframes to a consolidated (1,250)-shaped dataframe. These preprocessing steps enabled the models to effectively capture temporal dependencies.

# Model Selection and Evaluation: 
Multiple models were considered for the state prediction task, including NaiveForecaster, ARIMA, SARIMA, KNN, KNN with Dynamic Time Wrapping, Temporal Convolutional Network (TCN), SARIMAX, LSTM, and bi-directional LSTM. Extensive literature review was conducted to understand the concepts of time series analysis and time series classification. Each model was trained and evaluated using appropriate metrics to assess its accuracy.


The project was a success, and the team was able to achieve an outstanding accuracy of 96.6% using bi-directional LSTM with transpose transformations. The project demonstrates the effectiveness of advanced models in accurately predicting the state of the automated manufacturing unit based on sensor data.

