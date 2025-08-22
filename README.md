# Iris Flower Classification

##  Overview
This project demonstrates how to build a machine learning model that classifies iris flowers into three species: Setosa, Versicolor, and Virginica. The Iris dataset contains measurements of flower sepals and petals, which are used to predict the species. The workflow covers everything from exploratory data analysis (EDA) to training a Decision Tree Classifier, evaluating the model, and making predictions on new data.

##  Features of This Project
- Loads and explores the Iris dataset using pandas, seaborn, and matplotlib
- Performs EDA with pair plots, heatmaps, and summary statistics
- Splits the dataset into training and testing sets
- Trains a Decision Tree Classifier with entropy as the splitting criterion
- Evaluates model performance using accuracy, confusion matrix, and classification report
- Visualizes the trained decision tree and feature importance
- Makes predictions on new flower measurements

##  Requirements
Make sure you have Python installed (version 3.8 or higher is recommended). Required libraries:
$ pip install numpy pandas matplotlib seaborn scikit-learn
Alternatively, install from requirements.txt:
$ pip install -r requirements.txt

##  Project Setup
1) Clone this repository and enter the folder:
$ git clone https://github.com/kajalkumari13/Iris-Flower-Classification.git
$ cd Iris-Flower-Classification
2) Install dependencies:
$ pip install -r requirements.txt
3) Run the project:
$ python iris_classifier.py

##  How the Code Works
1) Load the dataset — The Iris dataset is loaded from scikit-learn and converted into a pandas DataFrame.
2) EDA (Exploratory Data Analysis) — Visualizations such as count plots, pair plots, and heatmaps help understand relationships between features.
3) Data preparation — The dataset is split into training and testing sets.
4) Model training — A Decision Tree Classifier (criterion="entropy", max_depth=3) is trained on the data.
5) Model evaluation — Accuracy score, classification report, and confusion matrix are used to evaluate performance.
6) Visualization — The decision tree is plotted, and feature importance is displayed to understand how the model makes predictions.
7) Prediction — The model predicts the species of a new flower when given its measurements.

##  Example Output
- Dataset summary and sample rows
- Distribution plots of species
- Confusion matrix showing correct and incorrect predictions
- Decision tree diagram
- Prediction for a new flower input
Example:
Input: [5.0, 3.4, 1.5, 0.2]
Output: Setosa

##  Conclusion
This project serves as a complete walkthrough of a simple yet powerful machine learning classification task. It demonstrates how to analyze data visually, how to train and evaluate a classifier, and how to interpret results with decision tree visualization and feature importance. The Iris dataset remains a great starting point for anyone learning data science, and this project is designed to be both educational and practical.

 Developed by Kajal Kumari (https://github.com/kajalkumari13)
