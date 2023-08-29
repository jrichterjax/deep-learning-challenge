# Neural Network Model Report

## Overview of the Analysis

The purpose of this analysis is to create a tool that can help a foundation determine which applicants have the best chance of success if provided funding.

## Results

* Data Preprocessing

    * The target variable for the model is whether the result of funding was successful ("IS_SUCCESSFUL"). 

    * The features for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

    * EINs and organization names were removed because they are neither targets nor features.

* Compiling, Training, and Evaluating the Model

    * The original model created includes 2 hidden layers, 112 neurons, and 2 activation functions.

    * In the original model (65% accuracy), target model performance was not achieved. 
    
    * After adjustments were made, target model performance was achieved (91% accuracy).  

    * To increase performance, a third hidden layer was added, the number of nodes was increased, and the number of epochs was increased.

    

