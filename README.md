# deep-learning-challenge

## Overview
The purpose of this analysis is to find a tool that can help the nonprofit foundation Alphabet Soup pick which applicants will most likely succeed with their funding. 

## Results
* Data Preprocessing
  * The 'IS_SUCCESSFUL' column was the target variable of this model.
  * All the columns except for the 'EIN', 'NAME', and 'IS_SUCCESSFUL' columns were the features for the model.
  * The 'EIN' and 'NAME' columns were removed from the input data.
* Compiling, Training, and Evaluating the Model
  * I went with two layers and 80 neurons for the first layer and 30 neurons for the second layer with relu activation for both. The output layer had a sigmoid activation. Those are the numbers I went with after multiple tries to optimize the model to reach target model performance.
  * I wasn't able to reach the target model performance.
  * I tried different number of layers to try and increase model performance.

## Summary
After a few attempts to try and optimize the model, I couldn't achieve a target predictive accuracy higher than 75% and I was only able to get it to around 72.5%. Therefore, I wouldn't recommend this model but maybe a surprived model can achieve a better accuracy. 

