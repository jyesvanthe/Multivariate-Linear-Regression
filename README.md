# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd

### Step2
Read the csv file

### Step3
Get the values of X and Y variables

### Step4
Create the linera regression model and fit

### Step5
Predict the CO2 emission of a car wher4e the weight is 3300kg,and the volume is 1300cm^3

## Program:
```
import pandas as pd.

from sklearn import linear_model df-pd.read csv("cars.csv")
x=df[['Weight', 'Volume']]
y=df['CO2'] regr-linear_model.LinearRegression()
regr.fit(x,y) print("Coefficient:",regr.coef_)
print("Intercept;", regr.intercept) predictedC02-regr.predict([[3300,1300]])
print("Predicted Co for the corresponding weight and volume", predictedCO2)
```
## Output:

![Alt text](<Screenshot 2024-01-02 030650.png>)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.