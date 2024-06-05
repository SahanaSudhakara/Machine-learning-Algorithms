# Iris Data Set Analysis

## Introduction
The purpose of this project is to study the impact of different proximity measures on various types of analyses using the Iris data set. Proximity measures are crucial for tasks such as clustering, anomaly detection, and supervised classification. The Iris data set is a well-known dataset containing information about different species of Iris flowers. The dataset includes four dimensions of measurements (sepal length, sepal width, petal length, and petal width) and the corresponding species label.

## Dataset
The Iris data set used in this analysis is available in the Files tab as `iris.csv`. Each row in the CSV file represents a data point with four dimensions and a corresponding label indicating the species of Iris flower.

## Analysis Tasks

### 1. Compute Euclidean Distance
Calculate the Euclidean distance between all pairs of species mean vectors and report them in a table.

### 2. Standardize Column Vectors and Compute Euclidean Distance
Standardize each column vector and compute the Euclidean distance between species mean vectors.

### 3. Compute Mahalanobis Distance
Calculate the Mahalanobis distance between species mean vectors.

### 4. Compute Cosine Similarity
Compute the cosine similarity between species mean vectors.

### 5. Compute Pearson Correlation
Calculate the Pearson correlation coefficient between species mean vectors.

### 6. Pros and Cons of Proximity Measures
Evaluate the advantages and disadvantages of each proximity measure for quantifying species similarity.

### 7. Outlier Detection using Mahalanobis Distance
Identify outliers within each species using Mahalanobis distance as the proximity measure.

### 8. Outlier Detection using Euclidean Distance
Detect outliers within each species using Euclidean distance as the proximity measure.

### 9. Comparison of Anomaly Detection Results
Compare the effectiveness of Mahalanobis and Euclidean distances for anomaly detection.

### 10. Nearest Neighbors-like Classifier Evaluation
Evaluate a nearest neighbors-like classifier using Mahalanobis distance as the proximity measure and report results in a contingency table.

## Conclusion
This project aims to explore various proximity measures and their impact on different analyses using the Iris data set. By analyzing the results, we can gain insights into the effectiveness of these measures for tasks such as anomaly detection and classification.

## Comparing Distances
The distances computed in this project (Euclidean, standardized Euclidean, Mahalanobis, Cosine similarity, Pearson correlation) will be compared based on their performance in tasks such as anomaly detection and classification. Factors such as data distribution, dimensionality, and scale will be considered to determine the suitability of each distance measure for different scenarios.
