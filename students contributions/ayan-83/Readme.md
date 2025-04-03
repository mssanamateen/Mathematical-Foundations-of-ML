Features:
Brand,Model,Year,Engine_Size,Fuel_Type,Transmission,Mileage,Doors,Owner_Count,Price.

Find the algorithm which can be applied on this dataset?

Since the provided Cars dataset has a continuous output variable "Price", regression is the appropriate method to be used.
If the relationship between the features and Price is linear like with features such as Brand and Model with respect to the Price then "Multi-Linear Regression" would be apt. 
However, when considering other features like Year, Mileage, and Owner_Count with respect to the Price, which can lead to non-linear relationships, using a "Random Forest Regression model" would likely provide more accurate predictions.


Clean the dataset.

Find input and output features.

Input Features : The Dependent variables in the dataset are the Input Features.

1) Brand,
2) Model,
3) Year,
4) Engine_Size,
5) Fuel_Type,
6) Transmission,
7) Mileage,Doors,
8) Owner_Count.

Output Features : The Independent variables in the dataset are the Output Features.
1) Price.
