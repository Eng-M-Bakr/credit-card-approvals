# credit-card-approvals
Our data is talking about credit cards approval, many banks spend a lot of time in order to take a decision either approving the credit card for a customer or not.
Some parameters affect this decision like gender, Age, Debt, Married, Bank Customer, Education Level, Ethnicity, Years Employed, Prior Default, Employed, Credit Score, Driver's License, Citizen and Income.
We are going to inspect the data, our target is to implement a machine learning code which helps in taking the decision programmatically in order to save time.
Before implementing the machine learning models and choose which model giving the best accuracy, we have to inspect the data, clean the data without losing its consistency then preprocess the data to be used for the machine learning models.
We have independent variables which was numbered from A1 to A15 and the dependent variable is A16 which is approved or not.
Presence of a dependent variable with zero or one forced us to use classification
Models of machine learning.
In order to enhance our project we used grid search for each model to get the best parameters that should be used as arguments for the model to give the best accuracy.
Finally we used Ensembling as a try to get better and better accuracy for the model.
Our code was implemented in the sequence of:
1- Loading data
2- Inspecting data
3- Cleaning data
4- Preprocessing of data
5- Machine learning models:
 Logistic regression
 Decision tree
 Random forest
 K nearest neighbors
6- Hyperparameters tuning (grid search) for each model
7- Ensembling:
 Voting ensemble
 Average ensemble
