# deep-learning-challenge
# Report

## Overview
This project aimed to create a predictive model that would help determine the success of funding for applicants of a nonprofit organization called Alphabet Soup. To achieve this, data was preprocessed to prepare it for modeling.

The preprocessing steps included removing any irrelevant columns that would not contribute to the prediction of the target variable. Additionally, rare variable values were binned or grouped together to reduce the number of unique values and simplify the model. Another important step  was converting categorical data into numerical data, which is necessary for many machine learning algorithms. 

The goal of the modeling process was to develop a machine learning model that could accurately predict the success or failure of funding for applicants. Overall, the goal of the project was to leverage machine learning techniques to improve the efficiency and effectiveness of the funding process for Alphabet Soup, and this was achieved  by implementing data preprocessing techniques and developing a successful predictive model.

## Results
### Data Preprocessing:

What variable(s) are the target(s) for your model?
The target variable is the "IS_SUCCESSFUL" column, which indicates whether the funding was used effectively or not.

What variable(s) are the features for your model?
The features are all the other columns except for the ones that are not relevant or do not contribute to the prediction of the target variable. The relevant features include "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".

What variable(s) should be removed from the input data because they are neither targets nor features?
The variables that should be removed are the "EIN" and "NAME" columns, which are unique identifiers that do not contribute to the prediction of the target variable.

### Compiling, Training, and Evaluating the Model:

How many neurons, layers, and activation functions did you select for your neural network model, and why?
The model has two hidden layers with 80 and 30 neurons, respectively. The activation function used for the hidden layers is "relu", and "sigmoid" is used for the output layer because it is a binary classification problem.

Were you able to achieve the target model performance?
The target accuracy was set at 75%, and the final model was able to exceed it with an accuracy of 80.05%. This means that the model is performing well and can provide valuable insights and predictions.
