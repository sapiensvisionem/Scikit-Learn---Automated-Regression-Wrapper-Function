# Regression-Wrapper-Function-in-Python-Sklearn

Using Scikit-Learn library in Python, I created a wrapper function that automates regression with a single line of code. It takes in two arguments: data and location where it will store results in csv and rds format. The function runs 17 different statistical and machine learning algorithms from linear regression to multilayer perceptron. The function returns the following two items in the given location:

1. summary table of evaluation metrics (RMSE, R2, etc) of every regression model on test set
2. save every model
