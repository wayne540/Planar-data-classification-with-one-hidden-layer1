---

# Planar Data Classification with One Hidden Layer

## Overview

This project implements a **simple neural network with one hidden layer** to classify planar datasets. It’s a hands-on implementation from scratch in **Python**, using only **NumPy** for matrix operations and **Matplotlib** for visualization.

The goal is to understand how forward propagation, backpropagation, and gradient descent work in practice, and to see how a neural network can separate non-linearly separable data.

---

## Features

* One hidden layer neural network
* Activation functions:

  * **tanh** for hidden layer
  * **sigmoid** for output layer
* Forward and backward propagation implemented from scratch
* Gradient descent optimization
* Cost function (cross-entropy)
* Visualization of the decision boundary

---

## Project Structure

```
Planar-data-classification-with-one-hidden-layer/
├── attempt4.ipynb        # Main notebook with network implementation
├── planar_utils.py       # Utility functions for dataset handling and plotting
├── testCases.py          # Test cases for verifying function correctness
└── README.md             # Project description and instructions
```

---

## Getting Started

### Prerequisites

* Python 3.x
* NumPy
* Matplotlib
* Jupyter Notebook (optional, for running the `.ipynb`)

You can install dependencies via pip:

```bash
pip install numpy matplotlib jupyter
```

### Running the Project

1. Open `attempt4.ipynb` in Jupyter Notebook or VS Code.
2. Execute the cells step by step to train the neural network and see the results.
3. Observe the cost decreasing and the network’s decision boundary on the planar dataset.

### Optional: Running as Script

If you export the notebook as a Python script (`.py`), you can run:

```bash
python attempt4.py
```

---

## How It Works

1. **Layer Sizes:** Determine input, hidden, and output layer sizes.
2. **Parameter Initialization:** Randomly initialize weights and biases.
3. **Forward Propagation:** Compute activations using `tanh` and `sigmoid`.
4. **Cost Computation:** Compute cross-entropy cost for binary classification.
5. **Backpropagation:** Compute gradients for weights and biases.
6. **Parameter Update:** Apply gradient descent with learning rate.
7. **Iteration:** Repeat forward/backward propagation for a number of iterations until convergence.

---

## Results

* The model successfully classifies non-linearly separable planar datasets.
* Cost decreases smoothly over iterations.
* Learned weights remain in reasonable ranges (no exploding values).
* Decision boundary is visualized via Matplotlib.

---

## References

* Andrew Ng, *Deep Learning Specialization*
* Python NumPy and Matplotlib documentation

---
