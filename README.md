# Micrograd -

I built this to understand gradient descent and neural networks from scratch. 
This is an auto gradient engine from [Andrej Karpathy's video](https://www.youtube.com/watch?v=VMj-3S1tku0)

- The value class keeps track of each operation applied to a number and automatically calculates the gradients using ._backward()
- A small neural network was built using the neuron, layer, and multi layer perceptron (MLP) class 
Training process: forward pass -> calculate loss -> backpropagation/calculate gradients -> gradient descent.


Before this, I had no clue how neural networks actually learned. It seemed like magic. This taught me: 
- How neural networks learn/how the training process works
- Why we need autograd (calculating derivatives by hand is impossibly slow even for a small neural net)
- How changing weights by small amounts many many times results in intelligence!

