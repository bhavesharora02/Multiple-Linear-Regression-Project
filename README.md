This project is an introduction to machine learning with a focus on predicting car selling prices. It covers various stages of the machine learning workflow, including data collection, preprocessing, model training, and evaluation.

**Project Overview**
The goal of this project is to predict car selling prices using linear regression models. The dataset used contains information about various car attributes such as fuel type, seller type, and transmission type.

**Contents**
Importing Dependencies

**Essential libraries for data manipulation, visualization, and machine learning are imported at the beginning.**
Data Collection and Processing

**Loading the Data**: The dataset is loaded from a CSV file into a pandas DataFrame.
**Inspecting the Data**: The first few rows of the dataset are displayed to get an overview. The shape of the dataset is checked to understand its size. A summary of the dataset is obtained to identify missing values and data types.
**Categorical Data Distribution**: The distribution of categorical features like fuel type, seller type, and transmission type is analyzed.
Encoding Categorical Data

Categorical features are converted into numerical values using label encoding to prepare the data for machine learning algorithms.
Splitting the Data

The dataset is separated into features (X) and the target variable (Y). The data is then split into training and testing sets to evaluate the model's performance.

**Model Training - Linear Regression**

A Linear Regression model is initialized and trained using the training data.
Model Evaluation

**Training Data Evaluation**: The model's performance is evaluated on the training data by predicting the selling prices and calculating the R squared error.
**Visualization**: A scatter plot is created to visualize the actual prices versus the predicted prices for the training data.
**Test Data Evaluation**: The model's performance is evaluated on the test data by predicting the selling prices and calculating the R squared error.
**Visualization**: A scatter plot is created to visualize the actual prices versus the predicted prices for the test data.
