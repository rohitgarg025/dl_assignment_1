# Deep Learning [CS F425] Assignment 1

## Submitted by :
* Somesh Singh [2018A7PS0175G]
* Rohit Garg [2018A7PS0193G]
* Aditya Mishra [2018A7PS0117G]

## Dependencies:
* Python 
* PyTorch
* Tensorboard
* Notebook Environment
* Numpy
* Pandas
* Sci-kit Learn
* Matplotlib

## MLP
We trained multi-layer perceptron (MLP) model on CIFAR and MNIST dataset. On increasing the number of layers, we observed the following issues:

* __Degradation Problem__ : As the depth of the network increased, we observed a decline in training accuracy and increase in loss.
* __Vanishing and Exploding Gradients problem__ : Means that gradients of loss become more and more muted in the beginning layers of a network as the network become increasingly deeper.
* __Non-convexity of loss surface with chaotic behaviour__. <br>
--> Clearly, increasing the number of layers did not lead to expected phenomenon of overfitting.

## Why Skip Connections?
* We overcame the short-comings of MLP network by use of Skip connections or shortcut connections.
* It was observed that Skip connections improved both train ing and test accuracy and loss.
* Even with more number of layers skip connections were able to converge better.
* Thus, skip connections improved helped us solve degradation problem and in feature reusability.

