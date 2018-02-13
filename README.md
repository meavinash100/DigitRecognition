## Different variations of Deep Learning Models using Tensorflow and Keras for Handwritten Digit Recognition on MNIST Dataset

### The following variations of deep learning models are used in the exploration:
* Fully connected shallow neural network without minibatched
* Fully connected deep neural network with minibatchs
* Fully connected deep neural network with dropout regularization
* Fully connected deep neural network with dropout regularization and learning rate decay
* Convolution neural network (CNN) without Maxpooling
* Convolution neural network (CNN) with Maxpooling
* Convolution neural network (CNN) without Maxpooling with Keras
* Convolution neural network (CNN) with Maxpooling and Dropout with Keras
* ResNet50 Implementation with Keras

### Possible Hyperparameters for Tensorflow
* Learning Rate
* Dropout Rate
* Minibatch Size
* Number of Epochs
* Number of Layers in the Neural Network (Depth of the network)
* Number of Neurons in the Fully Connected Layers
* For CNN
  * Stride
  * Number of Channel filters
  * Kernal Size (Framesize) of Maxpool Layer
  
### Possible Hyperparameters for Keras
* Dropout Rate
* Minibatch Size
* Number of Epochs
* Number of Layers in the Neural Network (Depth of the network)
* Number of Neurons in the Fully Connected Layers
* For CNN
  * Stride
  * Number of Channel filters
  * Kernal Size (Framesize) of Maxpool Layer
  
Note: 
1. Some cmputation intensive parts of the code are commented because the development is done in a resource constrained environment. 

References:
* Deep Learning Specialization on Coursera by deeplearning.ai
* Martin Gorner repo https://github.com/martin-gorner/tensorflow-mnist-tutorial