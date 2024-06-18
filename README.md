# Breast-cancer-prediction
Dataset
The dataset used is "breast cancer.csv" which contains features extracted from breast mass images.

Steps
Import Libraries: Import necessary libraries such as pandas, sklearn, and matplotlib.
Load Dataset: Read the dataset from the CSV file.
Data Preprocessing:
Check for null values.
Split the data into features (X) and target (Y).
Split the data into training and testing sets.
Standardize Features: Standardize the features using StandardScaler.
Cross-Validation: Perform cross-validation to determine the best k value for the KNN classifier.
Model Training: Train the KNN classifier using the best k value.
Model Evaluation: Evaluate the model on the training and testing sets.
Performance Metrics: Calculate accuracy, precision, recall, and F1 score.
Classification Report: Display the classification report.
Predictions: Display the true and predicted labels for the test set.
