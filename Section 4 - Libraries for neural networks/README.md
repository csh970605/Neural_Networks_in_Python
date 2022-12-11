# Homework instruction: iris dataset

The goal is to build a neural network in PyBrain to classify the Iris dataset, so the code is very similar to the one we already have implemented

Hints:

Try to find how to declare more hidden layer using the buildNetwork shortcut

In order to create the SupervisedDataset object, you can implement a for loop to go through each instance of the dataset

As we have a classification problem with 3 classes (setosa, virginica and versicolor), you need to use the softmax function in the output layer

Also, you need to encode classes. For example: class 0 will be 1 0 0, class 1 will be 0 1 0, and finally, class 2 will be 0 0 1

The final output of the neural network will be an array with 3 values and you need to extract the highest probability

# Homework instruction: wine classification

The goal is to build a neural network in sklearn to classify types of wines! 
