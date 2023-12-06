# CO2 Emission Prediction and Analysis
This repository contains code for predicting CO2 emissions from cars using a linear regression model in Python. The goal is to analyze the impact of various features, such as fuel type, engine size, and transmission type, on CO2 emissions and provide insights for designing more environmentally friendly cars.

# Dataset
The dataset used for this analysis is loaded from the 'CO2 Emissions.csv' file. The dataset includes information about various features of cars, including make, model, vehicle class, transmission type, fuel type, and CO2 emissions in grams per kilometer.

# Data Exploration and Preprocessing
The code performs data exploration, including checking the dataset's shape, information, and handling any missing values. It then preprocesses the data by changing fuel type names, performing dummy encoding on categorical variables, and reducing dimensionality using feature selection.

# Skewness Visualization
The code visualizes the skewness of selected features using distribution plots, histograms, and kurtosis analysis. Understanding skewness is crucial for building a better predictive model.

# Correlation Analysis
The code calculates and visualizes the correlation between variables, helping identify features that significantly affect CO2 emissions. It also removes insignificant features based on correlation values.

# Linear Regression Model
The linear regression model is built using selected features to predict CO2 emissions. The model is trained and evaluated using mean squared error (MSE) and R-squared metrics.

# Conclusion
The analysis provides insights into the relationship between car features and CO2 emissions. The linear regression model suggests that cars with smaller engine sizes, fewer cylinders, and better fuel efficiency contribute less to CO2 emissions. These findings can guide car manufacturers in designing more environmentally friendly vehicles.

Feel free to explore the code and results for a detailed understanding of CO2 emissions prediction and analysis.

# Usage
Ensure you have the necessary dependencies installed:

pandas 
seaborn 
matplotlib
scikit-learn


Run the code to load the dataset, perform data exploration, preprocess the data, and build/train the linear regression model.

Explore the results and analysis to gain insights into the impact of different car features on CO2 emissions.

# Note
Make sure to have the 'CO2 Emissions.csv' file in the same directory as the code for successful execution.
