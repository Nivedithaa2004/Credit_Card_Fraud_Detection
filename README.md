# Credit-Card-Fraud-Detection-Using-Machine-Learning

## ABSTRACT

Credit card fraud is one of the major challenges faced by financial institutions and customers. With the increasing use of credit cards for online and offline transactions, detecting unauthorized transactions has become increasingly important. Machine learning can help identify unusual transaction patterns and distinguish fraudulent transactions from legitimate ones.

This project focuses on developing a machine learning-based system for detecting fraudulent credit card transactions. Historical transaction data is used to train different classification models, and their performance is evaluated using test data. The project compares multiple machine learning algorithms to determine their effectiveness in identifying fraudulent transactions.

<br>

<b>Keywords:</b> Credit Card Fraud Detection, Machine Learning, Fraudulent Transactions, K-Nearest Neighbors, Logistic Regression, Support Vector Machine, Decision Tree.

<br>
<br>

## Overview

The growing use of credit cards has made electronic payments convenient, but it has also increased the possibility of unauthorized transactions. Credit card fraud can occur when someone gains access to confidential card information or uses a card without the owner's permission.

Since a large number of transactions take place every day, manually identifying fraudulent activities is difficult and time-consuming. Machine learning provides an automated approach by learning patterns from previous transactions and using those patterns to identify potentially fraudulent transactions.

This project explores different machine learning classification techniques and compares their performance in detecting fraudulent transactions from a large transaction dataset.

<br>
<br>

## Project Goals

The primary goal of this project is to develop a machine learning-based approach for identifying fraudulent credit card transactions.

The main objectives are:

- To analyze credit card transaction data.
- To identify patterns related to fraudulent transactions.
- To preprocess the dataset for machine learning.
- To implement multiple classification algorithms.
- To evaluate the performance of each model.
- To compare the results obtained from different algorithms.
- To determine a suitable machine learning model for fraud detection.

The project also aims to understand how machine learning can be applied to improve the security of financial transactions.

<br>
<br>

## Data Source

The dataset used in this project is obtained from Kaggle. It contains credit card transactions made by European cardholders during September 2013.

The dataset contains **284,807 transactions and 31 attributes**. Most of the features are numerical and have been transformed using Principal Component Analysis (PCA) to protect the confidentiality of the original transaction information.

The dataset includes the following important attributes:

- **Time** – Represents the time elapsed between transactions.
- **Amount** – Represents the amount involved in each transaction.
- **V1 to V28** – Anonymized features obtained through PCA transformation.
- **Class** – Indicates whether the transaction is legitimate or fraudulent.

The `Class` attribute contains two possible values:

- `0` – Legitimate transaction
- `1` – Fraudulent transaction

The dataset is highly imbalanced because fraudulent transactions form only a small portion of the total transactions.

<br>
<br>

<b>Dataset: </b>
<a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle Dataset</a>

<br>
<br>

## Algorithm

The following machine learning algorithms are used in this project:

1. K-Nearest Neighbors (KNN)
2. Logistic Regression (LR)
3. Support Vector Machine (SVM)
4. Decision Tree (DT)

These algorithms are trained using the transaction dataset and their results are compared to understand which model performs better for fraud detection.

<br>
<br>

## Future Work

The project can be further improved by using larger and more diverse transaction datasets. Advanced machine learning and deep learning techniques can also be explored to improve the detection of complex fraudulent patterns.

Future improvements may include:

- Using Random Forest, XGBoost, and other ensemble learning techniques.
- Applying methods such as SMOTE to handle the imbalanced dataset.
- Performing hyperparameter tuning to improve model performance.
- Developing a real-time fraud detection system.
- Adding transaction location and device information.
- Using customer transaction history to identify unusual activities.
- Developing a web-based application for real-time fraud prediction.

<br>
<br>

## Conclusion

This project demonstrates how machine learning can be used to detect fraudulent credit card transactions. Four classification algorithms, namely KNN, Logistic Regression, Support Vector Machine, and Decision Tree, are implemented and compared.

The performance of each model can be evaluated using metrics such as accuracy, precision, recall, and F1-score. The comparison helps in understanding the strengths and limitations of different machine learning approaches for credit card fraud detection.

Overall, the project shows that machine learning can be effectively used to analyze transaction patterns and assist in identifying potentially fraudulent activities, thereby improving the security of credit card transactions.
