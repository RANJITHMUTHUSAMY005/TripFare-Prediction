TripFare-Predicting-Urban-Taxi-Fare-with-Machine-Learning
This project is basically about predicting total taxi fare based on the data provided.

Skills Developed

Exploratory Data Analysis (EDA)
Data Cleaning and Preprocessing
Data Visualization with Matplotlib & Seaborn
Feature Engineering
Regression Model Building and Evaluation
Hyperparameter Tuning
Deployment with Streamlit
Problem Statement As a Data Analyst at an urban mobility analytics firm, your task is to analyze historical taxi trip records and build a predictive model to estimate total taxi fare amounts. The model will help passengers get accurate fare estimates before booking and support urban mobility analytics.

Dataset The dataset contains historical taxi trip records from a metropolitan transportation network. It includes features such as pickup and dropoff locations, trip distance, duration, time of travel, rate codes, payment types, and fare amounts.

Data Collection Download and load the dataset using Pandas.

Data Understanding
Explore dataset shape, data types, missing values, duplicates, and general statistics.

Feature Engineering

Calculate trip_distance using the Haversine formula.
Extract time-based features like pickup_day, am_pm, and is_night.
Convert pickup datetime from UTC to local time (e.g., EDT).
Create binary and categorical indicators for better model insights.
Exploratory Data Analysis (EDA)
Analyze relationships such as:

Fare vs. Distance
Fare vs. Passenger Count
Time-of-day and weekday/weekend fare variations
Outlier detection and handling
Data Transformation

Handle outliers using Z-score .
Fix skewness in continuous variables.
Encode categorical variables using OneHotEncoder and LabelEncoder.
Feature Selection

Use correlation analysis.
Extract feature importance from models like Random Forest.
Model Building
Train multiple regression models including:

Linear Regression
Ridge and Lasso Regression
Random Forest Regressor
XGB Regressor
Hyperparameter Tuning
Optimize the best-performing model with RandomizedSearchCV.

Model Deployment
Save the best model and encoders. Build a Streamlit app to interactively predict taxi fares based on user inputs.
