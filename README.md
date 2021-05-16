# Linear-Regression

Linear regression is a linear model, e.g. a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, that y can be calculated from a linear combination of the input variables (x). <br />

In this analysis, 100 random input samples have been considered with value less than 1. <br />
A function, here, y = 3x has been considered and some randomness has been added to it. <br />
Straight lines are of the form, y = mx + c.  <br />
Here, we consider m to be the weights and c to be the bias added.  <br />
Therefore, we can say, y = wx + b. <br />

y = [w,b] . [x,1]<sup>T

Here, we create a new variable x_dash = [x,1]

The bias added is 1 here. <br />

The cost here is mean squared error.  <br />
Cost = Sum (y(predicted) - y(actual))<sup>2   <br />
  
= Sum (wTx - y(actual))<sup>2  
  
Residuals = wTx - y(actual)
Gradient vector = x * (Residuals)

w(t+1) = w(t) - (Learning Rate) * (Gradient vector)

The code has been run for 100 epochs with a learning rate of 0.01.
