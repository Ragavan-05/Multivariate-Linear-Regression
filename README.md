# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step 1:
Import required libraries and load the dataset.
Step 2:
Define the feature matrix � and target vector �.
Step 3:
Split the dataset into training and testing sets.
Step 4:
Create a Linear Regression model and train it using training data.
Step 5:
Predict outputs, evaluate the model, and plot the residual errors.

## Program:
```py
imprt matplotlib pwplot is plt
import oumpy as tp
from sklearm import dataset's, linear _madel, metrics
# lond the hostog datnset
bostan = datisets lond bosltomytelun.X y-false)# befininy feature matris(X) and trespuontse vector(y)X- boston dotl
y= boson target
# splitting X and y into training und iesting sets
ffom silern moded scleston imoort tnin tet selit
X tmin, X test, y_ tain, y_test w train test split(x, s, test sie=0,.4.
andom stite=l)
# create lineur rewresing obieet
teg = lirxea_madel L.inearRegression)# train the model using the traiting sels reg fitrX train, y train)
f regressiom coefficients
pmint(Coefliciernts: ', rog auvef.)
# variance oore: I mcans perfect prcediction
prinml'Variance score: ' format(creg.score( X test, y. test))
# plot for residuul eror
## setting plot style
plt stvle user'fivethirtveizh)
# ploting residual eros in training data
pltscatter(reg predictiX_truin), reg predJict(X train)-y. tmin, 
colar - "green', s= 10, lakel -'Iain daa)
# plotting residual erors in test data
plt.scatterfreg predict_iest), reg predict(X_test)-y_test, 
colar = "blue",5= 10. labe/ -'Test cdata)
mpotinr line foe zero resialuual erut
plt hlines y = l, xmin =D, xmax = 50, linewidth = 2)
i# plotting lezend
plt legend lox = 'upper ripht')
## plot title
plt. titler" Residual errots”)
## method call for showing the plot
plt.show)

```
## Output:

<img width="793" height="605" alt="Screenshot 2025-12-27 132248" src="https://github.com/user-attachments/assets/48b63175-c207-4af9-bc72-cb88763a2465" />

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
