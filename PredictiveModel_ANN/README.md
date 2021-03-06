# Predictive Model Using Artificial Neural Networks

## Predictive Modelling
Predictive modeling is a process that uses data mining and probability to forecast outcomes. Each model is made up of a number of predictors, which are variables that are likely to influence future results. Once data has been collected for relevant predictors, a statistical model is formulated. The model may employ a simple linear equation, or it may be a complex neural network, mapped out by sophisticated software. As additional data becomes available, the statistical analysis model is validated or revised. 

## Regression
Regression analysis is a form of predictive modelling technique which investigates the relationship between a dependent (target) and independent variable (s) (predictor). Multiple linear regression attempts to model the relationship between two or more explanatory variables and a response variable by fitting a linear equation to observed data. Every value of the independent variable x is associated with a value of the dependent variable y. The population regression line for p explanatory variables x1, x2, ... , xp is defined to be Uy = B0 + B1x1 + B2x2 + ... + Bpxp. 

Formally, the model for multiple linear regression, given n observations, is
yi = B0 + B1xi1 + B2xi2 + ... Bpxip + Ei for i = 1,2, ... n.

## Artificial Neural Network
An Artificial Neural Network (ANN) is a computational model based on the structure and functions of biological neural networks. Information that flows through the network affects the structure of the ANN because a neural network changes - or learns, in a sense - based on that input and output. A neural network performing regression will have one output node, and that node will just multiply the sum of the previous layer activations by 1. The result will be ŷ, “y hat”, the network’s estimate, the dependent variable that all x’s map to. To perform backpropagation and make the network learn, we simply compare ŷ to the ground-truth value of y and adjust the weights and biases of the network until error is minimized, much as we would with a classifier.

## Libraries Used
Keras - A collection of high-level Neural Networks written in Python

Numpy - Paackage for scientific computing using Python

## Run The Code
The code is written in python and run with the standard command

python filename.py
