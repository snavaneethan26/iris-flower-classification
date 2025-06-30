Iris Flower Classification using Decision Tree

This repository contains a Python script for classifying Iris flower species based on their sepal and petal measurements. It demonstrates a basic machine learning workflow using the Decision Tree Classifier, including data loading, exploratory data analysis (EDA), model training, and evaluation.

Project Description:
The goal of this project is to build a classification model that can accurately predict the species of an Iris flower (setosa, versicolor, or virginica) 
given its four features : sepal length, sepal width, petal length, and petal width. A Decision Tree Classifier is used for this task due to its interpretability and effectiveness on this dataset.

Features:
Data Loading: Loads the Iris dataset from a CSV file.
Data Preprocessing: Handles the conversion of species names (strings) to numerical labels using LabelEncoder.

Exploratory Data Analysis (EDA):

Displays the first few rows and information about the dataset.
Generates a pairplot to visualize relationships between features and species.
Calculates and displays the correlation matrix of features.
Data Splitting: Divides the dataset into training and testing sets to evaluate model performance on unseen data.
Model Training: Trains a Decision Tree Classifier on the training data.
Model Evaluation: Assesses the model's performance using standard classification metrics:
Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-Score for each class)

Requirements

To run this script, you need to have the following Python libraries installed:
pandas
matplotlib
seaborn
scikit-learn

You can install them using pip: pip install pandas matplotlib seaborn scikit-learn

Usage
Download the Iris Dataset: Ensure you have the Iris.csv file. You can typically find this dataset as part of scikit-learn's datasets or from various online machine learning repositories.
Place Iris.csv: Save the Iris.csv file in a location accessible by your Python script.
Update csv_file_path: Open the iris_flower_classification.py script and modify the csv_file_path variable to point to the correct absolute path of your Iris.csv file.

Important Note for Windows Users: The r prefix before the string (r"...") creates a "raw string," which correctly handles backslashes in file paths on Windows.
Run the Script: Execute the Python script from your terminal or IDE: python iris_flower_classification.py

