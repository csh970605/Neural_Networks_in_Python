# Homework Instruction

In theoretical classes we worked with the example of salary increase based on age and educational background. The idea of this homework is to use a dataset to train the single layer perceptron to learn this pattern. Instead of using the AND or OR operators, you should use the same code in order to classify whether a person will earn or not a salary increase.

Below you can see the input and output variables

```
inputs = np.array([[18,2], [20,3], [21, 4], [35,15], [36,16], [38, 18]])
outputs = np.array([0, 0, 0, 1, 1, 1])
```
Class "0" (zero) indicates a person won't earn a salary increase, otherwise, class "1" (one) indicates a person will earn a salary increase. After training the single layer perceptron, use the new instances below to make predictions. Will the instances below be classified 0 or 1?

```
test_inputs = np.array([[17,5], [25,8], [45,10], [31,20]])
```
Hint: you will need to normalize the inputs in order to train the neural network. You can use the MinMaxScaler from sklearn library

