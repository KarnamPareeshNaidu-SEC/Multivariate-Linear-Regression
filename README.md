# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import necessary Python libraries such as numpy, pandas, and sklearn
### Step2

Separate independent variables (features 
𝑋
X) and dependent variable (target 
𝑦
y)
### Step3
Divide the dataset into training and testing sets using train_test_split().

### Step4

Create a Linear Regression model using LinearRegression().
### Step5

Compare predicted values with actual values to evaluate performance.
## Program:
```

# Developed by:KARNAM PAREESH  NAIDU
# Reg no: 212225230129

import pandas as pd
from sklearn import linear_model

df = pd.read_csv("c:/carmath.csv")
X = df[['Weight', 'Volume']]
y = df['CO2']

regr = linear_model.LinearRegression()
regr.fit(X, y)
print('Coefficients:', regr.coef_)
print('Intercept:',regr.intercept_)

predictedCO2 = regr.predict([[3300, 1300]])
print('Predicted CO2 for the corresponding weight and volume',predictedCO2)


```
## Output:
<img width="833" height="211" alt="image" src="https://github.com/user-attachments/assets/04bcb094-bab4-4c0f-9c22-013348786409" />



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
