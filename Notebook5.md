# Notebook \#5
Deep learning with MLP and CNN for an image recognition task. 

## The Data: 📊

For this notebook, you will train two deep neural networks (DNN): **Part 1) a multilayer perceptron (MLP)***, and Part 2) a convolutional neural network (CNN) for an image recognition task. In this case, the algorithm will utilize a dataset of images to learn useful features for classifying an image into one of 10 classes. You should be using the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).

<div>
<img src="https://docs.pytorch.org/tutorials/_images/cifar10.png" width=500/>
</div>

The starter notebook contains a snippet of code on how to download the dataset using PyTorch's __torchvision.datasets__ module

## The Exercises: 💪
The assignment is to run an experiment where you try a simple MLP network and a CNN to determine which network yields the best result in terms of the classification accuracy metric. I will be looking for the following:

- In a mark-down cell at the top of your notebook, write your name and give a brief explanation of the problem.  
- Build an **MLP** that has a structure that contains:
  - One input layer 
  - One (or more) hidden layers
  - One output layer
- Build a **CNN** that has this structure that contains:
  - Conv layer 1
  - Conv layer 2
  - Flatten layer
  - Fully Connected layer (Dense)
  - Fully Connected layer (Dense)

- **Train both models** and compare their performance.    
    - You should train each model for enough epochs that your performance on the test set stops improving (i.e., show where you reach overfitting).

- **Include graphs** of how well your testing data performed vs. the training data. Include only the graphs of your tuned models. Describe the process you used to tune the models, but you should not include graphs of this entire process. 
- **Conclusions**: Answer the following questions in a markup cell at the bottom of your notebook.
    - Describe the process you used to tune the models. How many epochs of training have been utilized for the MLP? How many epochs of training have been utilized for CNN?
    - How accurate can you make your MLP predictor? How accurate can you make your CNN predictor? At which epoch do you anticipate achieving the best results, respectively, for MLP and CNN?
    - What configuration of your network (MLP or CNN) proved to be more accurate? Why do you think this is the case?

Rename your file LastnameNotebook5.ipynb and submit the link to your repository to Blackboard.
