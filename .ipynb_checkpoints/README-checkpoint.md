# Assignment---Module-13

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results


### Original Neural Network Model:
  
  * 116 input features
  * 1 output neuron
  * 2 hidden layers
  * first hidden layer has 58 neurons
  * second hidden layer has 29 neurons
  * relu activation function is used on both hidden layers
  * sigmoid acitvation function is used on the output layer
  
![Original Model Summary](Images/Original_Model_Summary.JPEG)

  * compiling the model using binary_crossentropy function
  * optimizer "adam" is used
  * the model was run for 50 epochs


### Alternative 1 Neural Network Model:
  
  * 116 input features
  * 1 output neuron
  * 2 hidden layers
  * first hidden layer has 58 neurons
  * second hidden layer has 29 neurons
  * relu activation function is used on both hidden layers
  * sigmoid acitvation function is used on the output layer
  
![A1 Model Summary](Images/A1_Model_Summary.JPEG)

  * compiling the model using binary_crossentropy function
  * optimizer "adam" is used
  * the model was run for 100 epochs


### Alternative 2 Neural Network Model:
  
  * 116 input features
  * 1 output neuron
  * 2 hidden layers
  * 1 Dropout layer after the first hidden layer
  * first hidden layer has 58 neurons
  * second hidden layer has 29 neurons
  * relu activation function is used on both hidden layers
  * sigmoid acitvation function is used on the output layer
  
![A2 Model Summary](Images/A2_Model_Summary.JPEG)

  * compiling the model using binary_crossentropy function
  * optimizer "adam" is used
  * the model was run for 100 epochs

## Summary

Neither alternative models improved accuracy by any great degree. The Alternative Model 2 showed some slight accuracy improvement, from 0.730 in the original model to 0.732 in the Alternative 2 model.

In the Alternative 1 Model, where I ran the identical specification as the Original Model, but over 100 epochs, the accuracy decreased slightly from 0.730 to 0.729.

Loss was also roughly the same across all models.

![Original_Model_Results](Images/Original_Model_Results.JPEG))

![A1_Model_Results](Images/A1_Model_Results.JPEG))

![A2_Model_Results](Images/A2_Model_Results.JPEG))

