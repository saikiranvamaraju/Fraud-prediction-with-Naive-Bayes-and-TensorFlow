# Fraud-prediction-with-various-algorithms(Naive Bayes, Logistic regression, SVM's)
Binary classification of fraudulent data with imbalanced class problem

Background
------------------------------------------------------------------------------------------------------------------------------------------
The dataset was obtained from Kaggle(https://www.kaggle.com/mlg-ulb/creditcardfraud/data). The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation.  due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Approach & Goal
------------------------------------------------------------------------------------------------------------------------------------------
Given the class imbalance ratio, measured accuracy using metrics like precision, recall, AUC since Confusion matrix accuracy is not meaningful for unbalanced classification. Finally, improve the model’s fraud detection rate using various algorithms
