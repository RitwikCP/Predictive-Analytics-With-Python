# RESTAURANT REVENUE PREDICTION - USING REGRESSION MODELS

![zyro-image (14)](https://user-images.githubusercontent.com/94697656/204720584-2c3aed6c-70af-4081-a60a-af787e039647.png)

## REGRESSION MODELS USED
#### MULTIPLE LINEAR REGRESSION
Multiple Linear Regression is one of the important regression algorithms which models the linear relationship between a single dependent continuous variable and more than one independent variable. It is one of the most common types of predictive analysis. This type of analysis allows one to understand the relationship between a continuous dependent variable and two or more independent variables. The independent variables can be either continuous (like age and height) or categorical (like gender and occupation). It's important to note that if the dependent variable is categorical, then one should dummy code it before running the analysis.

#### POLYNOMIAL REGRESSION
Polynomial regression is a kind of linear regression in which the relationship shared between the dependent and independent variables Y and X is modeled as the nth degree of the polynomial. This is done to look for the best way of drawing a line using data points. The algorithm of linear regression works only when the regression in the data is linear. Polynomial regression can be considered one of the exceptional cases of multiple linear regression models. In other words, it is a linear regression type containing dependent and independent variables, and they both share a curvilinear relationship. A polynomial relationship is fitted in the data.
Also, several linear regression equations are converted into polynomial regression equations by including numerous polynomial elements. 


#### DECISION TREE

A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes. A decision tree starts with a root node, which does not have any incoming branches. The outgoing branches from the root node then feed into the internal nodes, also known as decision nodes. Based on the available features, both node types conduct evaluations to form homogenous subsets, which are denoted by leaf nodes, or terminal nodes. The leaf nodes represent all the possible outcomes within the dataset. Decision tree learning employs a divide and conquer strategy by conducting a greedy search to identify the optimal split points within a tree. This process of splitting is then repeated in a top-down, recursive manner until all, or the majority of records have been classified under specific class labels. 


#### RANDOM FOREST
Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression. One of the most important features of the Random Forest Algorithm is that it can handle the data set containing continuous variables as in the case of regression and categorical variables as in the case of classification. It gives better results for classification problems. We know that a forest comprises numerous trees, and the more trees more it will be robust. Similarly, the greater the number of trees in a Random Forest Algorithm, the higher its accuracy and problem-solving ability.  Random Forest contains several decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset. It is based on the concept of ensemble learning which is a process of combining multiple classifiers to solve a complex problem and improve the performance of the model.


### DATASET
TFI has provided a dataset with 137 restaurants in the training set, and a test set of 100000 restaurants. The data columns include the open date, location, city type, and three categories of obfuscated data: Demographic data, Real estate data, and Commercial data. The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. 

##### Data fields
1. Id : Restaurant id. 
2. Open Date : opening date for a restaurant
3. City : City that the restaurant is in. Note that there are unicode in the names. 
4. City Group: Type of the city. Big cities, or Other. 
5. Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile
6. P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.
7. Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values. 

### PROBLEM
Given this dataset, predict the revenue of the restaurants using regression models.

### OBJECTIVE
To develop multiple regression models and predict the revenue of the restaurants.

### MOTIVATION
To learn and implement multiple regression models using a hands-on approach.

### RESULTS OBTAINED
* Multiple Linear Regression
    * Train MSE: 0.12075529195820595
    * Test MSE: 0.3192631654626014
* Polynomial Regression
    * Train MSE: 2.2117054370233137e-29
    * Test MSE: 0.3297153742895021
* Decision Tree
    * Train MSE: 0.0
    * Test MSE: 0.33592637911963047
* Random Forest
     * Train MSE: 0.024438153818975995
     * Test MSE: 0.24601449219628901
* Random Forest with most important features
     * Train MSE: 0.025106891923101293
     * Test MSE: 0.24442905583046876

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)
