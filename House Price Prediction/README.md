# HOUSE PRICE PREDICTION - USING REGRESSION MODELS

![zyro-image (13)](https://user-images.githubusercontent.com/94697656/204715344-0a2219e1-0d8f-44c8-acaf-71e67c9c7c9f.png)


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
The dataset is called Ames Housing dataset. It containes over 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, all in csv format.

Here's a brief version of what you'll find in the data description file.

1. SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
2. MSSubClass: The building class
3. MSZoning: The general zoning classification
4. LotFrontage: Linear feet of street connected to property
5. LotArea: Lot size in square feet
6. Street: Type of road access
7. Alley: Type of alley access
9. LotShape: General shape of property
10. LandContour: Flatness of the property
11. Utilities: Type of utilities available
12. LotConfig: Lot configuration
13. LandSlope: Slope of property
14. Neighborhood: Physical locations within Ames city limits
15. Condition1: Proximity to main road or railroad
16. Condition2: Proximity to main road or railroad (if a second is present)
17. BldgType: Type of dwelling
18. HouseStyle: Style of dwelling
19. OverallQual: Overall material and finish quality
20. OverallCond: Overall condition rating
21. YearBuilt: Original construction date
22. YearRemodAdd: Remodel date
23. RoofStyle: Type of roof
24. RoofMatl: Roof material
25. Exterior1st: Exterior covering on house
26. Exterior2nd: Exterior covering on house (if more than one material)
27. MasVnrType: Masonry veneer type
28. MasVnrArea: Masonry veneer area in square feet
29. ExterQual: Exterior material quality
30. ExterCond: Present condition of the material on the exterior
31. Foundation: Type of foundation
32. BsmtQual: Height of the basement
33. BsmtCond: General condition of the basement
34. BsmtExposure: Walkout or garden level basement walls
35. BsmtFinType1: Quality of basement finished area
36. BsmtFinSF1: Type 1 finished square feet
37. BsmtFinType2: Quality of second finished area (if present)
38. BsmtFinSF2: Type 2 finished square feet
39. BsmtUnfSF: Unfinished square feet of basement area
40. TotalBsmtSF: Total square feet of basement area
41. Heating: Type of heating
42. HeatingQC: Heating quality and condition
43. CentralAir: Central air conditioning
44. Electrical: Electrical system
45. 1stFlrSF: First Floor square feet
46. 2ndFlrSF: Second floor square feet
47. LowQualFinSF: Low quality finished square feet (all floors)
48. GrLivArea: Above grade (ground) living area square feet
49. BsmtFullBath: Basement full bathrooms
50. BsmtHalfBath: Basement half bathrooms
51. FullBath: Full bathrooms above grade
52. HalfBath: Half baths above grade
53. Bedroom: Number of bedrooms above basement level
54. Kitchen: Number of kitchens
55. KitchenQual: Kitchen quality
56. TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
57. Functional: Home functionality rating
58. Fireplaces: Number of fireplaces
59. FireplaceQu: Fireplace quality
60. GarageType: Garage location
61. GarageYrBlt: Year garage was built
62. GarageFinish: Interior finish of the garage
63. GarageCars: Size of garage in car capacity
64. GarageArea: Size of garage in square feet
65. GarageQual: Garage quality
66. GarageCond: Garage condition
67. PavedDrive: Paved driveway
68. WoodDeckSF: Wood deck area in square feet
69. OpenPorchSF: Open porch area in square feet
70. EnclosedPorch: Enclosed porch area in square feet
71. 3SsnPorch: Three season porch area in square feet
72. ScreenPorch: Screen porch area in square feet
73. PoolArea: Pool area in square feet
74. PoolQC: Pool quality
75. Fence: Fence quality
76. MiscFeature: Miscellaneous feature not covered in other categories
77. MiscVal: $Value of miscellaneous feature
78. MoSold: Month Sold
79. YrSold: Year Sold
80. SaleType: Type of sale
81. SaleCondition: Condition of sale


### PROBLEM
Given Ames Housing dataset, predict the price of the house using regression models.

### OBJECTIVE
To develop multiple regression models and predict the price of the house.

### MOTIVATION
To learn and implement multiple regression models using a hands-on approach.

### RESULTS OBTAINED
* Multiple Linear Regression
    * Train MSE: 0.008506752500576458
    * Test MSE: 0.03444764103925788
* Polynomial Regression
    * Train MSE: 4.581046178560643e-22
    * Test MSE: 4.366868219461629
* Decision Tree
    * Train MSE: 9.262554660129297e-33
    * Test MSE: 0.050736391964679224
* Random Forest
     * Train MSE: 0.002635599298509284
     * Test MSE: 0.024350114657155735
* Random Forest (with most important features)
     * Train MSE: 0.004333614774789146
     * Test MSE: 0.03493676670772804

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)
