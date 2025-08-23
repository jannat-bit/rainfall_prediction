🌧️ Rainfall Prediction Project
📌 Overview
This project predicts precipitation levels (rainfall in inches) using the Austin Weather dataset.
The dataset contains daily weather information such as temperature, humidity, dew point, visibility, wind speed, and pressure.
The goal is to:
Clean and preprocess real-world weather data
Apply Linear Regression using scikit-learn
Visualize precipitation trends and correlations with other weather attributes
📊 Dataset
File: austin_weather.csv
Rows: 1319
Columns: 21 (temperature, humidity, dew point, visibility, wind speed, precipitation, etc.)
Precipitation values include 0, numeric inches, and "T" (trace amount).
🔎 Key Steps in the Project
Load Dataset → Read CSV file into Pandas DataFrame
Data Cleaning → Handle "T" values, missing values, and convert datatypes
EDA (Exploratory Data Analysis) → Heatmaps, scatter plots, time series
Feature Selection → Drop irrelevant columns (Date, Events)
Model Training → Linear Regression using scikit-learn
Evaluation → R² score and Mean Squared Error (MSE)
Visualization → Compare actual vs predicted rainfall, plot rainfall trends
📈 Sample Output
R² Score: Measures how well the model explains variance in rainfall
MSE: Measures average error of predictions
Visualizations include:
Correlation heatmap
Precipitation vs temperature scatter plot
Actual vs predicted precipitation plot
Precipitation trends over time
📚 Concepts Learned
Handling messy real-world data
Data preprocessing with Pandas & NumPy
Building regression models with scikit-learn
Data visualization with Matplotlib & Seaborn
✅ Future Improvements
Try advanced models: Decision Tree, Random Forest, XGBoost
Perform feature engineering (e.g., seasonal/weather event encoding)
Deploy as a web app using Flask/Streamlit
