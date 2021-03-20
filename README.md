# MachineLearningModels
This repository contains a few ML models made by me using Datasets available online to sharpen my Machine Learning skills and as a practice.<br />
Open to suggestions and any contribution to the repository for making the Models more accurate.

# 1)Titanic Dataset
### https://www.kaggle.com/brendan45774/test-file
### We have to make a model to predict whether a particular passenger onboard the titanic would survive the crash or not based on certain parameters and attributes given in the dataset.
## Type: 
Supervised Learning: Regression
## Model: 
Support Vector Regression(SVR)
## Accuracy: 
Accuracy obtained using SVR is 95.41%.
## Comments: 
After trying various regression algorithms, the SVR model gives the best accuracy.Though models like Random Forest,Decision Tree and other were giving 100% accuracy but that may lead to over-fitting and hence the SVR model is considered as it gives the next highest accuracy.
<br />

# 2)Stroke Analysis Dataset
### https://www.kaggle.com/fedesoriano/stroke-prediction-dataset
### This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
## Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
## Type: 
Supervised Learning: Classification
## Model: 
Random Forest Classifier
## Accuracy: 
Accuracy obtained using Random Forest Classifier is 99.09%.
## Comments: 
After trying various classification models,I concluded that the Random Forest Classifier gives the best accuracy.
<br />

# 3)Groceries Dataset
### https://www.kaggle.com/irfanasrullah/groceries
### Each row in this dataset consists of different items bought by a customer and using this data we can associate different pair of items generally bought together.This can be used for market analysis by grocery store vendors who can then formulate a method to increase the amount bought by their customers either by placing these items in close proximity or further apart.
## Type: 
Unsupervised Learning: Association Rule Learning
## Model: 
Apriori Association Rule Learning Models
## Comments: 
We have used the apriori model to associate pairs of items frequently bought by the customers.
<br />

# App Info

### Author [Yash Jhaveri](https://www.linkedin.com/in/yash-jhaveri-3b0882192/)