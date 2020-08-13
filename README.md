# Credit Card Fraud Detection

# Object
The objective of this project to handle the credit card fraud detection dataset.

# Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 

# Challenges 

This dataset is used to detect the credit card fraud detection. This is a classification problem. This is an imbalanced dataset based on target variable. So In this Project, I will use encoding and decording techniques to balanced dataset.

These are various techniques as follows -
 - 1. Cross Validation Like KFOLD and Hyperparameter Tuning (Logistics Regression )
 - 2. Ensemble Technique - Random Forest
 - 3. Under Sampling
 - 4. Over Sampling
 - 5. SMOTETomek
 - 6. Ensemple Technique - EasyEnsembleClassifier


# Libraries 

1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. sklearn
6. ibmlearn


# Commands

pip install imblearn

or 

pip install imbalanced-learn

# Dataset 

You have to download Credit Card Fraud Detection Dataset (CSV File) from Kaggle.

https://www.kaggle.com/mlg-ulb/creditcardfraud
