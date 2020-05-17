# Image classification with Logistic Regression from scratch using NumPy

This code includes feature extraction, model training, and evaluation steps for image classification with NumPy. Let's see what we will achieve in this notebook in steps:

   * First, we wil load and visualize the dataset and extract two different set of features to build a classifier on.

   * We will run our logistic regression algorithm with gradient descent the representations to classify digits into 1 and 5.
    
   * We will experiment with different learning rates to find the best one.

   * Finally, we will evaluate the implemented models, decide which is the best performing one and visualize a decision boundary.

Once again, let's remind ourselves that we won't be using any function or library that accomplishes the task itself. For instance, we won't use scikit-learn to implement cross validation, we will use numpy for that and for all of the other tasks.
