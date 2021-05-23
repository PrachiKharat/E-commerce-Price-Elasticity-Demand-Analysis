# E-commerce Price Elasticity Demand Analysis
 Analyze price tendencies and the impact in the ad impression demand by pricing variation through time in various e-commerce platforms for brands among similar electronic products
# Content 
## Part 1 .- Exploratory Data Analysis
 
- ### 1.1.-Price Exploratory Data Analysis

This price exploratory analysis was executed for following reasons:

- Product Condition Selection
- Price Outlier Detection
- Price Distribution Analysis
- Discount Price Correlation with Impression Total Count per Category
- Merchant (e-commerce) Impression Time Analysis

#### Libraries 

- **seaborn, Matplotlib, Pandas and Numpy**  

Price Distribution Plot     | Price Discount Correlation Heatmap
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/distplot.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/heatmapdisc.png)

## Part 2 .-  Price Elasticity and Cross-Price Elasticity of Ad Impression Demand ##

- ### 2.1 Price Elasticity of Ad Impression Demand
In following analysis, we would select Best Buy products as main data sample for our price elasticity analysis. For future reference,this model can be implemented in every kind of vendors by e-commerce or brick and mortar by measuring sales demand

 **Hypothesis Proposed**

 From Bestbuy laptop sample data in 2017. Is ad impression demand sensitive to its own product price changes? If yes, by how much ad impression demand is sensitive to price change?
 

 
#### Machine Learning Model

- Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Laptop, Desktop Price Elasticity     |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/PE.png)


- ### 2.2 Cross-Price Elasticity of Ad Impression Demand

 **Hypothesis Proposed**

 How much is ad impression demand influenced by main competitors when they change their prices?
 This model help us to know the naturality of competition between prices of our own price product advertised against main     competitors price product changes

#### Machine Learning Model

- Multi Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Cross-Price Elasticity of 12 Mac Book     |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/CPE1.png)
