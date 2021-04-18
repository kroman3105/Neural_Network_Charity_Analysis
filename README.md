# Neural_Network_Charity_Analysis

## Overview of Analysis
In order to predict the success of an organization after receiving funding money from Alphabet Soup, we used a neural network machine learning model.  The goal was to identify the key variable in the data provided to determine whether the money would be used effectively.

## Results

# Data Preprocessing

- The target variable was the 'IS_SUCCESSFUL' results
- The features of the model included Application Type, Affiliation, Classification, Use Case, Organization, Income Amount, Ask Amounts and if any Special Considerations were made
- The variables that were neitehr targets nor features were EIN and Name

# Compiling, Training, and Evaluating the Model

- The original model ran with 80 neurons on hidden layer 1, and 30 neurons on hidden layer 2 with activation function relu on the second hidden layer and sigmoid on the output layer
- Per below snapshot, accuracy was only 72.42% so target performance was not achieved

![Original](https://github.com/kroman3105/Neural_Network_Charity_Analysis/blob/main/Images/Original.PNG)

- To increase model performance, we increased to 100 and 50 neorons on the first two layers and added a third layer with another 10 neurons.  We also decreased the epochs to 50 and changed the activation assoicated with the output to tanh.  Unfortunately expected results were still not achieved with an accuracy of 72.07%

![Optimized](https://github.com/kroman3105/Neural_Network_Charity_Analysis/blob/main/Images/Optimized.PNG)

## Summary

As the accuracy fell below the targeted results using this deep learning model, it appears that a different model should be pursued.  One recommendation for an alternative model to use would be to use the Random Forest classifiers.  This ensemble learning model is often able to improve predictive accuracy with faster performance and should be pursued as an alternative to the deep learning model performed. 
