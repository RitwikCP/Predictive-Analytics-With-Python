# BREAST CANCER CLASSIFICATION- USING CLASSIFICATION MODELS

![zyro-image (15)](https://user-images.githubusercontent.com/94697656/204727407-6f8d5c41-47f4-43ab-a699-af562c07cf86.png)

## CLASSIFICATION MODELS USED
#### K-NEAREST NEIGHBOR
The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another. It's also worth noting that the KNN algorithm is also part of a family of “lazy learning” models, meaning that it only stores a training dataset versus undergoing a training stage. This also means that all the computation occurs when a classification or prediction is being made. Since it heavily relies on memory to store all its training data, it is also referred to as an instance-based or memory-based learning method.

#### GRADIENT BOOSTING MACHINE
Boosting is one of the popular learning ensemble modeling techniques used to build strong classifiers from various weak classifiers. It starts with building a primary model from available training data sets then it identifies the errors present in the base model. After identifying the error, a secondary model is built, and further, a third model is introduced in this process. In this way, this process of introducing more models is continued until we get a complete training data set by which model predicts correctly.Gradient Boosting Machine (GBM) is one of the most popular forward learning ensemble methods in machine learning. It is a powerful technique for building predictive models for regression and classification tasks. GBM helps us to get a predictive model in form of an ensemble of weak prediction models such as decision trees. Whenever a decision tree performs as a weak learner then the resulting algorithm is called gradient-boosted trees. It enables us to combine the predictions from various learner models and build a final predictive model having the correct prediction.

#### DECISION TREE

A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes. A decision tree starts with a root node, which does not have any incoming branches. The outgoing branches from the root node then feed into the internal nodes, also known as decision nodes. Based on the available features, both node types conduct evaluations to form homogenous subsets, which are denoted by leaf nodes, or terminal nodes. The leaf nodes represent all the possible outcomes within the dataset. Decision tree learning employs a divide and conquer strategy by conducting a greedy search to identify the optimal split points within a tree. This process of splitting is then repeated in a top-down, recursive manner until all, or the majority of records have been classified under specific class labels. 


#### RANDOM FOREST
Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression. One of the most important features of the Random Forest Algorithm is that it can handle the data set containing continuous variables as in the case of regression and categorical variables as in the case of classification. It gives better results for classification problems. We know that a forest comprises numerous trees, and the more trees more it will be robust. Similarly, the greater the number of trees in a Random Forest Algorithm, the higher its accuracy and problem-solving ability.  Random Forest contains several decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset. It is based on the concept of ensemble learning which is a process of combining multiple classifiers to solve a complex problem and improve the performance of the model.


### DATASET
The dataset is called Breast Cancer Wisconsin (Diagnostic) Dataset. It containes over 32 columns, giving data regarding various aspects of tumours, all in csv format.

Here's a brief info about the columns.


<img width="448" alt="Screenshot 2022-11-30 at 1 21 37 PM" src="https://user-images.githubusercontent.com/94697656/204738303-75559af0-0812-48b2-a381-ce1cdb9385f1.png">

### PROBLEM
Given Breast Cancer Wisconsin (Diagnostic) Dataset, classify tumors into malignant (cancerous) or benign(non-cancerous).

### OBJECTIVE
To develop multiple classification models and predict the price of the house.

### MOTIVATION
To learn and implement classification regression models using a hands-on approach.

### RESULTS OBTAINED
<img width="581" alt="Screenshot 2022-11-30 at 1 24 25 PM" src="https://user-images.githubusercontent.com/94697656/204738865-68e045b7-4f19-42e6-8627-14beeebf84bd.png">
<img width="696" alt="Screenshot 2022-11-30 at 1 24 34 PM" src="https://user-images.githubusercontent.com/94697656/204738846-32aec798-6ebd-4ce3-8c53-c56d009d2758.png">



### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)
