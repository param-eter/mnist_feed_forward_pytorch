# MNIST - PyTorch Feed Forward Model

## Overview
A PyTorch based feed forward neural network to recognise handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/).

This was covered in a course I was doing and I thought a cleaner version in notebook form with some annotations may be useful for others.

## The Task
60,000 training images  
10,000 test images  
10 possible digits (0-9)  

The evaluation metric used accuracy.

## Requirements
PyTorch 0.3.1  
I haven't tested this on other versions.

if CUDA is available, the model and variables are moved onto the GPU, otherwise processing is done on the CPU.

## Approach
-Download data  
-Explore the training data  
-Set model parameters
-Make datasets iterable  
-Create the model class
-Instantiate the model class  
-Instantiate the loss class  
-Instantiate the optimiser  
-Train and test the model

## Outcome
The model returned an accuracy of **97.55%** using 2 non-linear layers(ReLU). There's still potential for this model to be improved by changing things like the number of hidden units, learning rate, number of layers and batch size, but it's a good starting point.
