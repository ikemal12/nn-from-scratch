# Neural Network using only NumPy

A simple 2-layer neural network trained on the MNIST dataset, achieving 84% accuracy without any explicit optimisations.

The purpose of this exercise was to gain a deeper understanding behind the underlying maths of neural networks.

The neural network has a simple 2-layer architecture:

* Input layer a<sup>[0]</sup> has 784 units corresponding to 784 pixels within each 28x28 input image
* There is one hidden layer a<sup>[1]</sup> which has 10 units with a ReLU activation function
* Finally the output layer a<sup>[2]</sup> has 10 units corresponding to the 10 digit classes (0-9), with a softmax activation

Future extensions:

* Add optimisation techniques like regularisation
* Try different variations of gradient descent like momentum, RMSProp, Adam optimiser 
