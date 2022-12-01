# Columbia-Code-Election-Modeling
2020 Logistic Presidential Election Models for registered and non-registered states

Included in this are two ipynb files:
'non_registered_training_predictions_11_30' - this file contains a predictive support model for the 2020 United states presidential election using voterfile data for states without available voter registration data. It utilizes first a logistic regression with L1 penalization to select significant features, which are then imputed into a statsmodels logistic regression model to predict voting outcomes. 

'training_prediction_and_dataframe' - this file contains identical code as above, but for states with voter registration data. 
