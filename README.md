# Indian General Elections 2019 EDA and winner prediction

<img src = "https://github.com/yashwanth-gurram/Indian-General-Elections-2019/blob/master/Images/Lok-Sabha-Elections-2019.jpg" width = "1000">

## Overview
* Analysis of candidates in 2019 General Election in the Republic of India.
* Prediction of a candidate winning the election based on his/her features using Classification techniques.
* With over 600 Million voters voting for 8500+ candidates across 543 constituencies, the general elections in the world's largest democracy are a potential goldmine of data.

## Source
The dataset is downloaded from kaggle (https://www.kaggle.com/prakrutchauhan/indian-candidates-for-general-election-2019)

## Resources
* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn

## EDA

Below are the some of the highlights of EDA

![](https://github.com/yashwanth-gurram/Indian-General-Elections-2019/blob/master/Images/download%20(1).png)
![](https://github.com/yashwanth-gurram/Indian-General-Elections-2019/blob/master/Images/download%20(2).png)
![](https://github.com/yashwanth-gurram/Indian-General-Elections-2019/blob/master/Images/newplot.png)

## Model development
* Firstly, I split the data into train and tests sets with a test size of 20%.
* Used a standard scaler to preprocess the data.
* Then I used three classifiers namely logistic regressor, Decision tree classifier and Random Forest classifier to predict.

## Model Performance

Model | Accuracy
------|---------
Logistic Regression | 90.5%
Decision Tree | 88%
Random Forest | 92%
