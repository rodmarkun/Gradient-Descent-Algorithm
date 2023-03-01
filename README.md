# Gradient descent algorithm

**Gradient descent** is an iterative optimization algorithm used to find the local minimum of a function. It is widely used in machine learning and deep learning to minimize the cost function or loss function.

The idea behind gradient descent is to move in the direction of the steepest descent of the cost function to reach the local minimum. In other words, it tries to find the best set of parameters for a machine learning model that minimize the error between predicted values and the actual values.

The algorithm starts with an initial set of parameters and calculates the derivative of the cost function with respect to each parameter. Then, it updates the parameters in the opposite direction of the derivative, multiplied by a learning rate alpha, which determines the step size at each iteration.

The algorithm repeats the process until **convergence**, where the cost function does not significantly change between iterations or reaches a predefined number of iterations.

![Pasted image 20230301172457](https://user-images.githubusercontent.com/75074498/222212590-83b2b44b-2424-461e-bde4-d742730cede9.png)

There are two types of gradient descent algorithms: batch gradient descent and stochastic gradient descent. Batch gradient descent calculates the derivative of the cost function over the entire training dataset at each iteration, while stochastic gradient descent calculates the derivative for a randomly training data at each iteration.

## Advantages & Disadvantages of Gradient Descent Algorithm

Advantages of Gradient Descent:

-   It is a widely used and efficient optimization algorithm that can be used in various types of machine learning problems.
-   It allows for the optimization of complex models with many parameters.

Disadvantages of Gradient Descent:

-   The algorithm may converge to a local minimum instead of the global minimum, depending on the choice of learning rate and initial parameters.
-   The algorithm may be slow to converge if the learning rate is too small or may overshoot the minimum if the learning rate is too large. Finding the optimal learning rate can be a challenging task.

## How to run this project

You can run this project with **Jupyter Notebook** or any software that supports .pynb files. If you have Python installed, you can install Jupyter Notebook with the following command:

```python
pip install jupyter
```

After installing Jupyter, clone this repo and run the following command in the resulting folder:

```python
jupyter notebook
```

Then select the corresponding file in the interface and run all cells.
