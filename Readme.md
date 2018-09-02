* CNN based classifier to classify objects in CIFAR-10 dataset.

* Dataset used: CIFAR-10- https://www.cs.toronto.edu/~kriz/cifar.html

### Data preprocessing:

  1. Feature scaling- Deep Learning models necessitate feature scaling because these models need to do serious computation. All the pixel values (ranging from 0 - 255 on 3 channels (rgb)) were scaled down to 0 to 1.
  2. One-hot encoding- To get rid of ordinality that is inherited by numerical values (0, 1, 2, 3, ..., 9). This ordinality may cause the weights of the ANN (which is a CNN for this case) to get skewed towards higher numerical values.

### Building the model

  * Libraries used:
     Keras API with Theano backend

  * Reference for the model was taken from the All Convolutional Net paper. Link: https://arxiv.org/abs/1412.6806
