# Gradient-Descent-Function
Performing Gradient Descent Function
Introduction
This repository contains code for a simple linear regression model implemented in Python using the gradient descent optimization algorithm. The model predicts the price of a car based on its features such as year, kilometers driven, engine size, and brand. The implementation includes data preprocessing, model training, and optimization using gradient descent.

Methods
Provided Code:
data: A dictionary containing sample data for car features and prices.
df: A Pandas DataFrame constructed from the provided data dictionary.
label_encoder: An instance of LabelEncoder used to encode the categorical variable "brand" into numerical values.
X_train and y_train: Features and target variable for training the model.
predict: Function to predict the target variable using linear regression.
compute_cost: Function to compute the mean squared error (MSE) cost function.
w_init and b_init: Initial weights and bias for the model.
Results
Initial Cost Calculation: The initial cost of the model with random weights and zero bias is computed using the provided compute_cost function.
Gradient Descent Implementation
Function: gradient_descent:
This function performs gradient descent optimization to update the weights and bias of the model iteratively.
It computes gradients using the entire training set and updates the parameters in the direction that minimizes the cost function.
The function takes input parameters such as learning rate (learning_rate), number of iterations (num_iterations), initial weights (w_init), and initial bias (b_init).
Cost is printed periodically to monitor the optimization process.
Discussion
The provided code sets up the data and basic components for a linear regression model.
The gradient descent implementation enhances the code by optimizing the model parameters to minimize the cost function.
Adjustments to hyperparameters such as learning rate and number of iterations may be necessary for optimal performance.
