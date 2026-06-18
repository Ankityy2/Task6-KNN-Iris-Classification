# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Project Overview

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for multi-class classification using the Iris dataset. The objective is to classify Iris flowers into different species based on their sepal and petal measurements.

KNN is a distance-based supervised machine learning algorithm that classifies new observations based on the majority class of their nearest neighbors.

---

## Dataset Information

### Dataset Source

Scikit-Learn Built-in Iris Dataset

### Dataset Size

* Total Samples: 150
* Total Features: 4
* Total Classes: 3

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes

* Setosa
* Versicolor
* Virginica

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Loading

The Iris dataset was loaded directly from the Scikit-Learn library and converted into a Pandas DataFrame for easier analysis.

### 2. Dataset Exploration

Performed exploratory analysis to understand:

* Dataset dimensions
* Feature information
* Statistical summary
* Target class distribution

### 3. Train-Test Split

The dataset was divided into:

* Training Data: 80%
* Testing Data: 20%

This allows the model to learn from training data and evaluate performance on unseen data.

### 4. Model Training

A K-Nearest Neighbors (KNN) classifier was trained using:

* K Value = 5
* Euclidean Distance Metric (default)

The model learns by storing the training data and classifying new samples based on the nearest neighbors.

### 5. Prediction

The trained model was used to predict flower species on the testing dataset.

### 6. Model Evaluation

Model performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 7. K Value Comparison

Multiple K values were tested to identify the most suitable number of neighbors.

K values evaluated:

* K = 1
* K = 2
* K = 3
* K = 4
* K = 5
* K = 6
* K = 7
* K = 8
* K = 9
* K = 10

The K value producing the highest accuracy was selected as the optimal value.

---

## Model Performance

### Evaluation Metrics

The KNN classifier achieved high classification accuracy on the Iris dataset.

Metrics Used:

* Accuracy Score
* Precision
* Recall
* F1 Score

These metrics indicate the effectiveness of the model in correctly identifying flower species.

---

## Key Concepts Learned

* Supervised Machine Learning
* Classification Algorithms
* K-Nearest Neighbors (KNN)
* Distance-Based Learning
* Train-Test Split
* Accuracy Evaluation
* Classification Report
* Confusion Matrix
* K Value Selection

---

## Interview Questions

### What is KNN?

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm that classifies a data point based on the majority class of its nearest neighbors.

### How does KNN work?

1. Select a value of K.
2. Calculate distances from the new point to all training points.
3. Identify the K nearest neighbors.
4. Perform majority voting.
5. Assign the most common class.

### How do you choose the value of K?

The value of K is selected by testing multiple values and choosing the one that provides the highest accuracy while avoiding overfitting and underfitting.

### What happens if K is too small?

The model may overfit and become sensitive to noise.

### What happens if K is too large?

The model may underfit and fail to capture important patterns.

---

## Conclusion

A K-Nearest Neighbors (KNN) classifier was successfully implemented using the Iris dataset.

The model was trained, tested, and evaluated using multiple performance metrics. Different K values were compared to identify the optimal number of neighbors.

The project demonstrates the practical application of distance-based classification algorithms and provides a strong foundation for understanding supervised machine learning techniques.

---

## Repository Structure

Task6-KNN-Iris-Classification/

├── Task6_KNN_Classification.ipynb

├── README.md

---

## Author

Ankit Yadav


