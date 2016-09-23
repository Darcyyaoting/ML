# ML

1 Many ML algorithms such as linear regression,logistic regression, neural network use loss function or some optimization objective as their estimation.
And they use gradient descent(batch gradient descent) to reach the minimum of loss function.
However, when it comes to big data, the gradient descent doesn't work due to the heavy calculation.
So we can instead use stochastic gradient descent
(1) Randomly shuffle dateset
(2 for every single sample training set, we optimize the loss function instead of looping all the training dataset
