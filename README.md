# Survey misrepresentation prediction
The purpose of this project is to detect misrepresentation of the response in a survey data set.
The assumption is that individuals who share similar attributes will be predicted into the same class using a high performance predictor. The responses which differ significantly could be labelled as misrepresentation and subjected to other tests for confirmation. This will also help to reduce the number of individuals that will be subjected to expensive time consuming laboratory test.

The misrepresentation was detected using difference between the actual survey response and the predicted survey response
using the other variables in the survey data. 
The risk is that the misrepresentation reduces the value of the survey results and conclusions drawn from the survey.

A supervised machine learning predictive model was built using the survey data and predicted categorical response class.
The misrepresentation of the response variable given by each respondent was evaluated using the residual difference 
between model prediction and the actual response of the individual respondent.
The target variable in this project is made up of categorical values. 
The prediction features (variables) consists of numerical and text viables which have been ransformed in feature enginnering for model building task.
The best classification model preformance on test data is 95 percent
