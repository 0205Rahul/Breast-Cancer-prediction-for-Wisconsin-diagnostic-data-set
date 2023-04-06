# Breast Cancer Wisconsin Dataset - KNN and ANN Classification
This GitHub repository contains the code for applying two popular machine learning algorithms, K-Nearest Neighbors (KNN) and Artificial Neural Networks (ANN), to the Breast Cancer Wisconsin (Diagnostic) Dataset. The goal is to predict whether a breast mass is malignant or benign based on several features extracted from digitized images of a fine needle aspirate (FNA) of a breast mass.

The repository contains Jupyter Notebooks that demonstrate how to preprocess the data, apply the KNN and ANN algorithms, and evaluate their performance.

## Dataset
The Breast Cancer Wisconsin (Diagnostic) Dataset contains 569 instances with 30 numeric features. The dataset is widely used in the machine learning community for binary classification problems, and it is a benchmark dataset for evaluating the performance of different algorithms.

## Conclusion
In conclusion, this repository provides a comprehensive guide on how to apply the KNN and ANN algorithms to the Breast Cancer Wisconsin (Diagnostic) Dataset, and how to evaluate and compare the performance of the algorithms using various metrics. The code is well-documented and can be easily extended to other classification tasks.

Some Major Conclusions :
1. KNN is implemented with k=5 (no. of nearest neighbors), while ANN has 2 hidden layers of 16 neurons each. These elementary things are on subject to change
2. The same data, is divided into training and testing, and corresponding scores (Accuracy, ROC-AUC), confusion matrices, and errors are generated. Some of the data visualizations have been shown.
3. Data has been scaled for both, and normalised, to obtain optimal results. AUC and accuracies shows that ANN works better with a good convergence plot for the same dataset. Higher area under ROC curve is occuring for ANN.
4. Thus ANN model tends to perform better than KNN for complex datasets like the Breast Cancer Wisconsin (Diagnostic) dataset.
