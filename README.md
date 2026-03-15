# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

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
file:///C:/Users/acer/AppData/Local/Packages/5319275A.WhatsAppDesktop_cv1g1gvanyjgm/LocalState/sessions/B8B55370ACE5F2644131C2EC26CA0427C3FE6ADF/transfers/2026-11/MATH%20FOR%20AI%20JUP%20-2.pdf

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
