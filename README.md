## Neural Network

Why neural network? a single neuron only permits a linear decision boundary and not real-world problems are complicated

## Deep learning model summary

- Neural network model: multi-layer perceptron, feedforward networks
- Recurrent Neural Networks (RNN, LSTM): useful for modeling sequences (time series forecasting, sentence prediction)
- Convolutional Neural Networks: Useful for feature and object recognition in visual data (image, video). Also applied in other context (forecasting)
- Unsupervised Pre-trained Networks: Autoencoders, Deep Belief networks and Generative Adversarial networks. Used in generating images, labeling outcomes, dimensionality reduction

* Gradient descent
* Stochastic gradient descent
* Mini-batch gradient descent

In backpropagation, as we have more layers, the gradient gets very small at the early layers, this is known as the vanishing gradient problem. For this other activations such as ReLU have become more common.

# Activation functions

They improve our ability to determine non-linear outcomes. Thus it allows the nn to compute more complex features

1. Sigmoid activation function: prone to vashing gradient problem
2. hyperbolic tangent function: prone to vashing gradient problem
3. Rectified Linear Unit (ReLU): solves vashing gradient problem
4. Leaky Rectified Linear Unit (LReLU): solves vashing gradient problem
5. softmax

### Output layer:
Binary classification:sigmoid
Regression with negative and positive values: Linear activatio furnction
Regression with only positive values, use ReLU

### Hdden layers
Most commen choice is ReLU since it is faster. Sigmoid run into the vanishing gradient problem

## Optimizers

Updates weights by optimising the way the gradients are calculated

* Momentum
* Nesterov momentum
* Adaptive gradient algorithm (AdaGrad)
* RMSProp
* Adam (adapt the learning rate and use several learning rates)

Adam and RMSProp are the most popular

## Data shuffling

### Convolutional Neural Network

### Kernel 
It is a grid of weights overlaid on image, centered on one pixel. They are feature detectors


## CNN architectures

* LeNet
* AlexNet
* VGG
* Inception
* ResNet