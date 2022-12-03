# poland-cars-sales-EDA

* Exploratory data analysis for poland cars(200k) advertisement on OTOMOTO website from kaggle:
https://www.kaggle.com/datasets/bartoszpieniak/poland-cars-for-sale-dataset

This dataset is rich with many information:208,304 observations of 25 variables.
The most important attributes for this dataset were: Price, Condition, Vehicle_Brand, Production_year, Mileage_km, Power_HP, Transmission, Fuel_type.

The project goals are to do Exploratory data analysis and visualization to get some insights about these cars, their prices, their popularity, also to learn about visualization best techniques and to do some modeling on this data.

We started with
Data cleaning:

First steps:
Removed the columns contained many nulls.
Fill the columns that can be imputed or filled with some pattern.
Remove the remaining Null rows from the data set to continue in the EDA.

Second steps:
Remove outliers for the columns and visualize them to gain more insights about the data.


Data preparation:
Make the columns have the same format.

EDA:
* Get top 10 brands that have the most ads in this dataset.
* Split the data into those brands.
* Try to get some relation between Price and other attributes like Mileage_km.

Data exploration questions:
1. Does the fuel_type affects the price: yes some fuel type like hydrogen are the most expensive cars.
2. What is the most 10 famous brands in poland?
3. Does the production_year affects the price? yes old cars are relatively lower in price.
4. Does the horsepower can change the price?
5. Most expensive brands.
6. How the attributes are correlated to each other ( that helps in feature engineering).
7. How the transmission affects the price ?

