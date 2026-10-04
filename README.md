# Neural Network From Scratch

A two-layer feedforward neural network built in NumPy, with no ML frameworks, that classifies handwritten digits from MNIST.

## Overview

- **Architecture:** 784 inputs, 10 ReLU hidden units, 10 softmax outputs
- **Implemented by hand:** one-hot label encoding, backpropagation, and gradient descent, with no library calls for any of them
- **Training:** 42,000 images, with 1,000 held out for evaluation
- **Result:** about 89% training accuracy after 500 iterations at a learning rate of 0.1

## Files

- `neural-network-from-scratch.ipynb`: the full implementation and training run
- `AI.pdf`: reference material

## Running it

Open the notebook in Jupyter and run the cells in order. It needs `numpy`, `pandas`, and `matplotlib`, plus the MNIST `train.csv` (Kaggle's Digit Recognizer format). The notebook reads it from a Kaggle path, so update the `pd.read_csv` path if you run it elsewhere.
