# Text Classification in Spam Detection


This project implements a text classification task for spam detection using various classifiers: Naive Bayes, Decision Tree, and Random Forest. Here's a summary of what it does:

Data Loading and Exploration:

Loads a dataset containing SMS messages labeled as spam or ham (not spam).
Prints the first few rows of the dataset to inspect its structure.
Data Preprocessing and Splitting:

Splits the data into training and test sets using the train_test_split function from scikit-learn.
Feature Extraction:

Uses a count vectorizer to convert text data into numerical features, specifically counts of word occurrences.
Model Training:

Trains three different classifiers: Naive Bayes, Decision Tree, and Random Forest, using the training data transformed by the count vectorizer.
Model Evaluation:

Makes predictions on the test data using each classifier.
Calculates the accuracy of each classifier using the accuracy_score function from scikit-learn.
Displays the accuracy of each classifier.
Confusion Matrix Visualization:

Generates confusion matrices for each classifier using the confusion_matrix function from scikit-learn.
Visualizes the confusion matrices using heatmap plots with seaborn and matplotlib.
Overall, this code provides a comparison of different classifiers for the task of spam detection and visualizes their performance using confusion matrices.
