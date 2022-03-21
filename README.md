# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was to preprocess application data for the neural network model. After the data is preprocessed, it is complied trained and evaluated. Finally the data is optimize to analyze if there is a better training model.

## Results

### Data Preprocessing
  The variable that is the target for this model is the "IS_SUCCESSFUL column.
  The variables that are considered to be features for this model are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS"
  The EIN and the NAME column were neither targets nor features and should have been removed from the input data.

### Compiling, Training, and Evaluating the Model
  For the first model, I increased the hidden layers in 1 and 2 to 100 and 50 to see if the precentage will go down if there where more nerons to.
  The second instance I added another hidden layer to the model again seeing if more neurons would help fit the data. In the third instance, I used tanh instead of relu to see if a more complicated activation would help.
  I was unable to get the accuracy and the loss to change by any substantial amount.
  I altered the "Define the model.." step to add more nerons to the hidden layers, change the activation and add a hidden layer.

## Summary
This model was unable to reach the target of 75% accuracy and did not seem to budge when adjustments were made. Random Forest may be complicated enough with the intricacies of the the descion trees to make a difference and change the accuracy and loss.
