# Purpose
The purpose of this analysis is to perfrorm deep learning on charity data to find out if they will succeed or fail.

# Results

## Preprocessing 
* When it comes to the target our target variable is the IS_SUCCESSFUL variable due to being the goal to see if a charity succeeds or not.
* All other variables within the charity data file are considered as features to help determine the success rate for it.
*  The excluded variable were the NAME and EIN  because they done provide any significance in determining if a charity would be successful or not.

## Compiling, Training, and Modelling
* There were 3 Neuron Layers that get smaller and smaller the deeper the layer goes and the two unique activation functions were TANH and Sigmoid activation.
* I was not able to achieve the 75% goal but was really close with 72%.
  [!EPOVH](images/EPOCH.png)
* Some steps I took was to increase the amount of hidden layers, change the activation function from RELU to TANH and also Increasing number of epochs being runned.

## Summary
The overall results of the model was relatively close to the goal of 75% , I think using a supervised learning algorithm would of been much better because there were labels already in place to work from. Additionally, a logistic regression model can help classify if it would be successful or not.