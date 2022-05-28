# Statistics

I will share some notebooks about statistics here. Some could be general concepts and fundamentals. Some related to projects for example DNA sequencing.
Please contact if you had questions.

## Bias Variance Trade-off
This notebook gives shows the the general trade-off relation between bias and variance by giving a numerical example. Please feel free to change the function to something else if you like. 
Following this example, we can understand why when we are increasing models order to minimize the bias, we may be overfitting - this can be observed as the variance is increased, meaning that the model may not fit in general cases (with other data). We can also note that there is a a optimal point for the order, where MSE is minimized. Please note that this is a simple example and in large complicated NN models we may not be able to find an absolute minimum. That is why regularization techniques are very important to avoid overfitting. Other notebooks will discuss the regularization.
