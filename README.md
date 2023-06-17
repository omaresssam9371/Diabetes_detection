#  Diabetic Prediction Using Machine Learning Techniques

## Introduction

*Diabetes is characterized by abnormally high levels of sugar; after a meal, the amount of the blood 
glucose in the blood increase which release the insulin hormone, which stimulates the muscle and cells to use 
the blood glucose causing the blood sugar level to decrease to normal levels.

* We are going to build a model that help patients to know whether they have the disease or not  

## Data

*In out project we are focusing on classifying whether you have diabetes or not based on some main 
features the features:
 General Health  High cholesterol  Income
 Blood Pressure  Age  Education
 Body Mass Index  Heart Attack  Physical Activity
 Difficulty walking  Physical Health
 Had Stroke or not
 Mental Healt

## Data Prepration

The data used consists of 253680 records.
Data preparation process:
1. Binarize the data to be only labeled as 0 and 1.
2. Choosing the top contributing features through SelectKBest tool provided by sklearn library as 
it uses the co-matrix to determine what is the best features to use
3. Normalizing the dat
## Histograms

<img src='docs/Histogram.png' width = '800' height='600'>


## Results
We get an accuracy 85% using more than 250000 records 
There is a way we can oversample with a better accuracy 89% so the model can learn a lot about both labels
