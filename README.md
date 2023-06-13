# CIFAR-1--Classification-Model-Neural-Network-and-Deep-Learning
## Aim
* To implement a particular model in order to solve the CIFAR-10 classification problem and classify every single image in terms of 1 out of 10 classes.
* To build a model on training set and evaluate on tetsing set to acheive highest possible accuracy
## The Model
An architecture to process images based on Convolutional Neural Networks consisting of the n Backbones (B1,...,Bn) and a Classifier.
## The Backbone 
* The CustomModel is built with a backbone and a classifier, implementing multiple Block instances and fully connected layers in a sequential container.
* The backbone is responsible for extracting features from the samples.
## The Classifier
* The classifier network comprises fully connected linear layers, comparing activation functions, batch normalization, and blocks.
Adaptive average pooling is used to reduce the vector size and map it to a 'k' vector size.
