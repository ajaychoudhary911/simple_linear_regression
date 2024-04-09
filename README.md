# simple_linear_regression

Simple Linear Regression
This repository contains Python code for implementing a simple linear regression model using the salary data provided in the 'Salary_Data.csv' file.

Code Structure
The simple_linear_regression.py script contains the code for performing the following tasks:

1. Importing the Libraries
Importing NumPy, Matplotlib, and Pandas libraries, which are commonly used for data manipulation, visualization, and numerical operations in Python.
2. Importing the Dataset
Reading the 'Salary_Data.csv' file containing the dataset.
Separating independent variable (feature) and dependent variable (target) from the dataset.
3. Splitting the Dataset
Splitting the dataset into training and test sets using train_test_split from scikit-learn.
4. Training the Model
Training a simple linear regression model on the training set using LinearRegression from scikit-learn.
5. Making Predictions
Predicting the salaries for the test set using the trained regression model.
6. Visualizing the Results
Plotting the actual salaries vs. years of experience for both the training and test sets to visualize the performance of the model.
Usage
To use this script, follow these steps:

Ensure you have Python installed on your system.
Install the required libraries by running pip install -r requirements.txt.
Place your dataset in CSV format and update the filename in the script accordingly.
Run the script using Python.
bash
Copy code
python simple_linear_regression.py
Requirements
Python 3.x
NumPy
Matplotlib
Pandas
scikit-learn
Contributors
Your Name - Creator
Feel free to contribute to this project by forking the repository and submitting pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
