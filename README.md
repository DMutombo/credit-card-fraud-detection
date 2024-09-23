# Credit Card Fraud Detection

## Abstract

This project aims to leverage predictive data analytics to detect fraudulent credit card transactions. By employing various machine learning techniques such as logistic regression, decision trees, and neural networks, this project seeks to build models that can effectively identify fraudulent transactions within a dataset. The project is implemented in R, taking advantage of its robust statistical and visualization libraries.

## Background
Credit card fraud poses a significant threat to both consumers and financial institutions. As the volume of transactions continues to rise, so does the complexity and frequency of fraudulent activities. Machine learning provides an opportunity to detect fraud in real-time by analyzing transaction data for patterns that could indicate illegitimate behavior.

## Problem
Traditional methods of detecting fraud often rely on predefined rules or manual review processes, which can be slow and error-prone. Given the imbalanced nature of fraud detection (with fraudulent transactions being rare compared to legitimate ones), there's a need for advanced techniques that can accurately identify fraudulent transactions without flagging too many false positives.

## Solution
This project develops multiple machine learning models to detect fraudulent transactions in a dataset. The following steps were completed:

+ Exploratory Data Analysis (EDA): Examined the dataset to understand the distribution of features and the imbalance between fraudulent and non-fraudulent transactions.

+ Logistic Regression Model: Built a generalized linear model for binary classification to predict whether a transaction is fraudulent.

+ Decision Tree Model: Created a decision tree to classify transactions, using the Rpart module in R.

+ Neural Network: Developed a neural network model to classify transactions, considering the complexities of relationships between features.

+ Model Evaluation: Compared the performance of these models using metrics such as accuracy and the Receiver Operating Characteristic (ROC) curve.

## Results
+ Logistic Regression: The logistic regression model provided a baseline accuracy and ROC curve for comparison.
+ Decision Tree: The decision tree model offered better interpretability, allowing us to visualize the decision-making process for classifying transactions.
+ Neural Network: The neural network model showed the highest accuracy but at the cost of increased training time and complexity.
The models were evaluated on a test dataset, and their performances were compared using ROC curves. The neural network model demonstrated the best performance with the highest area under the curve (AUC), followed by the decision tree and logistic regression models.

## Summary
This project successfully demonstrated the use of predictive analytics in detecting credit card fraud. By comparing different machine learning models, we identified that neural networks, despite their complexity, can provide superior accuracy in fraud detection tasks. However, decision trees and logistic regression remain valuable tools, particularly for their interpretability and faster training times.

Future work could involve enhancing model performance through techniques such as ensemble learning or exploring other advanced models like support vector machines (SVMs) and deep learning networks.

