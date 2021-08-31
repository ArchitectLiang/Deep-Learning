# CV
Computer Vision Project

In this assignment you will practice writing backpropagation code, and training
Neural Networks and Convolutional Neural Networks. The goals of this assignment
are as follows:

- understand **Neural Networks** and how they are arranged in layered
  architectures
- understand and be able to implement (vectorized) **backpropagation**
- implement various **update rules** used to optimize Neural Networks
- implement **batch normalization** for training deep networks
- implement **dropout** to regularize networks
- effectively **cross-validate** and find the best hyperparameters for Neural
  Network architecture
- understand the architecture of **Convolutional Neural Networks**
- gain an understanding of how a modern deep learning library (PyTorch) works
  and gain practical experience using it to train models.

### Q1: Fully-connected Neural Network (35 points)
The IPython notebook `FullyConnectedNets.ipynb` will introduce you to our
modular layer design, and then use those layers to implement fully-connected
networks of arbitrary depth. To optimize these models you will implement several
popular update rules.

### Q2: Batch Normalization (25 points)
In the IPython notebook `BatchNormalization.ipynb` you will implement batch
normalization, and use it to train deep fully-connected networks.

### Q3: Dropout (10 points)
The IPython notebook `Dropout.ipynb` will help you implement Dropout and explore
its effects on model generalization.

### Q4: ConvNet (20 points)
In the IPython Notebook `ConvolutionalNetworks.ipynb` you will implement several
new layers that are commonly used in convolutional networks as well as implement
a small convolutional network.

### Q5: Train a model on CIFAR10 using Pytorch! (10 points)
Now that you've implemented and gained an understanding for many key components 
of a basic deep learning library, it is time to move on to a modern deep learning
library: Pytorch. Here, we will walk you through the key concepts of PyTorch, and
you will use it to experiment and train a model on CIFAR10. We highly recommend 
you use Google Colab (https://colab.research.google.com/) for this notebook, as it
comes with Pytorch installed and provides access to GPUs.

If you use Colab for this notebook, make sure to manually download the completed 
notebook and place it in the assignment directory before submitting. Also remember 
to download required output file and place it into submission_logs/ directory.

