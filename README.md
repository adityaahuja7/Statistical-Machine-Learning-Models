# **README**
## Model-1

* Implemented GradientBoosting Classifer from scratch with DecisionTreeRegression as the base model.
* Maximum Tree Depth = 1
* Number of Iterations (M) = 5
* Learning Rate 0.1

##Model-2

* Created a Feed Forward Neural Network to Classify samples from the FMNIST Dataset
* the NN contains 1 Input Layer with 784 nodes, 1 Hidden Layers with 64 Nodes (ReLu), 1 Output Layer with 10 nodes (Softmax)
* SGD optimizer has been used with learning rat 0.1 and momentum = 0.9
* Multiclass cross entropy function has been used
* Batch Size = 512

##Model-3

* Created an AutoEncoder to encode and decode samples from the MNIST Dataset
* Used Adam Optimizer with learning rate 0.01
* Used Mean-Squared Loss function (Reason mentioned in comments)
* Removed the decoder and added 2 more layers to create the 'MNIST Classification Model'.

##Model-4

* Implemented Bagging Classifier from Scratch.
* Bag Size = 3
* Used majority voting to decided predicted class.
