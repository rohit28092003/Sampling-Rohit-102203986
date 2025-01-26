Credit Card Sampling Analysis
Project Overview
This project involves analyzing different sampling techniques to handle imbalanced credit card transaction data and evaluating the performance of various machine learning models on these sampled datasets. The goal is to identify the most effective sampling technique and model combination for predicting fraudulent transactions.

Sampling Techniques Used
Simple Random Sampling: Selects a subset of individuals randomly from the larger dataset.
Stratified Sampling: Divides the population into homogeneous subgroups before sampling.
Cluster Sampling: Divides the population into clusters and randomly selects entire clusters.
Systematic Sampling: Selects samples based on a fixed periodic interval.
Multistage Sampling: Involves multiple stages of sampling, typically combining several methods.
Models Evaluated
Random Forest Classifier
Gradient Boosting Classifier
Logistic Regression
SVM (Support Vector Machine)
K-Nearest Neighbors (KNN)
Requirements
This project is implemented in Python, using libraries such as Pandas, NumPy, scikit-learn, and imbalanced-learn. Ensure you have these installed:

pip install pandas numpy scikit-learn imbalanced-learn
Dataset
The dataset used is a CSV file containing credit card transactions, with features labeled from V1 to V28 (PCA transformed features), 'Time', and 'Amount'. The target variable is 'Class', where 1 represents fraudulent transactions and 0 represents non-fraudulent transactions.

Setup and Execution
Clone the repository or download the project to your local machine.
Place your dataset in the root directory or modify the dataset path in the script.
Run the script using Python:
python sampling.py
Check the output CSV file model_sampling_results_pivot.csv for the accuracy results of different models under various sampling techniques.
Results
Results are saved in a pivot table format in the model_sampling_results_pivot.csv file, where each row represents a machine learning model and each column a sampling technique. The cells contain the accuracy scores, allowing for easy comparison across different methods.
