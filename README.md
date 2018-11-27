## First-Deep-learning-
 My first Deep learing program using with Python and Tensorflow 
# Dataset 
   the most common "hello world" example for deep learning, which is the mnist dataset. 
   It's a dataset of hand-written digits, 0 through 9. It's 28x28 images of these hand-written digits.
# Dependecies
    Tensorflow :
                 import tensorflow as tf
    Keras :
            import tensorflow.keras as keras
            
A basic neural network consists of an input layer, which is just your data, in numerical form. After your input layer, you will have some number of what are called "hidden" layers. A hidden layer is just in between your input and output layers. One hidden layer means you just have a neural network. Two or more hidden layers, a deep neural network



A single neuron might look as follows:


The idea is a single neuron is just sum of all of the inputs x weights, fed through some sort of activation function. The activation function is meant to simulate a neuron firing or not. A simple example would be a stepper function, where, at some point, the threshold is crossed, and the neuron fires a 1, else a 0. Let's say that neuron is in the first hidden layer, and it's going to communicate with the next hidden layer. So it's going to send it's 0 or a 1 signal, multiplied by the weights, to the next neuron, and this is the process for all neurons and all layers.

The mathematical challenge for the artificial neural network is to best optimize thousands or millions or whatever number of weights you have, so that your output layer results in what you were hoping for. Solving for this problem, and building out the layers of our neural network model is exactly what TensorFlow is for. TensorFlow is used for all things "operations on tensors." A tensor in this case is nothing fancy. It's a multi-dimensional array.
