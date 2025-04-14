# Deep Learning – Homework Assignments  
**Ben-Gurion University of the Negev – Department of Software and Information Systems Engineering**  
**Course: Deep Learning**

## Overview  
This repository contains my solutions and experiments for the course assignments in Deep Learning. Each assignment explores a key building block of deep learning—from constructing a dense neural network from scratch to implementing advanced models like Siamese networks and Recurrent Neural Networks.

---

## Repository Structure

- `hw1/`  
  - `Dense_Neural_Network_From_Scratch.ipynb`  
    Implements a deep fully connected network (DNN) with forward and backward propagation, trained and evaluated on the MNIST dataset.  
    Includes support for batch normalization, L2 regularization, and training without external libraries like PyTorch or TensorFlow.

- `hw2/`  
  - TBD

- `hw3/`  
  - TBD

- `hw4/`
  TBD

---

## Assignment 1 – Dense Neural Network from Scratch

### Goal
To build a complete dense neural network architecture, implementing both the **forward** and **backward** propagation steps manually. Train the model on MNIST and evaluate performance with and without batch normalization and L2 regularization.

### Implemented Features
- Forward Propagation
  - `initialize_parameters`, `linear_forward`, `relu`, `softmax`, `linear_activation_forward`
  - Batch normalization (`apply_batchnorm`)
  - Full model forward: `l_model_forward`

- Backward Propagation
  - `linear_backward`, `relu_backward`, `softmax_backward`
  - `linear_activation_backward`, `l_model_backward`
  - Support for L2 regularization

- Training & Evaluation
  - `compute_cost` with categorical cross-entropy
  - `update_parameters` using gradient descent
  - `l_layer_model` for training
  - `predict` for accuracy evaluation

### Experiments
- Trained on MNIST with 4 hidden layers: `[784 → 20 → 7 → 5 → 10]`
- Batch size, learning rate, and early stopping configurable
- Performance compared:
  - With vs. without batch normalization
  - With vs. without L2 regularization

---

## Upcoming Assignments

### Assignment 2 – Siamese Network with CNN
- Build a Siamese architecture for similarity tasks
- Use CNNs to learn an embedding space
- Train using contrastive or triplet loss
- Apply to image pairs (e.g., face or digit verification)

### Assignment 3 – Lyric Generator with RNN
- Build an RNN (likely LSTM or GRU) to generate sequences
- Train on a song lyric dataset
- Sample from the model to generate new lyrics

### Assignment 4 – TBD
- Description and notebook will be added when released

---
