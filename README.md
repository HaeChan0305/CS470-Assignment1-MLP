<div align=center>
  <h1>
    MLP: Multi-Layer Perceptron
  </h1>
  <p>
    <b>KAIST CS470: Introduction to Artificial Intelligence (Spring 2023)</b><br>
    Programming Assignment 1    
  </p>
</div>

<div align=center>
  <p>
    Instructor: <a href=https://sites.google.com/site/daehyungpark target="_blank"><b>Daehyung Park</b></a> (daehyung [at] kaist.ac.kr)<br>
  </p>
</div>


## Assignment 1
### TASK 1: Implement a Multi-Layer Perceptron (MLP)
In this exercise, you will implement a neural network with fully-connected layers to perform image classification, and test it out on the [CIFAR-10](http://www.cs.toronto.edu/~kriz/cifar.html) dataset. Please, run following blocks for running your code.

### TASK 2: Train a model
To train our model, we will use a Stochastic Gradient Descent(SGD) method with momentum. In addition, we will adjust the learning rate with an exponential learning rate schedule as optimization proceeds; after each epoch, we will reduce the learning rate by multiplying it by a decay rate.

### TASK 3: Visualization
You have to plot the loss function and the accuracies on the training and validation sets. Then, visualize the weights that were learned in the first layer of the network. The weights of the intermediate layer may learn to represent specific features of the inputs, such as their curvature, thickness, or orientation.

### Results
- Visualization
  
  <img src="/assignment1_MLP/Figure/visualization.png" width="50%" height="50%">
  
- Loss and accuracy Plot
  - ReLU

    <img src="/assignment1_MLP/Figure/loss_ReLU.png" width="50%" height="50%">
    
    <img src="/assignment1_MLP/Figure/accuracy_ReLU.png" width="50%" height="50%">

  - Leaky ReLU

    <img src="/assignment1_MLP/Figure/Leaky_ReLU.png" width="50%" height="50%">

  - SWISH

    <img src="/assignment1_MLP/Figure/SWISH.png" width="50%" height="50%">

  - SELU

    <img src="/assignment1_MLP/Figure/SELU.png" width="50%" height="50%">

- Loss and accuracy by activation functions on 2000 iteration.

| Activation Function | ReLU | Leaky ReLU | SWISH | SELU |
|---|---|---|---|---|
| **Loss** | 1.49 | 1.50 | 1.51 | 1.54 |
| **Accuracy** | 0.470  | 0.469 | 0.472 | 0.462 |


<!--
# Tutorial Links
- [Tutorial 1-1](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_1/cs470_tutorial_1_1.ipynb)
- [Tutorial 1-2](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_1/cs470_tutorial_1_2.ipynb)
- [Tutorial 1-3](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_1/cs470_tutorial_1_3.ipynb)
- [Tutorial 2](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_2/RL_tutorial.ipynb)
- [Tutorial 3](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_3/README.md)


# Quiz
- [Quiz 1](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_1/MLP_tutorial_quiz_problem.ipynb)
- [Quiz 2](https://github.com/pidipidi/CS470_IAI_2023_Spring/blob/main/tutorial_1/tutorial2_quiz.ipynb)


# Installation
- [ROS2 Foxy](https://docs.ros.org/en/foxy/Installation.html)
-->

# ETC
For educational purpose only. This software cannot be used for any re-distribution with or without modification. The lecture notebook files are copied or modified from the material of Siamak Ravanbakhsh. 

