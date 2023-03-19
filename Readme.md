fter this pandemic caused by Covid 19, we all got to know health is a very big concern for all of us. Besides the corona, there are several more deadly diseases in the world which affects the human life. One of such disease is HEART ATTACK.
 
       Although the disease itself is not curable, but keeping " Prevention is better than Cure " I tried to create a ML model which can predict the chance of getting a heart attack when fed with current health stats.
       
       I had followed the 5 stages of the Machine learning lifecycle for the completion of the project.

1) Data Gathering - 

        I had collected the dataset from the Kaggle website which is an online platform for data scientists and machine learning enthusiasts. The dataset had around 300 records and 14 columns like blood pressure, age, gender, blood sugar level, cholesterol level etc....

2) Data Preprocessing -

       After gathering the dataset, I had to do some preprocessing to convert the raw data into usable form. I removed the duplicate records from the dayaset. I checked for the missing values but got to know that the dataset didn't contain any missing values. Since all the columns had numerical values , I didn't have to compute any categorical data. 

3) Data Analysis -

        After preprocessing the data, I did some analysis by getting some statistical measures of the data like the minimum value, maximum value, average value etc.....
        I had also plotted some histograms of various columns to analyse each column. 

4) Model Training- 

        Till this point I had got an overall idea about the data and the data is now completely ready to be trained. 
        Since the problem was to find if a person has chance of getting Heart Attack or not which is a classification problem, I used several classification algorithms like Logistic Regression , K Nearest Neighbour, Decision Tree and Random Forest for the purpose.I divided the data in 80: 20 ratio which means 80% of data was used to train the model and with the remaining 20% data, the model was tested.

5) Model Testing -

       After testing the model with the unknown 20% data using various classification algorithms, I got an accuracy of 85% using K-Nearest Neighbours.

So by using this 5 ML lifecycle stages, I completed the entire ML model.
