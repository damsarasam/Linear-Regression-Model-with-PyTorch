## Linear Regression Model with PyTorch

This repository contains a Python script demonstrating the workflow for building and training a simple linear regression model using PyTorch. Linear regression is a fundamental supervised learning technique used for modeling the relationship between a dependent variable and one or more independent variables.

**Key Components:**

1. **Data Generation:** Synthetic data is generated to simulate a linear relationship between input and output variables.

2. **Data Splitting:** The generated data is split into training and testing sets to evaluate the model's performance.

3. **Model Definition:** A linear regression model is defined as a subclass of `nn.Module` in PyTorch, with learnable parameters for weight and bias.

4. **Model Training:** The defined model is trained using stochastic gradient descent (SGD) optimization, minimizing the L1 loss function.

5. **Model Evaluation:** The trained model's performance is evaluated on the test data, tracking the training and testing loss over epochs.

6. **Model Saving:** The trained model's state dictionary is saved to a specified file path for future use.

7. **Visualization:** The training and testing loss curves and the model's predictions are visualized to analyze performance.

**Usage:**

1. Ensure you have PyTorch and Matplotlib installed in your environment.
2. Run the Python script to generate synthetic data, train the linear regression model, and evaluate its performance.
3. Optionally, visualize the training and testing loss curves and compare the model's predictions against the actual test data.
