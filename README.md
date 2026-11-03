Python Guided House Price Prediction Project Read Me

Author: Marcus Hollimon

Version: 3.13

Credit for tutorial code: https://www.freecodecamp.org/news/how-to-build-a-house-price-prediction-model/

NOTE: 

The tutorial wanted to use anaconda, but I found a work around.
The main difference is needing to manually import the openpyxl library.

Purpose:

To understand more about common data science libraries like scikit-learn, matplotlib, seaborn, pandas by breaking down a tutorial's code and adding a bit more functionality to it.

Description:

This program cleans the HousePricePrediction.xlsx file and then trains a linear regression model on the 1,460 houses that have a sale price. 20% of those houses (292) are held back as a test set, and the model's predictions for them are compared with their real prices to calculate the error. The user can choose mean absolute error (MAE), mean absolute percentage error (MAPE), root mean squared error (RMSE), or R2 score. The 1,459 houses at the end of the dataset with no sale price aren't used, since there's no real price to check a prediction against. It also allows the user to chose a few different graphs to see correlations and the accuracy of the model.
