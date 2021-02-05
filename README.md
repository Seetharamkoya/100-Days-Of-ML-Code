![github-small](https://camo.githubusercontent.com/bd3ac351e28b6e6d6a5dbe73fc4d6f49c87fe713e73f3a582ddfcc74633e2e39/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d507974686f6e2d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d707974686f6e266c6f676f436f6c6f723d776869746526636f6c6f723d333737364142)
![github-small](https://camo.githubusercontent.com/aa7054917c7c8fe73c9b61cdb674f7412c9c423d0aebf02ca478453ca7f0959b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50616e6461732d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d70616e646173266c6f676f436f6c6f723d776869746526636f6c6f723d313530343538)
![github-small](https://camo.githubusercontent.com/def6624f7f52d3909e8e858b934f994c85e7b45e5f82667cd1137690064e961f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e756d50792d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d6e756d7079266c6f676f436f6c6f723d776869746526636f6c6f723d303133323433)
![github-small](https://camo.githubusercontent.com/9fe7d0c5bc695009af51786bfd406ca73f7b371cb678ee668804b086569cf6a4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f53636950792d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d7363697079266c6f676f436f6c6f723d776869746526636f6c6f723d384341414536)
![github-small](https://camo.githubusercontent.com/b13a12c010ff1051c318e7ca156e0f3b827a667b59886e89fd4aba2f53d6f507/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5363696b69744c6561726e2d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d7363696b69742d6c6561726e266c6f676f436f6c6f723d776869746526636f6c6f723d463739333145)
![github-small](https://camo.githubusercontent.com/faefc02a56789ea753692fdbbab144c3ac8f6dc0747cefcc92acb588f407a298/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f54656e736f72466c6f772d696e666f726d6174696f6e616c3f7374796c653d666c6174266c6f676f3d54656e736f72466c6f77266c6f676f436f6c6f723d776869746526636f6c6f723d464636463030)
## supervised learning:  regression and classification
Regression predicts a **continuous target variable Y**\
Y = f(X) + ε, where X = (x1, x2…xn)\
Training: machine learns f from labeled training data\
Test: machine predicts Y from unlabeled testing data\
## **Supervised learning algorithms:**


## SIMPLE LINEAR REGRESSION [Code](https://github.com/Seetharamkoya/100-Days-Of-ML-Code/blob/master/simple_Linear%20Regression.ipynb)
Linear regression is a parametric method, Predicting a response using a single feature.
It is a method to predict dependent variable (Y) based on values of independent variable (X). It is assumed that that the two variable aren linearly related. Hence, we try to find a linear function that predicts the response value(Y) as  accuractely as possible as a function of the feature or independent variable(X).

![github-small](https://madhureshkumar.files.wordpress.com/2015/07/regressioncurv.png?w=705)

In this regressionmodel, we are trying to minimize the erros in the prediction by finding the "line of best fit"  - the regression line from the errors would be minimal. we are trying to minimize the length between the observed value (Yi) and the predicted value from our model (Yp).

Squared loss (L2 loss) =  the square of the difference between the label and the prediction\
                       = (observation - prediction(X))2\
                       = (Yi - Yp)2
                          
Mean square error (MSE) = 1/N sum((Yi - Yp)2)\
![github-small](https://spin.atomicobject.com/wp-content/uploads/linear_regression_error1.png)



### Reducing the loss - An Iterative Approach
![github-small](https://developers.google.com/machine-learning/crash-course/images/GradientDescentDiagram.svg)

The "model" takes the one or more features as input and returns one predictions(Yp) as output. To "Compute Loss" part of the model we will use two input values.
- Yp The model's prediction for features x
- Y The correct label corresponding to features x.
### Gradient Descent
The Gradient is a vector which gas both magnitude and direction. The first stage in gradient descent is to pick a staring value for(m/slope/weight(wi)) and it could be a random value or zero. The gradient descent algorithm takes a step in the direction of the negative gradient in order to reduce loss as quickly as possible. Gradient descent algorithms multiply the gradient by a scalar known as a **learning rate**(step size) to determine the next point.

![github-small](https://developers.google.com/machine-learning/crash-course/images/GradientDescentNegativeGradient.svg)

**Hyperparameters** are the parameters whose value is to control the learning process and it has no influence on the performance of the model but effects the speed and quality of the learning process(too small and too large step size).

![github-small](https://spin.atomicobject.com/wp-content/uploads/linear_regression_gradient1.png)







https://adit.io/posts/2016-02-20-Linear-Regression-in-Pictures.html#gradient-descent
