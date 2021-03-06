# Data Science portfolio by Krushna Borkar
Portfolio of data science projects completed by me for academic, self learning, and hobby purposes.
This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

## Stand Alone Projects

### 1. __[Malicious URL Detection using Machine Learning](https://github.com/kvborkar100/Data_Science_Portfolio/tree/master/test%20-%20urldetect)__
A phishing website detector(webapp) based on Random Forest algorithm. User have to enter the URL and,then the features from the URL such as alexa ranking, URL length,Domain, sub domain etc, total 27 features are extracted from URL. Then machine Learning model(Random Forest Classifier) will try to classify it into Phishing, Benign, Suspecious category. i have used dataset from UCI machine Learning Repository.It is available [here](https://archive.ics.uci.edu/ml/datasets/phishing+websites).

Tools : Python, scikit-learn, matplotlib, Django
### 2. __[Amazon Reviews Sentiment Analysis](https://github.com/kvborkar100/Data_Science_Portfolio/tree/master/Sentiment%20Analysis%20Amazon%20Reviews)__
Sentiment analysis for Amazon reviews is done using the reviews obtained from users about different products on amazon.com. The dataset consist of 3.6 million training reviews and 400k testing reviews. The is built using 80k reviews and testing is done on 20k reviews. Ensembling Learning (VotingClassifier) is used to train model with 5 different Classifiers giving accuracy of 87%. __[Dataset](https://www.kaggle.com/bittlingmayer/amazonreviews)__

## Data Analysis and Visualisation

##### Tools: Pandas, Numpy, Seaborn, Matplotlib, Plotly

### 1. __[911 Calls - Exploratory Data Analysis](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/911%20Calls%20EDA%20.ipynb)__
Exploratory Data Analysis of the 911 calls dataset hosted on Kaggle. Demonstrates extraction of useful features from different variables.

### 2. __[Internet Speed in India Data Analysis](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/Internet%20Speed%20in%20India%20-%20EDA%20final.ipynb)__
Complete Data Analysis of dataset containing more than 24 milion rows for speed testcarried out in different states in India with diffrerent technologies. Dataset is obtained from __[Open Government Data (OGD) Platform India](https://data.gov.in/)__<br>
You can find this dataset __[Here](https://data.gov.in/catalog/myspeed-crowdsourced-mobile-data-speeds)__

### 3. __[Soccer Data Analysis](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/Soccer%20Data%20Analysis.ipynb)__
This analysis is my minor project for course Python for Data science UCSanDiego edX. I have used an open dataset from Kaggle. This __[European Soccer Database](https://www.kaggle.com/hugomathien/soccer)__ has more than 25,000 matches and more than 10,000 players for European professional soccer seasons from 2008 to 2016.I have used only players table to get a specific insight from data.

## Kaggle Kernels

### 1. Titanic: Machine Learning from Disaster
Titanic: Machine Learning from Disaster is a knowledge competition on Kaggle. It is known as the the 'Hello World' on Kaggle. This is a binary classification problem where we have to predict whether passenger wil survive or not. Here is my __[kernel](https://www.kaggle.com/kvborkar100/titanic-survival-prediction)__

### 2. Big Mart Sales Predictions
Big Mart Sales Predictions data set contains data for 1559 products across 10 stores in different cities.I have built a predictive model and find out the sales of each product at a particular store.This problem is good for introdution to feature engineering __[Here](https://www.kaggle.com/kvborkar100/big-mart-sales-prediction)__ is the Kernel.

### 3. House Prices: Advanced Regression Techniques
House Prices: Advanced Regression Techniques is the knowledge competition on Kaggle. Thedataset contains many large number of features.This dataset has given me opportunity for feature transformation and data visualization. __[Here](https://www.kaggle.com/kvborkar100/house-prices-prediction)__ is my kernel

### 4.Digit Recogninzer
A classic handwritten digit recogninzer competition on Kaggle. built a CNN using keras to identify digits. The model gave 99.58% accuracy on public leaderboard with ranking 296 Top 12%. __[Kernel](https://www.kaggle.com/kvborkar100/digit-recognizer)__

## Machine Learning

### 1. __[Restaurant Reviews classification using Natural Language processing](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/Restaurant%20Reviews%20classification%20using%20NLP.ipynb)__
In this project I have built a classifier that classify a restaurant review as Good or Bad. The restaurant review dataset contains 1000 reviews with labels 1(Good) and 0(Bad).
Tools: scikit-learn, NLTK

### 2. __[Prediction of score of a Beer](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/How%20to%20choose%20perfect%20Beer.ipynb)__
In this project I have built a regression model to predict the score of a beer based on different features of the beer. dataset can be found __[here](https://www.machinehack.com/course/how-to-choose-the-perfect-beer/)__

### 3. __[Multiclass classification - to predict damage to building](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/Predict%20Damage%20to%20building.ipynb)__
In this problem I have built a model that can predict the extent of damage that has been done to a building after an earthquake. it is a multiclass classification problem. Dataset is available __[here](https://www.hackerearth.com/challenge/competitive/machine-learning-challenge-6-1/machine-learning/predict-the-energy-used-612632a9-3f496e7f/)__

## Deep Learning

### 1. __[Apparel Recognintion Analytics Vidhya](https://github.com/kvborkar100/Data_Science_Portfolio/blob/master/Identify%20Apparel.ipynb)__
Apparel classification problem on Analytics vidhya. The model is built using keras with 92.99% accuracy.
