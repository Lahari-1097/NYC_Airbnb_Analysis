NYC Airbnb Data Analysis and Prediction
Overview
This project aims to analyze and predict various aspects of Airbnb listings in New York City using the "AB_NYC_2019.csv" dataset. The analysis includes exploring booking trends, affordability by neighborhood, and predicting the average length of stay using regression.

Files
AB_NYC_2019.csv: The dataset containing Airbnb listings in NYC.
NYC_Airbnb_Analysis.ipynb: Jupyter Notebook containing the code for data analysis, visualization, and prediction.
README.md: This file.
Dependencies
Python 3.x
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn

Usage:
Clone the repository or download the files.
Make sure you have Python and the required libraries installed.
Run the Jupyter Notebook NYC_Airbnb_Analysis.ipynb to execute the analysis and predictions.
Analysis Steps
Data Loading and Inspection: Load the dataset and check for missing values and data types.

Data Preprocessing:
Remove duplicate entries.
Convert 'last_review' to datetime format.
Remove rows with missing values in 'reviews_per_month'.
Exploratory Data Analysis (EDA):
Explore booking trends by neighborhood.
Analyze affordability by neighborhood.
Calculate the average length of stay.

Predictive Modeling:
Train a RandomForestRegressor model to predict the average length of stay based on features like number of reviews, reviews per month, and availability.
Evaluate the model's performance using Mean Squared Error.

Data Visualization:
Generate a heatmap to visualize the average price by neighborhood group and neighborhood.
Create a bar plot to show the average price by neighborhood group.

Results:
The analysis provides insights into booking trends and affordability across different neighborhoods in NYC.
The predictive model accurately estimates the average length of stay based on the provided features.
Visualizations aid in understanding the distribution of prices and booking patterns.
