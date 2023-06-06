# Model Selection and Performance Optimization in Linear Regression - An exploration of architectures

The purpose of this notebook is to experiment with various architectures of a linear regression model in order to select the best model for a given task. By exploring different architectural choices, we aim to gain insights into improving model performance.

## Objective
The goal of this notebook is to provide intuition on what to try next when encountering specific performance issues with the model. We will conduct experiments with different architectural aspects of the model to observe their effects on cross-validation error and training error. Specifically, we will examine the error as a function of:

- Degree of Polynomials
- Regularization parameter (lambda)
- Number of Training Examples

By conducting these experiments, we aim to identify a subset of models that demonstrate superior performance.

## Bias-Variance Analysis
In addition to the architectural exploration, we will also analyze whether the current model suffers from a bias or variance problem. Based on the outcome of this diagnostic, we will adjust the model accordingly, striving to achieve a better model with lower cross-validation error and training error.

## Debugging and Insights
By going through this notebook, you will gain insights into various methods for debugging a learning algorithm. The content closely follows my thought process throughout the exploration and analysis.

## Implementation Details
- Linear regression will be utilized for its simplicity.
- The `sklearn` library will be extensively used to simplify the code further.
- The primary focus is not on understanding the linear regression algorithm itself, but rather on comprehending how the model's architecture can impact its performance.

## Acknowledgement
I am immensely grateful for the invaluable knowledge I have gained from Andrew Ng's course, "Advanced Learning Algorithms," which is part of the "Machine Learning Specialization" on Coursera. To emphasize certain points, I have included a few screenshots from the lectures in this notebook.
