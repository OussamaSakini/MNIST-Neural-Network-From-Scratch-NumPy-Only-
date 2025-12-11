# MNIST-Neural-Network-From-Scratch (NumPy Only)

This mini-project implements a fully-connected neural network from scratch using only NumPy.
No TensorFlow, no PyTorch just pure linear algebra and backpropagation.

**Objective :**
The goal is to classify handwritten digits (0–9) from the MNIST dataset.

**Features :**
Manual implementation of:
- Forward propagation
- ReLU activation
- Softmax output layer
- Cross-entropy loss
- Backpropagation
- He & Xavier initialization
- Gradient descent updates
Accuracy up to 87% on validation set
Image prediction + visualization
Dataset preprocessing (train/validation split)

**Model architecture :**
1- Input: 784 pixels (28×28 flattened)
2- Hidden layer: 128 neurons (ReLU)
3- Output layer: 10 neurons (Softmax)

784 → 128 → 10

**How to run :**
1- Place train.csv and test.csv inside /dataset
2- Install dependencies: pip install numpy pandas matplotlib
3- Run the notebook:Image_Recognation_NN_from_Scratch.ipynb
