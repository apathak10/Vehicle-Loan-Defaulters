# Vehicle-Loan-Defaulters

Objective: To find best model which fits dataset of vehicle loan defaulter in first installment (EMI)

Source: https://www.kaggle.com/lampubhutia/loandefault-ltfs-avml-finhack#train_LTFS.csv

Installation: Download "train_LTFS.csv" file from Source link and import this csv file into .ipynb script

Summary of Project:
- Applied Logistic Regression, Decision Tree, Random Forest and XGBoost to find model which best fits this classification problem
- Rectified the issue of class imbalance by under-sampling to show correct accuracy of 73%, instead of 78%
- Performed Feature Engineering and removed Multicollinearity to remove insignificant features from 41 variables
- Cleaned dataset of 0.23 million entries by appropriate measures after doing EDA by Matplotlib and Seaborn libraries

Application: Once all the data of new customer is entered, XGBoost Model detects with an accuracy of 77% that whether customer is going to pay back the loan or not. As the sanctioning the loan takes more time, therefore this model can act as a quick measure to speed up the process.
