# Neural Network From Scratch
This project involves implementing a neural network from scratch and training it on the [MNIST dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) for handwritten digit classification. 
The code is developed based on the principles outlined in the book ["Neural Network from Scratch"](nnfs.io).


## This neural network implementation consists of the following components:
* Layer_Dense: Implements a dense layer with random initialization of weights and zero biases.
* Activation_ReLU: Implements the ReLU activation function.
* Activation_Softmax: Implements the softmax activation function for multiclass classification.
* Loss: Defines the base class for loss functions.
* Loss_CategoricalCrossentropy: Implements the categorical cross-entropy loss function.
* Activation_Softmax_Loss_CategoricalCrossentropy: Combines the softmax activation and categorical cross-entropy loss.
* Optimizer_SGD, Optimizer_AdaGrad, Optimizer_RMSprop, Optimizer_Adam: Implement various optimization algorithms for updating weights and biases during training.

