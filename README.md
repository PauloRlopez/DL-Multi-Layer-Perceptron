# Building a Multi-Layer-Perceptron

![Alt image](https://github.com/PauloRlopez/DL-Multi-Layer-Perceptron-Handwritten-Character-Image-Classifier/blob/master/mnist.png)

## Overview 

Building a multi-layer perceptron to try to classify handwritten digits using tensor flow.

The data was acquired from: [THE MNIST DATABASE](http://yann.lecun.com/exdb/mnist/)

## Directions

I recommend to install tensor flow as a virtual environment via conda 
1. Install [tensorflow](https://www.tensorflow.org/install/)  
2. download the dataset
3. split it into training and testing datasets
4. test the model
5. calculate the accuracy 

## Dependencies 

1. get the [input_data](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/mnist/input_data.py) py script and put it on your current working folder.
2. tensorflow 

## Purpose 

This is a Deep Learning exercise that was re-created and change a few lines for my learning purposes.  

## Results

        $(tensorflow) 2_Imagine (master *) Deep Learning $ python mnist.py
        Extracting ~/DS_ML/Deep Learning/train-images-idx3-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/train-labels-idx1-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/t10k-images-idx3-ubyte.gz
        Extracting ~/DS_ML/Deep Learning/t10k-labels-idx1-ubyte.gz
        WARNING:tensorflow:From mnist.py:62: initialize_all_variables (from tensorflow.python.ops.variables) is deprecated           and will be removed after 2017-03-02.
        Instructions for updating:
        Use `tf.global_variables_initializer` instead.
        W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.1                       instructions, but these are available on your machine and could speed up CPU computations.
         W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use SSE4.2                       instructions, but these are available on your machine and could speed up CPU computations.
        W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX instructions,               but these are available on your machine and could speed up CPU computations.
         W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use AVX2                         instructions, but these are available on your machine and could speed up CPU computations.
         W tensorflow/core/platform/cpu_feature_guard.cc:45] The TensorFlow library wasn't compiled to use FMA instructions,          but these are available on your machine and could speed up CPU computations.
                WARNING:tensorflow:Passing a `GraphDef` to the SummaryWriter is deprecated. Pass a `Graph` object instead,                     such as `sess.graph`.
                
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

Credit to google for creating tensorflow and  Yann LeCun, Courant Institute, NYU
Corinna Cortes, Google Labs, New York Christopher J.C. Burges, Microsoft Research, Redmond.

**Thanks**

