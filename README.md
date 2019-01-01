# PyScience
PyScience is a library that is aimed to help data scientists find the model that best fits the data. Although most of the features are already provided by the [scikit-learn package](https://scikit-learn.org/stable/) , we introduce a more complete and compact set of utilities that include basic optimisation (achieved by means of [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)), scaling and introduction of dummy variables when needed. A basic summary with additional basic plots of the results are included.

## Classification
For classification problems we provide
- random forest classification
- logistic regression
- nearest neighbours classification

![Alt text](gallery/cm.png?raw=true "cm")

## Regression
For regression problems we provide
- random forest regression
- linear regression
- nearest neighbours regression

![Alt text](gallery/regression_forest.png?raw=true  "regression_forest")

## Time series

- time series and ARIMA models

![Alt text](gallery/ARIMA.png?raw=true "ARIMA")

## How to use it
The code is written for python3.X only and the data must be in `pandas DataFrame` format.

The response variable column name must be `"actuals"` in the data file, whereas there is no restriction on the types and names for the predictors.

A `run.py` is provided: simply provide the name of the algorithm you want to run and the path to the data file you want to run it on. 