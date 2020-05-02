## Numbers' images classification

Present notebook contains codes for images classification. The goal is to predict if number on an image is prime or composite.
Modified MNIST dataset has been used. '0' and '1' numbers' pictures has been deleted. 
Labels has been encoded into 0 and 1, where 0 is a prime number (2, 3, 5 or 7) and 1 is a composite number (4, 6, 8, or 9). 
The model used is multilayer artificial neural network. 
Model of the network was created with Tensorflow 2.0 and Keras as high level API. 
Model was tuned with Scikit-learn library.

### Dataset describtion
Dataset contains pictures of images which represent numbers from 0 to 9, and labels of those numbers.
There are 4 files, which divide data on 
images taining set, labels training set, images test set, and labels test set as follows:  

*train-images.idx3-ubyte
*train-labels.idx1-ubyte
*t10k-images.idx3-ubyte
*t10k-labels.idx1-ubyte

Data source: [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)

### Agenda

MNIST_binary_cls_tf.ipynb consists of:

1. Data exploration
2. Data preparation
3. Data modelling
4. Model assessment
5. Hyperparameters tuning
6. Model assessment


### To do:

* model's hyperparameters tuning
* improve model architecture
* implement convolutional neural networks

