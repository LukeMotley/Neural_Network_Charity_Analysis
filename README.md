# Neural_Network_Charity_Analysis

## Overview of The Analysis:

Explain the purpose of this analysis.
A deep learning neural network is used to create a binary classifer for the prediction of whether applicants of the funding organization, Alphabet Soup, will be successful or not. Alphabet Soup has funded over 34,000 organizaiton of over the years. This is the data that was used to create the neural network to predict success.

## Results:
### Data Preprocessing
* Target variable: IS_SUCCESSFUL
* Feature variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* Variables (Neither Target nor Feature): NAME, EIN
    
### Compiling, Training, and Evaluating the Model

* I kept the layers to 2 to save time. After experimenting, the final neuron count resulted in 15 and 9 and tanh and relu for the first and second layer, respectively. 

* I was not able to reach the goal without adding an unnecissary level of complexity in the number of the nuerons and layers. 

* The steps I took to improve performcance included testing various activation functions and change the number of neurons.

## Summary:
The neural network model did not reach the target accuracy of 75%. 72.9% is still close to the target, especially for keeping the number of nuerons and layers reasonably low. 
If given a chance, using a Random Forest Classifer might yield better prediction. This is because a Random Forest Classifer could help work with any outliers that might exist.  RFCs also compute faster than machine learning models, so it can be easier to use for large data sets.
