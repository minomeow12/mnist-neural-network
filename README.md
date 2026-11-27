# mnist-neural-network

A neural network built using Python and NumPy to recognize handwritten digits.

# MNIST Handwritten Digit Recognition

## About the Project

This project uses a neural network built from scratch with Python and NumPy to recognize handwritten numbers (0–9) from the MNIST dataset.

The goal is to understand how neural networks learn and how different settings affect their accuracy.

## Tools Used

- Python
- NumPy
- Pandas
- Matplotlib

## How It Works

1. Loads handwritten digit images from the MNIST dataset.
2. Converts pixel values into numbers between 0 and 1.
3. Trains a neural network using backpropagation.
4. Tests how well the network recognizes digits.
5. Creates graphs and confusion matrices to show the results.

## Experiments

I tested three things:

1. **Hidden Neurons:** How the number of neurons affects accuracy.
2. **Momentum:** How different momentum values affect training.
3. **Training Data Size:** How using more or less training data affects accuracy.

## Results

- Best test accuracy: **97.96%**
- More hidden neurons generally improved accuracy.
- Lower momentum values worked better in these tests.
- Using more training data helped the model recognize digits better.

## How to Run

1. Install the required libraries:

```bash
pip install numpy pandas matplotlib
```

2. Download `mnist_train.csv` and `mnist_test.csv` and place them in the project folder.

3. Run the Python file:

```bash
python mnist-neural-network.py
```

4. Choose experiment 1, 2, or 3.

## What I Learned

Through this project, I learned how to build and train a neural network without using machine learning frameworks like TensorFlow or PyTorch. I also learned how changing network settings affects accuracy and performance.

## Project Report

The full report includes experiment results, graphs, confusion matrices, and explanations.
