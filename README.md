# Optimizer-Performance-on-Non-Convex-Functions
Optimise different functions using different optimisers.


1. Non-Convex Function Optimization
a. Optimize the following functions:
i. f (x, y) = (1 - x) ^2 + 100(y - x^2)^2
ii. f(x) = sin(1/x)

Handle (x = 0 ) by setting ( f(0) = 0 ) or slightly exceeding zero.

b. Apply the following optimizers at Learning rate ((alpha)): 0.01, 0.05, 0.1:
● - Gradient Descent
● - Stochastic Gradient Descent with momentum
● - Adam
● - RMSprop
● - Adagrad

Presentation of results:
a) Convergence behaviour for each optimizer and time taken by
each optimizer.
b) Impact of hyperparameters on convergence speed and the final result,
with plots showing convergence.
