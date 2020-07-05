#  Automate detection of different emotions from paragraphs and predict overall emotion 


## About :

This project is part of an Internship (TCS iON RIO 210 ) 

## Problem Statement:
RIO-210: Automate detection of different emotions from paragraphs and predict overall emotion - (Batch 01)



## Solution

### A complete analysis is available here : [emotion-prediction-notebook](https://github.com/RepoMan20/Automate-detection-of-emotions-using-ML/tree/master/models)

#### Contents: 

1. [Libraries ](#libraries)
2. [Models ](#models)

<a name="libraries"></a>
## Libraries:

Libraries used :  
                  ```
                  Core libraries: numpy,sklearn,pandas,matplotlib
                  ```
                  <br />
                   ```
                  Machine Learning / NLP Libraries  : Sci-kit Learn(sk-learn), NLTK
                  ```
                  <br />
                  ```
                  Deep Learning Libraries : Tensorflow, Keras
                  ```
## Embeddings : 
Fasttext pre-trained (english) word vectors were also used as embeddings: https://fasttext.cc/docs/en/english-vectors.html


## Flow:- 
1. Data cleaning
2. Data pre-processing
3. Feature Selection
4. Stopwords removal 
5. Feature Encoding
6. Creating Bag-of-words(BoW) model 
7. Final Model creation

<a name="models"></a>
## Selection of model 

Since the dataset consists of categorical data, classification algorithms were used to strengthen the predictive power of the model.

Here two models were built viz: 

1. **Multinomial Naive Bayes**
2. **Random Forest Classifier**
3. **Support Vector Machine(SVM)**
4. **SGD classifier**
5. **Logistic Regression**


## Result:
To determine the best model to use for this classification problem, a comparison was done between all of the models.

The final result - **LSTM** model wins in the deep learning category for this task!   

1) Machine Learning: **SGD classifier** performed slightly better as compared to all  the other models in terms of accuracy.

2) Deep Learning:  **LSTM Architecture** provided the best results for predicting overall emotion from text, even better than SGD



## Data
Please refer the Data folder : [Data](https://github.com/RepoMan20/Automate-detection-of-emotions-using-ML/tree/master/datasets/crowdflower-sentiment-analysis-in-text)


## @Authors

* **Vishak Gopkumar** - (https://github.com/RepoMan20)


