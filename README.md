# Bank Marketing Analysis
[UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is predict if the client will subscribe a term deposit and how to find and target the customers
using the given parameters to improve the direct marketing campaigns in future.

## Project Description
* We have performed exploratory data analysis on dataset and created new features using bucketizing on age, min max scaling on   numerical features.
* The dataset was imbalanced with large no and few yes values on output/y column. We balanced the dataset adding weights to     each row of the dataset.
* We have also ran Gradient boosting algorithm,Random Forest,Logistic Regression and SVC models on the dataset and passed        weightcol =weight for balancing the dataset.

### Methods Used
* Feature Extraction
* Machine Learning models
* Predictive Modeling 


### Technologies
* Pyspark
* PysparkSql
* Pandas
* DataBricks

## Needs of this project
- Exploratory DAta Analysis
- Data PreProcessing 
- Feature Extraction -->Age_bucket,pdays_new, min max scaling
- Data Splitting
- Feature Preprocessing
- Feature Selection
- Model Training and Evaluation
- Model Ensemble
- Evaluation on held out data
- writeup/reporting

# Business Conclusion:
We found out that numerical features like consumerpriceindex, employeevarrate, pdays, housing_index, default_index, previous, contact_index, euribor3m, nremployed, campaign have high correlation with clients subscribing to term deposit.Based on these , we can prepare for the future markerting champaign
