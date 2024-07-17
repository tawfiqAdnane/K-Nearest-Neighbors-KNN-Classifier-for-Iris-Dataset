# K-Nearest-Neighbors-KNN-Classifier-for-Iris-Dataset
Description:
This project involves using the K-Nearest Neighbors (KNN) algorithm to classify the famous Iris dataset. The Iris dataset contains measurements of various features of Iris flowers, such as sepal length, sepal width, petal length, and petal width. The goal is to classify the species of Iris flowers based on these measurements.

Steps and Features:

Data Loading and Visualization:

Load the Iris dataset using load_iris() from sklearn.datasets.
Create feature (X) and target (y) arrays from the dataset.
Visualize the dataset using a scatter plot to show relationships between features (sepal length vs sepal width).
Model Training:

Split the dataset into training and testing sets using train_test_split() from sklearn.model_selection.
Train a KNN classifier (KNeighborsClassifier) with a chosen number of neighbors (n_neighbors) and a specific distance metric (default is Euclidean, but here metric="cosine" is used).
Model Evaluation:

Calculate and print the accuracy of the trained KNN model on the test set using .score() method of KNeighborsClassifier.
Evaluate the model performance across different values of n_neighbors (from 1 to 29) by computing accuracy scores for each and plotting them.
Conclusion:
This project demonstrates the application of the KNN algorithm for classification tasks using the Iris dataset. It explores how varying the number of neighbors (k) and the distance metric affects the model's accuracy. The final visualization (plt.plot(scores)) shows how accuracy changes with different values of k, providing insights into model selection and performance optimization.

By following these steps, you can effectively build and evaluate a KNN classifier for the Iris dataset, gaining practical experience in machine learning model development and evaluation.
