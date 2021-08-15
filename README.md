

# Overview: 

The following analysis consists of prediciting credit risk by applying six different algorithims and models from a credit card dataset from LendingClub. 

# Results:

## Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/81484054/129491875-850c2396-7003-43b5-9c00-7adc14d17f23.png)

 - The balanced accuracy score is at 65%
 - The low risk is at 100% with high risk at 1%
 - The precision is at 99%

## SMOTE Oversampling

![Screenshot (104)](https://user-images.githubusercontent.com/81484054/129491908-7c0cdbcb-9806-4fe2-b11b-4abcf36a979d.png)
![Screenshot (105)](https://user-images.githubusercontent.com/81484054/129491912-6a522765-1360-488a-9db9-a3d31511eb94.png)

 - The balanced accuracy score is at 65%
 - The low risk is at 100% with high risk at 1%
 - The precision is at 99%

##  Cluster Centroids Undersampling

![Screenshot (107)](https://user-images.githubusercontent.com/81484054/129492012-8850518f-1566-4d1d-b7f0-7fc2f36adc9a.png)
![Screenshot (106)](https://user-images.githubusercontent.com/81484054/129491986-1a361d08-6717-4202-9e1b-65d4ee0cadc0.png)

 - The balanced accuracy score is at 63%
 - The low risk is at 100% with high risk at 1%
 - The precision is at 99%

##  Combination (Over and Under) Sampling with SMOTEENN

![Screenshot (108)](https://user-images.githubusercontent.com/81484054/129492051-23c76b74-c36e-4d4b-b73c-e21f34a01268.png)
![Screenshot (109)](https://user-images.githubusercontent.com/81484054/129492065-90106117-cadf-4f4a-b008-f2315dd104a6.png)

 - The balanced accuracy score is at 51%
 - The low risk is at 100% with high risk at 1%
 - The precision is at 99%

## Balanced Random Forest Classifier

![Screenshot (112)](https://user-images.githubusercontent.com/81484054/129492331-59f1c4c8-303c-4851-8b7d-9ff66d435d3f.png)
![Screenshot (113)](https://user-images.githubusercontent.com/81484054/129492348-720371ca-5be8-41b2-bbce-6dcc6012703c.png)

 - The balanced accuracy score is at 80%
 - The low risk is at 100% with high risk at 3%
 - The precision is at 99%

## Easy Ensemble AdaBoost Classifier

![Screenshot (110)](https://user-images.githubusercontent.com/81484054/129492204-57533c35-0da3-4e73-a8e1-3ae154d8edcb.png)
![Screenshot (111)](https://user-images.githubusercontent.com/81484054/129492210-cc52390c-6484-4199-bf70-6a9d281682e8.png)

 - The balanced accuracy score is at 80%
 - The low risk is at 100% with high risk at 7%
 - The precision is at 99%

# Summary:

The following models all display a low accuracy score for LendingClub's credit card dataset. The test that resulted with the most accurate numbers would be the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier with an accuracy score of 80%. In this stage I would reccomend looking into further models or algorithms that could possibly provide a clearer accuracy score for Lendingclub.
