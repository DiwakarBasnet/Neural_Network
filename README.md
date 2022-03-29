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

### Hidden layer-
1. Multilayer Perceptron(MLP) --> ReLU
2. Convolutional Neural Network(CNN) --> ReLU
3. Recurrent Neural Network(RNN) --> Tanh or/and Sigmoid

## Note:
1. accuracy_score is for classification problems only.
2. For regression problem no need to put metric['accuracy'] in model.compile.
