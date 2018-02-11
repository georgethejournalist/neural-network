# neural-network
Basic neural network with backpropagation for sorting the famous Iris dataset.

The project consists of several classes which are used to create a neural network (namely Network.cs, Layer.cs, Node.cs, Synapse.cs) and a few classes that are used for data handling (Pattern.cs, PatternHelper.cs, ActivationFunctions.cs) inside of the network. The code is well documented and should be hopefully more-or-less self-explanatory.

For the classification task I created a neural network consisting of 4 input nodes, 3 output nodes and 2 hidden layers with 8 nodes each. I divided the full data set into two subsets – one each for training and testing in an 80/20 ratio. I decided to omit the validation phase and the subset with it. The weights were created randomly (with a specified seed). The steepness for the sigmoid activation was set to 1 and the learning rate 0.015 after a quick trial-and-error. I used sigmoid activation for both hidden and output layer nodes.

