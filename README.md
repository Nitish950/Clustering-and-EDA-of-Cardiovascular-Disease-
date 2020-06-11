# Clustering-and-EDA-of-Cardiovascular-Disease-

Cardiovascular disease (CVD) is a class of diseases that involve the heart or blood vessels. CVD includes coronary artery diseases (CAD) such as angina and myocardial infarction.Cardiovascular diseases are the leading cause of death in all areas of the world. Together CVD resulted in 17.9 million deaths in 2015, up from 12.3 million (25.8%) in 1990.

The dataset consists of 70,000 records of patient's data in 12 features. The target class "cardio" equals to 1,  when patient has cardiovascular desease, and it's 0, if patient is healthy.

Following analysis was carried out in this project:

* Worked with pandas to carry out initial analysis
* Carried out data cleaning by removing outliers and incorrect data
* Used seaborn and matplotlib libraries for visualization
* Utilized Sklearn and KMeans for clustering of the dataset
* Calculated BMI and it's relation with CVD and age
* Established relation between CVD and alcohol consumption in males and females



**Code and Resources used:** Python version : 3.7 Data source: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

Features:

* Age | Objective Feature | age | int (days)
* Height | Objective Feature | height | int (cm) 
* Weight | Objective Feature | weight | float (kg) 
* Gender | Objective Feature | gender | categorical code 
* Systolic blood pressure | Examination Feature | ap_hi | int 
* Diastolic blood pressure | Examination Feature | ap_lo | int 
* Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal 
* Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal 
* Smoking | Subjective Feature | smoke | binary 
* Alcohol intake | Subjective Feature | alco | binary 
* Physical activity | Subjective Feature | active | binary 
* Presence or absence of cardiovascular disease | Target Variable | cardio | binary 


