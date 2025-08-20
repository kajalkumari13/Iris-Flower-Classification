Iris Flower Classification

Project Overview

The Iris dataset is one of the most famous datasets in machine learning, often used for classification tasks. It contains measurements of 150 iris flowers belonging to three species: Setosa, Versicolor, and Virginica. The dataset includes four features:

Sepal Length

Sepal Width

Petal Length

Petal Width

The goal of this project is to build a supervised machine learning model that can accurately classify the species of an iris flower based on these features.

 Steps Involved

Data Loading

Used sklearn.datasets to load the Iris dataset.

Converted into features (X) and target labels (y).

Data Preprocessing

Checked for missing values (none in this dataset).

Separated data into features and target labels.

Train-Test Split

Divided dataset into training (80%) and testing (20%) sets using train_test_split().

Model Training

Implemented a Decision Tree Classifier from sklearn.tree.

Trained the model on the training dataset.

Model Evaluation

Measured performance using accuracy score, confusion matrix, and classification report.

Visualized results using heatmap and decision tree diagram.

Prediction

Tested with a new input sample: [5.0, 3.4, 1.5, 0.2]

Model correctly predicted the species as Setosa.

 Results

Achieved high accuracy (≈ 95–100%) on the test dataset.

Confusion matrix showed correct classification for most test samples.

Feature importance revealed that petal length and petal width are the most significant features.

 Applications

Automated flower classification in botanical research.

Can be extended for plant species recognition.

Serves as a beginner-friendly ML project for learning supervised classification.

 Technologies Used

Python

Scikit-learn

Pandas

Matplotlib & Seaborn

👩‍💻 Author

Kajal Kumari
