# Predictive_Analytics_for_Airline_Fare_Prices

Overview:

This project focuses on predicting the flight fares using various machine learning techniques. The dataset consists of flight information such as airlines, date of journey, source, destination, route, departure and arrival times, duration, total stops, and additional info, along with the price, which is our target variable. Through exploratory data analysis (EDA), feature engineering, feature selection, and model building, we aim to build a model that can accurately predict flight prices based on the given features.

Dataset:

The dataset used in this project includes information about flights in India, including airlines, date of journey, source, destination, route, departure time, arrival time, duration, total stops, additional information, and flight prices.

Features:

The dataset contains the following features:

Airline: The airline operating the flight.
Date_of_Journey: The date of the flight.
Source: The starting point of the flight.
Destination: The endpoint of the flight.
Route: The route taken by the flight.
Dep_Time: Departure time of the flight.
Arrival_Time: Arrival time of the flight.
Duration: Total duration of the flight.
Total_Stops: Total stops between the source and destination.
Additional_Info: Additional information about the flight.
Price: The price of the flight ticket.

Methodology:

Data Preprocessing: Handling missing values, converting data types, and preprocessing date and time features.
Exploratory Data Analysis (EDA): Analyzing the dataset to understand the distribution of various features and their relationship with the flight prices.
Feature Engineering: Creating new features like journey day, month, and derived attributes from the departure and arrival times to help improve model performance.
Feature Selection: Using techniques like mutual information regression to select features that have the most impact on the flight price.
Model Building: Building and training models like RandomForestRegressor and DecisionTreeRegressor. Also, hyperparameter tuning using RandomizedSearchCV to improve model performance.
Evaluation: Evaluating model performance using metrics like R^2 score, MAE, MSE, RMSE, and MAPE.
Deployment: Saving the model using pickle for future predictions on new data.

Tools and Libraries Used:

Data Manipulation and Analysis: Pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn
Model Persistence: Pickle

Results:

The RandomForestRegressor model with hyperparameter tuning showed promising results in predicting flight fares with a good R^2 score.

Future Work:

Experimenting with more advanced machine learning models and ensemble techniques.
Incorporating more features that may affect flight prices, such as weather conditions, festival times, etc.
Deploying the model as a web application to make flight fare predictions accessible to users.
