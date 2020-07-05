# Wine Variety Prediction using Machine Learning


## About this Repository:

This is a Machine Learning assignment. 

## Problem Statement:

To build a predictive model using the wine dataset to predict the **variety** of the wine. 


```
For example:- Cabernet Sauvignon, Pinot Noir...etc.
```

## Solution

### A complete analysis is available here : [Wine variety notebook](https://github.com/RepoMan20/wine-variety-prediction/tree/master/Data)

#### Contents: 

1. [Libraries used](#libraries)
2. [Exploratory Data Analysis](#eda)
3. [Visualizations](#viz)

<a name="libraries"></a>
## Libraries:

Libraries used :  ```
                  numpy,sklearn,pandas,matplotlib,seaborn,ppscore
                  ```


<a name="eda"></a>
## Exploratory Data Analysis (EDA)

1. Data cleaning
2. Features Selection
3. Feature encoding

<a name="eda"></a>
## Selection of model 

Since majority of the dataset consists of categorical data, classification algorithms were used to strengthen the predictive power of the model.

Here two models were built viz: 

1. **Decision Tree Classifier**
2. **Random Forest Classifier**

To determine the best model to use for this classification problem, a comparison was done between both the models.

The final result -  **Random Forest classifier** performed slightly better than the **Decision Tree Classifier** in terms of accuracy.

<a name="viz"></a>
## Visualizations

1. Visualization & actionable insights on predicted Test Data is available in .ipnyb* format under Data folder   (Visualizations_on_predicted_test_data.ipynb)

2. Visualization & actionable insights on  Train Data is available in .ipnyb* format under Data folder 
(Visualizations_on_train_data.ipynb)

3. Please refer the visualization folder for images of visualiztion of train data : [Visualization](https://github.com/RepoMan20/wine-variety-prediction/tree/master/Visualization_images)



## Data
Please refer the Data folder : [Data](https://github.com/RepoMan20/wine-variety-prediction/tree/master/Data)

**Please Note: Original Train data (the file 'train.csv' has been zipped into a compressed folder 'train.zip' due to upload file size limitations in Github) ** 

## @Authors

* **Vishak G** - (https://github.com/RepoMan20)


## Acknowledgments
* Readme boilerplate - [PurpleBooth](https://github.com/PurpleBooth)

