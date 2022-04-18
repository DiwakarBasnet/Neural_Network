# Neural Network

## Layers of neural network:
1. **Input layer-** Every NN has one input layer and number of neurons equals number of features or + 1 for bias.
2. **Output layer-** Every NN has one output layer. If NN is regression model then single node for output layer.
                 If NN is classifier model then single node for binary classification and for multi classification more than one node.
3. **Hidden layer-** Numbers of layers and neurons are hyperparameters.

## Activation functions:
### Output layer-
1. Regression problem --> Linear
2. Binary classification problem --> Logistic(sigmoid)
3. Multiclass classification problem --> Softmax
4. Multilabel classification problem --> one node per class sigmoid activation
![alt text](https://machinelearningmastery.com/wp-content/uploads/2020/12/How-to-Choose-an-Output-Layer-Activation-Function.png)

### Hidden layer-
1. Multilayer Perceptron(MLP) --> ReLU
2. Convolutional Neural Network(CNN) --> ReLU
3. Recurrent Neural Network(RNN) --> Tanh or/and Sigmoid
![alt text](https://machinelearningmastery.com/wp-content/uploads/2020/12/How-to-Choose-an-Hidden-Layer-Activation-Function.png)

## Loss functions:
Loss function show how deviated the prediction is with actual prediction.
Machines learn to decrease loss function by moving close to the ground truth.
There are many functions out there to find the loss based on the predicted and actual value depending on the problem.
And optimizers are used to minimize the loss to make predictions better.
