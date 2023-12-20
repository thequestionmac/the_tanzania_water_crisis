### The Tanzania Water Crisis

__Authored by__ Mark Njagi

---

#### Overview

In this project, we build a classification model that predicts whether or not a water pump is functional based on certain predictor variables in a bid to alleviate the water crisis in the country. The data is obtained from the Taarifa waterpoints dashboard which aggregates data from the Tanzanian Ministry of Water. The analysis adopts an iterative model of classifier building. To begin with, we define a baseline Decision Tree, evaluate its performance and thence optimize it for classification by hyperparameter tuning. Finally, we adopt a Random Forest Classifier Model, evaluate performance and make recommendations based on the results. The main metric of success for the project is chosen to be precision score.

---

#### Business Problem

The aim of this project is to model and train a classification model that most precisely predicts whether a water pump is functional or due for immediate repair based on certain predictor variables. The information generated from this study is intended to inform key government stakeholders on the occurrence of non-functional water pumps across the country, and thus enable them make timely repairs that will alleviate the problem.

--- 

#### Data Understanding and Cleaning
The data was sourced from Taarifa in collaboration with the Tanzanian Ministry of Water. The data cleaning process was made of four steps, namely: checking for duplicated values, dropping unnecessary values, handling missing data, and converting the target variable into a binary class. To prepare our data for machine learning, dummy variables were created for the categorical columns in the dataset. Additionally, the data was split into train and test datasets in order to validate the model as well as prevent data leakage. 

---

#### Modeling and Evaluation
The baseline model for our analysis was a simple Decision Tree Classifier. This classifier achieved a 99% precision score on the train data and 78% score on the test data, indicating that the model thoroughly overfitted the data and was unable to generalize to new information. After conducting hyperparameter tuning, the precision score for the optimized Decision Tree improved to 80.36%, which although was above the set metric of success, still was not the best model for our analysis. The random forest classifier, with 100 samples, proved to be the most precise classifier for our problem with a precision score of 81.35%, and is recommended for analysing waterpoint functionality.

---
