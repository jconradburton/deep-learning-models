# Deep Learning Models
DNN, CNN, and RNN models created for assignments in Deep Learning class from Ben Gurion University of the Negev taught by Dr. Gilad Katz.

## 1. Dense Neural Network Model

The goal of this assignment was to build a deep neural network from scratch, explicitly writing the forward and backpropagation processes without the use of libraries from softwares such as Pytorch. We implemented an L-layer network with ReLU as the activation function and softmax on the last layer. We then trained three different models, each with 4 hidden layers with sizes 20, 7, 5, 10. We used a learning rate of 0.009 and early stopping criterion of 100 training steps with less than 0.00001 improvement on the validation cost.

1. The above model with a batch size of 512.
   a. Train Accuracy: 0.9401041666666666
   b. Validation Accuracy: 0.937
   c. Test Accuracy: 0.9309
  
2. The above model with the addition of batchnorm and a batch size of 256
   a. Train Accuracy: 0.9312916666666666
   b. Validation Accuracy: 0.9345
   c. Test Accuracy: 0.9192

3. The above model without batchnorm and now with L2 regularization with epsilon = 0.4
   a. Train Accuracy: 0.9511875
   b. Validation Accuracy: 0.95175
   c. Test Accuracy: 0.941


## 2. Convolutional Neural Network



## 3. Recurrant Neural Network
