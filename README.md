# Transfer_Learning_Images_classification
In this tutorial, you will learn how to train a convolutional neural network for image classification using transfer learning. You can read more about the transfer learning at cs231n notes

## Load Data
We will use torchvision and torch.utils.data packages for loading the data.

The problem we’re going to solve today is to train a model to classify ants and bees. We have about 120 training images each for ants and bees. There are 75 validation images for each class. Usually, this is a very small dataset to generalize upon, if trained from scratch. Since we are using transfer learning, we should be able to generalize reasonably well.

This dataset is a very small subset of imagenet.

   Download the data from [Here](http://google.com) and extract it to the current directory.
   
## Training the model
Now, let’s write a general function to train a model. Here, we will illustrate:

  Scheduling the learning rate
  Saving the best model


