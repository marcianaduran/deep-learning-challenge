# Deep Learning Instructions

Steps
1. Preprocess the data; use `pd.get_dummies()` to encode categorical variables, `StandardScaler()` to scale the training and test features datasets, and the `transform ` function to fit the scaled data to the training data.
2. Compile, train, and evaluate a neural network model; assign the number of input features and notes using `TensorFlow` and `Keras`, and the hidden and output layers with an appropiate activation function. Export results to an HDF5 file.
3. Optimize the model to achieve a target predictive accuracy higher than 75%. Export results to an HDF5 file.

# Module 21 Report Template
## Overview of the Analysis
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Use the dataset provided to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup using machine learning and neural networks.

### Data Attributes (34,000 entries)
* `EIN` and `NAME`—Identification columns
* `APPLICATION_TYPE`—Alphabet Soup application type
* `AFFILIATION`—Affiliated sector of industry
* `CLASSIFICATION`—Government organization classification
* `USE_CASE`—Use case for funding
* `ORGANIZATION`—Organization type
* `STATUS`—Active status
* `INCOME_AMT`—Income classification
* `SPECIAL_CONSIDERATIONS`—Special considerations for application
* `ASK_AMT`—Funding amount requested
* `IS_SUCCESSFUL`—Was the money used effectively

### Optimization Process
1. 

## Results
<!-- Using bulleted lists and images to support your answers, address the following questions -->
### Data Preprocessing
* What variable(s) are the target(s) for your model?
  * `IS_SUCCESSFUL`—Was the money used effectively
* What variable(s) are the features for your model?
  * `APPLICATION_TYPE`—Alphabet Soup application type
  * `AFFILIATION`—Affiliated sector of industry
  * `CLASSIFICATION`—Government organization classification
  * `USE_CASE`—Use case for funding
  * `ORGANIZATION`—Organization type
  * `STATUS`—Active status
  * `INCOME_AMT`—Income classification
  * `SPECIAL_CONSIDERATIONS`—Special considerations for application
  * `ASK_AMT`—Funding amount requested
* What variable(s) should be removed from the input data because they are neither targets nor features?
  * `EIN` and `NAME`—Identification columns

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * Hidden layer 1: 8 neurons, 'relu' activation function
  * Hidden layer 2: 5 neurons, 'relu' activation function
  * Output layer:  1 neurons, 'sigmoid' activation function
* Were you able to achieve the target model performance?
  * No
* What steps did you take in your attempts to increase model performance?
  * 

## Summary
<!--  Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.-->
* 
