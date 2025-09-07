# Implement-Gradient-Descent-for-Linear-Regression
#700772575
# Nithin Gundapu

# Description : 
This assignment focuses on implementing linear regression using two different approaches: the closed-form solution (Normal Equation) and gradient descent. The goal was to compare both methods and understand how they perform on a synthetic dataset.

# Dataset :
I generated 200 data points using the equation: y = 3 + 4x + ,E where E is Gaussian noise and x is randomly sampled from the range [0, 5].

# Implementation
For the closed-form solution, I used matrix operations to directly calculate the optimal parameters.
For gradient descent, I started with initial values of [0, 0], used a learning rate of 0.05, and ran the algorithm for 1000 iterations.
I tracked the mean squared error (MSE) during training and plotted the loss curve to visualize convergence.

# Results
Both methods produced very similar results for the intercept and slope, confirming that gradient descent successfully converged to the same solution as the closed-form method. The loss curve showed smooth and consistent improvement over time.
