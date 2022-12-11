# Homework instruction: iris dataset

The goal is to build a neural network in PyBrain to classify the Iris dataset, so the code is very similar to the one we already have implemented

Hints:

Try to find how to declare more hidden layer using the buildNetwork shortcut

In order to create the SupervisedDataset object, you can implement a for loop to go through each instance of the dataset

As we have a classification problem with 3 classes (setosa, virginica and versicolor), you need to use the softmax function in the output layer

Also, you need to encode classes. For example: class 0 will be 1 0 0, class 1 will be 0 1 0, and finally, class 2 will be 0 0 1

The final output of the neural network will be an array with 3 values and you need to extract the highest probability

# Homework instruction: wine classification

The goal is to build a neural network in sklearn to classify types of wines

# Homework instruction: fashion mnist classification

The goal is to build a neural network in TensorFlow to classify types of clothes

# Homework instruction: diabetes classification

Use the diabetes.csv attached to this class in order to classify whether or not a person has diabetes. You can see here more information about the dataset

Hints:

Upload the .csv file into the Google Colab environment

Use the pandas library in order to load the csv file - check the read_csv function

It's a binary classification problem, class 0 (no disease) and class 1 (disease)

You need to normalize the data, check the MinMaxScaler from sklearn
