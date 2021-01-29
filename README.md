# Seetharamkoya-100-Days-Of-ML-Code
# Data Prepocessing






# SIMPLE LINEAR REGRESSION [Code](https://github.com/Seetharamkoya/100-Days-Of-ML-Code/blob/master/simple_Linear%20Regression.ipynb)
Predicting a response using a single feature.
It is a method to predict dependent variable (Y) based on values of independent variable (X). It is assumed that that the two variable aren linearly related. Hence, we try to find a linear function that predicts the response value(Y) as  accuractely as possible as a function of the feature or independent variable(X).

![github-small](https://www.skysilk.com/blog/wp-content/uploads/2018/09/SimpleLinearRegressionEquation.jpg)

In this regressionmodel, we are trying to minimize the erros in the prediction by finding the "line of best fit"  - the regression line from the errors would be minimal. we are trying to minimize the length between the observed value (Yi) and the predicted value from our model (Yp).

Squared loss (L2 loss) =  the square of the difference between the label and the prediction\
                       = (observation - prediction(X))2\
                       = (Yi - Yp)2
                          
Mean square error (MSE) = 1/N sum((Yi - Yp)2)

### Reducing the loss - An Iterative Approach
![github-small](https://developers.google.com/machine-learning/crash-course/images/GradientDescentDiagram.svg)

The "model" takes the one or more features as input and returns one predictions(Yp) as output. To "Compute Loss" part of the model we will use two input values.
- Yp The model's prediction for features x
- Y The correct label corresponding to features x.
### Gradient Descent
The Gradient is a vector which gas both magnitude and direction. The first stage in gradient descent is to pick a staring value for(m/slope/weight(wi)) and it could be a random value or zero. The gradient descent algorithm takes a step in the direction of the negative gradient in order to reduce loss as quickly as possible. Gradient descent algorithms multiply the gradient by a scalar known as a learning rate(step size) to determine the next point.

![github-small](https://developers.google.com/machine-learning/crash-course/images/GradientDescentNegativeGradient.svg)




