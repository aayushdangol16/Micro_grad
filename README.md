# Micrograd for Linear Regression

This project involves creating a micrograd framework capable of computing gradients for various operations, including:

- Addition (`add`)
- Subtraction (`sub`)
- Multiplication (`mul`)
- Mean (`mean`)
- Power (`pow`)
- Matrix Multiplication (`matmul`)

The framework is designed to solve a linear regression problem while incorporating the following steps:

## Features

1. **Gradient Computation**  
   Implemented custom backward functions to compute gradients for all operations listed above.

2. **Comparison with Autograd**  
   Compared the gradients computed using the micrograd framework with PyTorch's `autograd` gradients to validate correctness.

3. **Training on Housing Dataset**  
   Trained a linear regression model on the housing dataset using:
   - Micrograd's custom backward function for gradient computation
   - A manually implemented optimization loop to update model parameters
