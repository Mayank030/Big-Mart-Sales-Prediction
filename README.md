# Big Mart Sales Prediction using Pyhton.

The data scientists at Big Mart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

## Feature Description (X features): 

ProductID : unique product ID
Weight : weight of products

FatContent : specifies whether the product is low on fat or not

Visibility : percentage of total display area of all products in a store allocated to the particular product

ProductType : the category to which the product belongs

MRP : Maximum Retail Price (listed price) of the products

OutletID : unique store ID

EstablishmentYear : year of establishment of the outlets

OutletSize : the size of the store in terms of ground area covered

LocationType : the type of city in which the store is located

OutletType : specifies whether the outlet is just a grocery store or some sort of supermarket

## Target Variable : 

OutletSales : Sales of the product in the particular store.

## Work Flow :

Data Collection : Downloading and Loading the Dataset using pandas library

Data Pre-processing : Handling Missing Values and Encoding Categorical Features and Data Cleaning.

Data Analysis (EDA) : Visulizing Different Features and understand the Data using matplotlib and seaborn.

Splitting the Dataset : Splitting the Dataset into Training and Test Sets

XGBoost Regressor : Using XGBoost Regressor to train the model.

Evaluating the Model : Using R-Squared Metric to evaluate on the model 
