# Big_Mart_Sales_Prediction
## Introduction
We develop regression model to predict Big mart sales to find out the sales on test data of each product at a particular store. BigMart has collected sales data from the year 2013, for 1559 products across 10 stores in different cities. Where the dataset consists of 12 attributes like Item Fat, Item Type, Item MRP, Outlet Type, Item Visibility, Item Weight, Outlet Identifier, Outlet Size, Outlet Establishment Year, Outlet Location Type, Item Identifier and Item Outlet Sales. Out of these attributes response variable is the Item Outlet Sales attribute and remaining attributes are used as the predictor variables.

 We use different Machine Learning algorithms (Linear Regression, K-Nearest Neighbor, Decision Tree, Random Forest Regressor, XG Boost) to predict the outlet production sales. XG Boost is the best model its r2 score is 76.84. 
 
 This dataset is taken from kaggle.com
 
 ## Dataset Details
 The data has 8523 rows of 12 variables.

### Variable - Details
* Item_Identifier- Unique product ID
* Item_Weight- Weight of product
* Item_Fat_Content - Whether the product is low fat or not
* Item_Visibility - The % of total display area of all products in a store allocated to the particular product
* Item_Type - The category to which the product belongs
* Item_MRP - Maximum Retail Price (list price) of the product
* Outlet_Identifier - Unique store ID
* Outlet_Establishment_Year- The year in which store was established
* Outlet_Size - The size of the store in terms of ground area covered
* Outlet_Location_Type- The type of city in which the store is located
* Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
* Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

Data science concepts used in this project-

* Data loading
* Data Cleaning
* Data Analysis and Visualization
    - Univariate Analysis
    - Bivariate Analysis
    - Multivariate Analysis
* Outliers Detection and Cleaning
* Feature Engineering
    - Label Encoding
* Machine learning models
* GridSearchCV for hyperparameter tuning

Tools used in this project

* Python
* Numpy and Pandas
* Matplotlib for Data visualization
* Seaborn for plotting graphs
* Sklearn for model building
* Jupyter Notebook

## Dataset Reference

* Big Mart Sales Prediction
* We also upload the csv file of this project [Test.csv](https://github.com/HimanshuTinker555/Big_Mart_Sales_Prediction/files/10831686/Test.csv)
