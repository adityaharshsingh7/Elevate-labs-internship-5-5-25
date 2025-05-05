Iris Species Classification Using Support Vector Machine (SVM)

This project showcases how to use a Support Vector Machine (SVM) algorithm to classify Iris flower species based on the popular Iris dataset. It's a beginner-friendly machine learning project designed to introduce classification concepts using SVM.

 What is SVM?

Support Vector Machine (SVM) is a supervised learning algorithm widely used for both classification and regression tasks. Its core objective is to determine the optimal hyperplane that effectively separates different classes within a feature space.

 In binary classification, SVM aims to maximize the margin between two distinct classes.
 For multi-class scenarios like the Iris dataset, SVM applies approaches like "one-vs-rest" or "one-vs-one".
 SVM performs well in high-dimensional data settings and is memory-efficient, as it relies only on a subset of training data known as support vectors.

 Overview of the Iris Dataset

The Iris dataset is a classic and widely-used dataset in the fields of machine learning and statistics. It comprises 150 records spanning three Iris flower species: Iris setosa, Iris versicolor, and Iris virginica. Each record includes four key features:

 Sepal length
 Sepal width
 Petal length
 Petal width

 Project Pipeline

1. Data Loading – Load the dataset using `sklearn.datasets`.
2. Data Preprocessing – Split the dataset into training and testing subsets.
3. Model Training – Train an SVM classifier with `sklearn.svm.SVC`.
4. Prediction & Evaluation – Predict labels for test data and assess model accuracy.

 Tools & Libraries Used

 Python 3
 scikit-learn
 NumPy
 Matplotlib (optional, for data visualization)
