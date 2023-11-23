This project aims to predict the price of used cars.

To do this, I've used different types of  machine learning models. 
These models include kNeighbourRegressor, support vector machines, random forest, and linear regression.
Each of these models works in its unique way to understand the relationship between different features of a car (like mileage, model year, brand, etc.) and its price. 
These models try to make predictions about the price of other used cars based on their characteristics.

Note:
Typically, a dataset is provided where we split the data into training and testing sets. 
However, in this project, the training data contains the known values of the new price of used cars. 
while the testing data is where values of new price of used car is not given (or the value is Nan).
therefore,we cannot find performance metrics since there is nothing such as predicted values and actual values.
