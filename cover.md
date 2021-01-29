# Boston House Price Prediction

## What is the notebook about?
The price of a home in a settlement is determined by several surrounding factors besides the characteristics of the building, and there are evident patterns observed. This notebook creates a Model to predict the Median house price in an area considering some of those factors.

## What algorithms are used?
* A RandomForestRegressor model is trained to predict the median price of a house.
* Sklearn's Imputation to fill missing values, and Scaling (Inputs need to be scaled for Regressors)
* Mean Squared Error (MSE) with Cross Validation to evaluate the model.

## What is the content of the notebook?
This notebook performs Exploratory Data Analysis of the Boston House Price Dataset, and proceeds with creating a pipeline to preprocess data. The preprocessed data is used to train the RandomForestRegressor model, and it is evaluated using Mean Squared Error (MSE) with Cross Validation Technique. The Model is then saved and tested on additional Testing data.
