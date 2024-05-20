# Data-Exploration-and-Data-Visualization
Final Project for America on Tech - Tech Flex Leaders Data Science Track

Project Overview
This project involves exploring and visualizing data from a social media advertisement dataset. The dataset includes features such as Age and EstimatedSalary of users, and the target variable is whether the user purchased a product after seeing an ad. The project includes data exploration, visualization, feature engineering, and a simple machine learning model to predict purchases based on age and estimated salary.

Steps Followed
Data Exploration and Visualization
Data Curation/Feature Engineering
Machine Learning Model - Supervised Learning
1. Data Exploration and Visualization
Reading Data:

Loaded the dataset using pandas and displayed the first few rows to understand the structure of the data.
Statistical Analysis:

Calculated the mean, standard deviation, and variance for the numerical features (Age and EstimatedSalary).
Visualization:

Used seaborn and matplotlib to create box plots, bar charts, scatter plots, and histograms to explore the distribution, skewness, and shape of the features.

2. Data Curation/Feature Engineering
Outliers Detection:

Used the Interquartile Range (IQR) method to detect outliers in Age and EstimatedSalary.
Handling Missing Values:

Checked for and dropped any missing values in the dataset.
Dummy Variables:

Converted the categorical target variable 'Purchased' into dummy variables for the machine learning model.

3. Machine Learning Model - Supervised Learning
Logistic Regression Model:
Split the data into training and testing sets.
Trained a logistic regression model to predict whether a user purchased a product based on their age and estimated salary.
Evaluated the model using accuracy score, confusion matrix, and classification report.
