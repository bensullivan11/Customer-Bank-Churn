# Customer-Bank-Churn
This project provides a possible solution to help mitigate loses incurred by banks from annual customer churn.

## Data
The data set, provided by kaggle, contains 8 attributes on over 2000 bank customers along with the associated target vairable of whether the customer exited the bank or not.

## Modeling
8 different classification models were trained on the customer attributes and churn outcome to predict the probability of a customer leaving the bank on a test set.  

These models were additionally trianed with undersampling and oversampling techniques to enhance perfomance on the unbalanced data set.

## Application
Using the customer churn probability predictions from the best model, potential increase in profits were examined when extending a targeted promotion to customers with the highest chance of exiting the bank.
