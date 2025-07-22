# MNIST Neural Network Using Numpy
A minimalistic implementation of a 2-layer neural network built entirely from scratch using NumPy to classify handwritten digits from the MNIST dataset.
It classifies handwritten digits from the MNIST dataset and achieves **~86% accuracy** without using any machine learning libraries like TensorFlow or PyTorch.

---

## Features

- Feedforward neural network with manual backpropagation
- ReLU activation in the hidden layer
- Softmax activation in the output layer
- One-hot encoding for labels
- Trains using gradient descent
- Written entirely with NumPy

---

## Model Architecture

- Input Layer: 784 neurons (28x28 pixels)
- Hidden Layer: 10 neurons (ReLU)
- Output Layer: 10 neurons (Softmax)

---

## Sample Output

Trained over 500 iterations on normalized MNIST CSV:

Iteration:  0
Accuracy: 0.06333333333333334

Iteration:  1
Accuracy: 0.060444444444444446

Iteration:  2
Accuracy: 0.060333333333333336

Iteration:  3
Accuracy: 0.065

.
.
.

Iteration:  497
Accuracy: 0.859

Iteration:  498
Accuracy: 0.859

Iteration:  499
Accuracy: 0.859222222222222

Final Accuracy: ~85.9%

---

 ## Dataset
 
This project uses the MNIST CSV version from Kaggle

---

 ## Why Build from Scratch?
 
- Building your own neural network manually helps reinforce core ML concepts like:
- How weights and biases are updated during training
- The intuition behind ReLU and softmax
- Why data normalization matters
- What gradients and the chain rule really do
