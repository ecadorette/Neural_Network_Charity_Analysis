# Neural_Network_Charity_Analysis
Module20

## Overview
The purpose of the analysis is to build a neural network model for Alphabet Soup that can predict if an applicant will receive funding from the company. The dataset provided includes information on organizations that have previously received funding.

## Results

### Data Preprocessing
-The variables that are considered the targets for this module are the APPLICATION_TYPE and CLASSIFICATION columns from the datase.

-The variable considered the feature is the IS_SUCCESSFUL column from the dataset.

-The EIN and NAME columns were initially removed as they are not needed for the module.

### Compiling, Training, and Evaluating the Model
-For the most successful model, I had three hidden layers, layer one had 40 neruons, layer two had 20 neurons, and layer three had 10 neurons. There was only one activation function. I found that a higher number of neruons per layer slightly improved the accuracy.

-I was not able to achieve target performance, I only got to 60% accuracy. However I was able to improve the model with each attempt.

-Some steps I took to try and improve the model included changing the cutoff limit for binning for both Applicaiton_Type and Classification columns, changing the number of nerons for each layer, adding an extra hidden layer, changing the activation function, and increasing the number of epochs.

# Summary
Overall, I would not call the current model a success as it only has an accuracy rate of 60%. This model would need more work before presenting to the client for use.I think it would help to gain a better understanding of the dataset in order to better leverage the targets and variables as well as what data can be eliminated as noise. 
