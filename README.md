# Housing_prices Project

For this project I will try to find the best machine learning model that can predict the housing prices.  

# Columns    
Column Name | Description
------------ | -------------
Rooms	| Number of rooms	
Price	| Price in dollars	
Method	|
S	| Property sold
SP	| Property sold prior
PI	| Property passed in
PN	| Sold prior not disclosed
SN	| Sold not disclosed
NB	| No bid
VB	| Vendor bid
W	| Withdrawn prior to auction
SA	| Sold after auction
SS	| Sold after auction price not disclosed.
N/A	| Price or highest bid not available
Type	|
br |	Bedroom(s)
h	| House, cottage, villa, semi, terrace
u | Unit, duplex
t	| Townhouse
dev site	| Development site
o res	| Other residential.
SellerG | Real Estate Agent	
Date	| Date sold	
Distance	| Distance from CBD	
Regionname	| General Region (West, North West, North, North east …etc)	
Propertycount	| Number of properties that exist in the suburb.	
Bedroom2 	| Scraped # of Bedrooms (from different source)	
Bathroom	| Number of Bathrooms	
Car	| Number of carspots	
Landsize	| Land Size	
BuildingArea	| Building Size	
CouncilArea	| Governing council for the area	

# Summary of the solution:
## 1. Data overview:
   1. Data type
   2. Number of columns and rows
   3. Find missing values and fill missing values
      * Label encoder
      * Frequency encoder
   4. Data description and statistical summary
   5. Find outliers and drop them
## 2. Data Analysis Exploration (EDA)
   1. Pairplot and correlation heatmap
   2. Boxplot for bathrooms and prices
   3. Boxplot for bedrooms and prices 
   4. Boxplot for carspots and prices
   5. Boxplot for housing type and prices
   6. Housing price Distribution
## 3. Setting up the data for machine learning
   1. Data train test split
       * Sklearn.cross_validation
   2. Model train
       * Linear Regression Model
       * Decision Tree Regressor Model
       * Random Forest Regressor Model
## 4. Model predection
## 5. Model evaluations
   * Score
   * Mean Absolute Error
