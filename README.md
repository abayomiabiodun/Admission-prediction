# Admission-prediction
Prediction of admission based on some score to determine the chance of admission
#Some dependency needed for this project
### Pandas
### seaborn
### matplotlib
## These dependency can be import as follows

import pandas as pd import seaborn as sns import matplotlib.pyplot as plt from sklearn import linear_model 

Importing of the dataset needed for this 




The column that has the Serial No. has less important in the dataset that is the reason of dropping its column from the table



showing the Linear Regression with GRE Score, TOEFL Score, CGPA, all in comparison of Chance of Admission in the seaborn visualization below


(1) The greater the Gre Score the higher the chance of admission

(2) The greater the TOEFL Score the higher the chance of admission

(3) The greater the CGPA the higher the chance of admission

GRE Score, TOEFL Score, CGPA are preferrably used for our x because those columns has the highest correlated values and are dependent variables

Chance of Admit(i.e Chance of admission) in the given dataset is our indepent variable and is what we are trying to predict which is our output

Building of machine learning model of Linear Regression

0.04688621359385712 

The error is okay for the model









