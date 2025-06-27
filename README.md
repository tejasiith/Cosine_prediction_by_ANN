# Cosine Value Prediction using Artificial Neural Network (ANN)

This project demonstrates how a simple Artificial Neural Network (ANN) can be trained to learn and predict the values of the cosine function. It serves as an introductory application of deep learning in function approximation using PyTorch.

## Objective

To build a feed-forward neural network that learns the cosine function `cos(x)` over a specified range of input values and generalizes well to unseen data points.

## Model Details

- **Input**: Scalar `x` value
- **Output**: Cosine value `cos(x)`
- **Architecture**:
  - Input layer: 1 neuron
  - Hidden layers: 2 hidden layers with 32 neurons each
  - Activation: `ReLU` or `Tanh`
  - Output layer: 1 neuron
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- **Epochs**: 1000 (or as tuned)
- **Framework**: PyTorch

## Dataset

- Generated using: `x ∈ [0, 2π]`
- `y = cos(x)` computed using NumPy
- Data is split into training and test sets

## Results

- The trained model accurately predicts cosine values.
- Low MSE on both training and testing data.
- Smooth curve fitting is observed when compared to the actual `cos(x)` function.

## Usage

To run the notebook:

```bash
pip install torch matplotlib numpy
