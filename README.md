# Code README - Iris Dataset Exploration and SVM Classification
This README provides a brief overview of the Python code that focuses on the exploration of the Iris dataset and the implementation of Support Vector Machine (SVM) classification. The code uses various libraries, including pandas, scikit-learn, and matplotlib.

## Objective
The main objective of this code is to showcase the exploration of the Iris dataset and demonstrate how to perform classification using SVM.

## Code Structure
Import Libraries and Load Dataset:

Import the necessary libraries, including pandas, from sklearn.datasets import the load_iris function.
Load the Iris dataset using the load_iris() function.
Dataset Exploration:

Use the dir(iris) function to explore the attributes of the Iris dataset.
Display the feature names and target names.
Create a DataFrame and Add Target Column:

Create a pandas DataFrame using the features from the Iris dataset.
Add a column named "target" and populate it with the target values from the dataset.
Add a column named "flower name" by applying a lambda function to map target values to target names.
DataFrame Information:

Display information about the DataFrame using the info() function.
## Data Visualization:

Create scatter plots to visualize the sepal dimensions and petal dimensions for different flower types.
## Data Splitting and SVM Classification:

Split the data into features (x) and target (y) variables.
Split the data into training and testing sets using train_test_split from scikit-learn.
Import the Support Vector Machine (SVM) classifier from sklearn.svm.
Initialize the SVM model with a specific parameter (C=10).
Train the SVM model on the training data using the fit() function.
Calculate the accuracy score of the SVM model on both the testing and training sets.
## Prediction and Evaluation:

Predict flower types on the testing set using the trained SVM model.
Import the mean_squared_error function from sklearn.metrics.
Calculate the mean squared error between the predicted and actual target values.
## Usage
Ensure you have Python and the required libraries installed.
Run the script in your preferred Python environment.
The code will load the Iris dataset, explore its attributes, create visualizations, perform SVM classification, and evaluate the results.
## Note
This code serves as a demonstration of using SVM for classification on the Iris dataset.
Depending on your use case, you may need to customize hyperparameters, explore additional evaluation metrics, and handle outliers or imbalanced classes if necessary.
Always consider best practices and ethical considerations when working with datasets and machine learning algorithms.
