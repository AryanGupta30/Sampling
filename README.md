# Sampling

In this assignment we had to first balance the unbalance data then divide the data into 5 samples using 5 different sampling techniques.After which we had to apply 5 different machine learning models on each sample and find out which ML model gave the highest accuracy.

## Methods to Balance dataset

There are 2 methods to balance dataset :-
### 1. Undersampling - Sample the mojority class to the size of minority class
### 2. Oversampling - Sample the miority class to the size of moajority class

<img width="642" alt="image" src="https://github.com/AryanGupta30/Sampling/assets/100289349/f6543420-bb8d-4c6f-a538-0ae1ae67289b">

I have used Oversampling.

## Size of Samples
I have used this Formula to calculate sample size
<img width="467" alt="image" src="https://github.com/AryanGupta30/Sampling/assets/100289349/78d04c22-83c1-4ef0-92cd-cf541d511525">


sample size = 384
Hence size for 5 samples = 384*5 = 1920

## Sampling Techniques
I have used these 5 sampling techniques:-

+ Random Sampling
+ Systematic Sampling
+ Cross-val Sampling
+ Stratified Sampling
+ Bootstrap Sampling

## ML Models
Used the following 5 ML Classification Models :-
+ LogisticRegression
+ GaussianNB
+ KNeighborsClassifier
+ SGDClassifier
+ SVC

## Result

<img width="430" alt="image" src="https://github.com/AryanGupta30/Sampling/assets/100289349/61e7fc85-0a0f-4e1f-8f17-029105d231d6">

Maximum value in the matrix: 98.18
Row name at max value: KNeighborsClassifier
Column name at max value: Cross-val
