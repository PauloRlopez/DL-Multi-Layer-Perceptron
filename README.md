# Building a Multi-Layer-Perceptronn using Tensorflow

![Alt image](https://github.com/pau-lo/Deep-Learning-Multi-Layer-Perceptron-Handwritten-Character-Image-Classifier-/blob/master/mnist.png)

## Overview 

The MNIST database of handwritten digits, available from this [page](http://yann.lecun.com/exdb/mnist/), has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

Here we will be building a multi-layer perceptron to classify handwritten digits using tensorflow.

## Directions

It is recommended to install tensorflow as a virtual environment via conda. 

1. Install [tensorflow](https://www.tensorflow.org/install/)  
2. Download the dataset
3. Split it into training and testing datasets
4. Test the model
5. Calculate the accuracy 

## Dependencies 

1. get the [input_data](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/mnist/input_data.py) py script and put it on your current working folder.
2. tensorflow 

## Purpose 

A Deep Learning exercise to classify hand-written characters. 

## Results Example

    ```bat
    $  (tensorflow) 2_Imagine (master *) Deep Learning $ python mnist.py
        Extracting ~/DS_ML/Deep Learning/train-images-idx3-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/train-labels-idx1-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/t10k-images-idx3-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/t10k-labels-idx1-ubyte.gz
        
    
                
      Iteration: 0001 cost= 29.860465115
      Iteration: 0003 cost= 21.000626442
      Iteration: 0005 cost= 20.136222584
      Iteration: 0007 cost= 19.652899717
      Iteration: 0009 cost= 19.383099742
      Iteration: 0011 cost= 19.165024177
      Iteration: 0013 cost= 18.770430475
      Iteration: 0015 cost= 18.776208125
      Iteration: 0017 cost= 18.655625496
      Iteration: 0019 cost= 18.493998495
      Iteration: 0021 cost= 18.481863666
      Iteration: 0023 cost= 18.312887948
      Iteration: 0025 cost= 18.326373666
      Iteration: 0027 cost= 18.227951255
      Iteration: 0029 cost= 18.035528241
      Accuracy: 0.9235
      Tuning completed!
     

## Credits

Credit to google for creating tensorflow.
Thanks to Yann LeCun, Courant Institute, NYU;
Corinna Cortes, Google Labs, New York; and Christopher J.C. Burges, Microsoft Research, Redmond;
All are part of the **MNIST DATABASE.**
