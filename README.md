# Celsius-to-Fahrenheit
simple NN using numpy only

We know the true linear relationship between Celsius to Fahrenheit is 1.8 * C + 32 = F

I made a simple neural net to approximate this relation using Kaggle's Celsius to Fahrenheit dataset

Model structure is a scalar weight W and bias b

Forward pass -> W * C + b = F_pred

Mean squared error loss function

Back propogation from the partial derivatives of the MSE w.r.t. W and b

Update with learning hyperparameter alpha = 0.01
