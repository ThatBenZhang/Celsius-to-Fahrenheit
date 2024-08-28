# Celsius-to-Fahrenheit
simple NN using numpy only

We know the true linear relationship between Celsius to Fahrenheit is 1.8 * C + 32 = F

I made a simple neural net to approximate this relation using Kaggle's Celsius to Fahrenheit dataset

Model structure is a scalar weight W and bias b

Forward pass -> W * C + b = F_pred

Mean squared error loss function

Back propogation from the partial derivatives of the MSE w.r.t. W and b

Update with learning hyperparameter alpha = 0.01

Note: z-score normalization was applied to values of Celsius and Fahrenheit to account for numerical instability issues, therefore W and b have to be "de-normalized" at the end of traing to produced the expected output of W = 1.8 and C = 32
