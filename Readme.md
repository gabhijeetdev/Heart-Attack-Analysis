## HEART-ATTACK-ANALYSIS 
Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India. Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play.	

Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.After this pandemic caused by Covid 19, we all got to know health is a very big concern for all of us. Besides the corona, there are several more deadly diseases in the world which affects the human life. One of such disease is  HEART ATTACK.

Although the disease itself is not curable, but keeping " Prevention is better than Cure " I tried to create a ML model which can predict the chance of getting a heart attack when fed with current health stats.

I had followed the 5 stages of the Machine learning lifecycle for the completion of the project.

## 1) Data Gathering  
I had collected the dataset from the Kaggle website which is an online platform for data scientists and machine learning enthusiasts. The dataset had around 300 records and 14 columns like blood pressure, age, gender, blood sugar level, cholesterol level etc....

## 2) Data Preprocessing 
After gathering the dataset, I had to do some preprocessing to convert the raw data into usable form. I removed the duplicate records from the dayaset. I checked for the missing values but got to know that the dataset didn't contain any missing values. Since all the columns had numerical values , I didn't have to compute any categorical data. 

## 3) Data Analysis
After preprocessing the data, I did some analysis by getting some statistical measures of the data like the minimum value, maximum value, average value etc.....I had also plotted some histograms of various columns to analyse each column. 

## 4) Model Training
Till this point I had got an overall idea about the data and the data is now completely ready to be trained. 
Since the problem was to find if a person has chance of getting Heart Attack or not which is a classification problem, I used several classification algorithms like Logistic Regression , K Nearest Neighbour, Decision Tree and Random Forest for the purpose.I divided the data in 80: 20 ratio which means 80% of data was used to train the model and with the remaining 20% data, the model was tested. 

## 5) Model Testing -
After testing the model with the unknown 20% data using various classification algorithms, I got an accuracy of 85% using K-Nearest Neighbours.
So by using this 5 ML lifecycle stages, I completed the entire ML model.
The dataset consites of 14 features.(All information taken from uci public dataset archive)

## Features In Data Set
Only 14 feature used:
1.	age
2.	sex
3.	cp
4.	trestbps
5.	chol
6.	fbs
7.	restecg
8.	thalach
9.	exang 
10.	oldpeak
11.	 slope 
12.	ca 
13.	thal 
14.	num 
#### Age : displays the age of the individual.                          			     Male=1  female=0.
#### Sex : displays the gender of the individual using the following format  
#### Chest-pain type : displays the type of chest-pain experienced by the individual using the following format :
1 = typical angina 
2 = atypical angina
3 = non - anginal pain 
4 = asymptotic
#### Resting Blood Pressure : displays the resting blood pressure value of an individual in mmHg (unit)
#### Serum Cholestrol : displays the serum cholestrol in mg/dl (unit)
#### Fasting Blood Sugar : compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)
#### Resting ECG : 0 = normal , 1 = having ST-T wave abnormality , 2 = left ventricular hyperthrophy
#### Max heart rate achieved : displays the max heart rate achieved by an individual.
#### Exercise induced angina : 1 = yes 0 = no
#### ST depression induced by exercise relative to rest : displays the value which is integer or float.
#### Peak exercise ST segment : 1 = upsloping 2 = flat 3 = downsloping
#### Number of major vessels (0-3) colored by flourosopy : displays the value as integer or float.
#### Thal : displays the thalassemia : 3 = normal 6 = fixed defect 7 = reversable defect
#### Diagnosis of heart disease : Displays whether the individual is suffering from heart disease or not : 0 = absence 1,2,3,4 = present.
## Algorithm used
1)	Logistic regression
2)	K-nearest Neighbour
3)	Decision Tree
4)	Random Forest 
## Libraries used :
1)Numpy
2)Pandas
3)Matplotlib
4)Seaborn
5)scikit learn
## Conclusion:
we got that the most effective model for prediction is Logistic Regression i.e 85%

