# cs5213s20-project-g5

Project Description

- The goal of our project is to predict the fatality rate of a person who is diagnosed with coronavirus and has a medical history of heart problems. 
- For this project, we are using a dataset Heart.csv which consists of 303 records of health data with attributes - age, sex, trestbps, chol, fbs. 
- These five attributes from the data set along with attributes count and rate are useful in generating the fatality rate of an individual with a medical history of heart problems.

Our project flow is as follows : 

Data Engineering 

- For this phase, we create two new columns Count and Rate. 
- The dataengg() function returns the rate of the person's fatality rate diagnosed with corona virus and has a history of heart problems.
- The function checks for the conditions as mentioned and increases the count if the condition is satisfied.
- Since we consider 5 features/attributes, the value of count ranges between 0 -5 
- Rate is calculated by dividing the count by 5.
- The obtained rate is the probability that a person who has a medical history of heart problems will die if he is diagnosed with corona virus.

