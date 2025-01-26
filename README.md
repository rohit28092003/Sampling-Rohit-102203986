# Credit Card Sampling Analysis

## Project Overview
This project involves analyzing different sampling techniques to handle imbalanced credit card transaction data and evaluating the performance of various machine learning models on these sampled datasets. The goal is to identify the most effective sampling technique and model combination for predicting fraudulent transactions.

## Sampling Techniques Used
- Simple Random Sampling: Selecting samples randomly from the population.
- Systematic Sampling: Choosing samples at regular intervals after a random starting point.
- Cluster Sampling: Randomly selecting entire clusters from the population.
- Stratified Sampling: Dividing the population into subgroups based on specific criteria.
- Bootstrap Sampling: Resampling with replacement to generate multiple samples from the     original dataset.

Following the generation of five distinct samples using these techniques, five models were applied to each sample. The accuracies of each model for a given sample are summarized in the following table:

| Sample Technique      | Random Forest | Logistic Regression | Naive Bayes      | Decision Trees   | KNN              |
|-----------------------|---------------|---------------------|------------------|------------------|------------------|
| Simple Random Sampling| 0.9870        | 0.8831              | 0.7013           | 0.9610           | 0.8701           |
| Systematic Sampling   | 1.0000        | 0.8926              | 0.7450           | 1.0000           | 0.9329           |
| Cluster Sampling      | 1.0000        | 0.9670              | 1.0000           | 1.0000           | 0.9890           |
| Stratified Sampling   | 1.0000        | 0.9030              | 0.7239           | 0.9925           | 0.9552           |
| Bootstrap Sampling    | 1.0000        | 0.9250              | 0.7500           | 0.9625           | 0.9375           |

In above table, each row corresponds to a sampling technique, and each column represent the accuracy achieved by each model applied to the respective sample generated using that respective technique.
<br>
### The RANDOM FOREST outperformed all other models when applied to Stratified Sampling Technique.
