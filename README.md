# breast-cancer-classification
Breast Cancer Classification using Machine Learning — A supervised learning project applying Logistic Regression, Decision Tree, Random Forest, SVM, and k-NN to the sklearn breast cancer dataset. Includes preprocessing, model comparison, and performance analysis.


Objective

The objective of this project is to apply supervised learning techniques to classify breast cancer as malignant or benign using the Breast Cancer dataset from the sklearn library.
This project demonstrates data preprocessing, model implementation, and comparison of various classification algorithms.Dataset

The dataset is available in scikit-learn via:

from sklearn.datasets import load_breast_cancer


It contains 569 samples and 30 numerical features describing cell nuclei characteristics, along with a binary target variable:

0 → Malignant

1 → Benign

Preprocessing Steps

Loaded the dataset using load_breast_cancer() and converted it into a pandas DataFrame.

Checked for missing values (none found).

Applied StandardScaler to standardize feature scales.

Split the data into 80% training and 20% testing using train_test_split().

Models Implemented

The following five classification algorithms were trained and evaluated:

Logistic Regression – Linear model that estimates class probabilities using the sigmoid function.

Decision Tree Classifier – Non-linear model that splits data based on feature thresholds.

Random Forest Classifier – Ensemble of multiple decision trees for better generalization.

Support Vector Machine (SVM) – Finds the optimal hyperplane separating classes.

k-Nearest Neighbors (k-NN) – Classifies data based on the majority label of nearest neighbors.

Model Evaluation

Each model was evaluated using:

Accuracy Score

Confusion Matrix

The best-performing algorithm achieved the highest accuracy and robust classification performance, while results were compared to identify the least effective model.
