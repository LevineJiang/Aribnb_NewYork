New York Aribnb listing Price Study
==========================

This project aims at find the key fators that affect the price of New York Aribnb properties in python with Sklearn, Pandas, Numpy libraries.

## Model selection 

I tried 3 type of Machine Learning model

Error of Linear Regression is 86.57

Error of Decision Tree is 0, overfitting

Error of Random Forest Regressor is 80.84,  and 95% confidedence interval for the test RMSE is a range from 77 to 84.

The best model in this case is Random Forest Regressor

## Recommendation
We prepare the full pipeline from cleaning data process to predict the price. 

Theoretically, Airbnb can link their data base to our algorithm to generate the new price predication.

But the algorithm need further improve before actual implant.

## Issues:
Some attributes are not correlation to price well. 

Airbnb should collect other information, such as:

Square foot of the house/apartment,

Age of the house/apartment, 

Number of rooms of the property

Number of bedrooms, number of bathrooms
