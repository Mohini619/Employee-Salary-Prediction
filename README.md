Employee Salary Prediction
This project explores the use of machine learning to predict employee salaries based on relevant features. The focus is on building a linear regression model using Python libraries like pandas, NumPy, scikit-learn, and seaborn.

Getting Started

Clone the Repository:
git clone https://github.com/Mohini619/employee-salary-prediction.git

Install Dependencies:
Use pip to install the required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn

Run the Script:
Navigate to the project directory and execute the Python script:

Project Overview

Data Loading: The Salary.csv dataset is loaded using pandas.

Data Exploration:
Basic information about the data (dimensions, data types, null values) is displayed with data.info().
A scatter plot is generated to visualize the relationship between "YearsExperience" and "Salary" using matplotlib.pyplot and seaborn.

Data Preprocessing:
The predictor features (x) are separated from the target variable ("Salary" - y).
Data splitting is performed using train_test_split from sklearn.model_selection to create training and testing sets.

Model Building:
A linear regression model (lr) is created using LinearRegression from sklearn.linear_model.
The model is trained on the training data (x_train and y_train).

Model Evaluation:
Predictions are made on the testing data (x_test) using lr.predict().
The root mean squared error (RMSE) is calculated using mean_squared_error from sklearn.metrics to measure the model's performance.
The R-squared score is also calculated using r2_score to assess the model's goodness of fit.
