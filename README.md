# CIFAR-1--Classification-Model-Neural-Network-and-Deep-Learning
## Aim
* To implement a particular model in order to solve the CIFAR-10 classification problem and classify every single image in terms of 1 out of 10 classes.
* To build a model on training set and evaluate on tetsing set to acheive highest possible accuracy
## The Model
An architecture to process images based on Convolutional Neural Networks consisting of the n Backbones (B1,...,Bn) and a Classifier.
## The Backbone 
* The CustomModel is built with a backbone and a classifier, implementing multiple Block instances and fully connected layers in a sequential container.
* The backbone is responsible for extracting features from the samples.
* It consists of several blocks with convolutional layers, activation functions, batch normalization layers, and residual connections. The total number of block instances in the backbone is 5.
* ReLU activation function is used in the classifier network for its simplicity, effectiveness, and sparsity properties, which prevent overfitting and aid gradient propagation.
* The final layer of the backbone uses the Logsoftmax function for effective gradient optimization and a smooth training process during epochs.
* Batch normalization is applied to each layer in the backbone for normalization, which is particularly effective for CNN networks and image processing tasks.
## The Classifier
