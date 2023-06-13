# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas.
### Step2
Import linear model from sklearn.
### Step3
Read the files cars.csv.
### Step4
Assign he values for x and y as requried.
### Step5
Create the LinearRegression model and predic he output.
## Program:
```
Developed by: N SWETHA
Register No: 212222110050
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))
```
## Output:
![image](https://github.com/Swetha733N/Multivariate-Linear-Regression/assets/122199934/d178cd93-1ccd-49b1-8092-3ee61eafd7dd)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
