# LoopAcademy_ML_Workshop
![image](https://media-exp1.licdn.com/dms/image/C560BAQG3MALs09SFJA/company-logo_200_200/0/1581592144461?e=2159024400&v=beta&t=MqQp_ZwxMiwoTE00pQHCna0Yu0506mmIy7_USTxCqHc)


This repository is related to Machine Learning Workshop projects held by loop academy under the supervision of Amir Hosein Hadian Rasanan.[Loop Academy](http://loopacademy.io/).


## Project 1 : Classification task for Echocardiogram Data Set 

In this project the goal is to find out if the person survive or not according to  the proposed dataset. 
Data for classifying if patients will survive for at least one year after a heart attack is given and we are going to create pipline for this problem; starting from preprocessing tasks( like normalization,standardization ,...) to creating KNN model for the problem and evaluate our method. The link to the dataset and important notes about it is [here](https://archive.ics.uci.edu/ml/datasets/echocardiogram). I also write as many as comments for each section of this first project in the jupter notebook.


## Project 2 : Regression task for Medical Cost Personal Datasets [Kaggle Competition](https://www.kaggle.com/mirichoi0218/insurance) 

In this project we want to predict the cost of insurance using different regression algorithms here we focused on 'Linear Regression' / 'Ridge Regression' /'Lasso Regression' /'ElasticNet' /'MLP Regression' and we also compared these methods on proposed datasets.

###Dataset Columns

1.age: age of primary beneficiary

2.sex: insurance contractor gender, female, male

3.bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

4.children: Number of children covered by health insurance / Number of dependents

5.smoker: Smoking

6.region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

7.charges: Individual medical costs billed by health insurance

Final Evaluation (Accuracy): 

Linear Regression : 0.8263741406000221 %

Ridge Regression : 0.8017543931490523 %

Lasso Regression : 0.8017651593569302 %

ElasticNet : 0.804417969778704 %

MLP Regression : 0.8092914640324023 %
