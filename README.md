# Semantic Segmentation
In this project I've implemented a semantic segmentation of 
road from images using an FCN with VGG16 as base network.
The dataset used for training the network is the Kitti dataset.

This project is following the FCN described in the article 
[Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf).

The network structure is following the 
structure described in the article above.

The network is trained by using a loss function that includes cross entropy
loss and l2 regularization loss in order to apply layer regularization for each of the decoder layers.


