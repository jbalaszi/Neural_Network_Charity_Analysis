# Neural_Network_Charity_Analysis
Using neural networks to help the charity foundation predict where to make investments.

## Analysis Overview
Using knowledge gained over machine learning models and neural networks, the features in this dataset will be used to create a binary classifer that will tell the customer whether or not potenial applicants will be successful funded by Alphabet Soup. The dataset contains more than 34,000 organizations that have received funding from Alphabet Soup. 
This project will consist of three steps:
  1. Preprocessing the data for the neural network.
  2. Compile, train, and evaluate the model.
  3. Optimize the model.

## Results:
### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
- The variable considered the target in this module is the "IS_SUCCESSFUL" column.

2. What variable(s) are considered to be the features for you model?
- The features that will be used are very column except for "EIN" and "NAME" columns.

3. What variable(s) are neither targets nor features, and should be removed from the input data?
- The first columns removed were the "EIN" and "NAME" columns because we expect both of those features to have little effect on the outcome.


### Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation funcations did you select for your neural network model, and why?

The model was made with input features and two hidden layers. The first hidden layer has 80 neurons, the second layer has 30 nuerons, and lastly there is an outer layer. There are three activation funcations, one per layer. The 1st and 2nd hidden layers have an activation function of "relu" while the outer layer's activation function is "sigmoid".

2. Were you able to achieve the target model performance?

I was unable to achieve the 75% or above target model performance.

3. What steps did you take to try and increase model performance?

Some steps taken to increase model performance was:
- Adding hidden layers
- Changing activation type
- Changing number of neurons in each layer
