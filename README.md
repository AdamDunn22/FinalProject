# FinalProject
## Topic
Due to the Pandemic many people reviewd their life choices and how they take care of their bodies so because of that we want to see if the number of people with Diabetes has changed at all.

## Reason for Selected Topic 
Due to the Pandemic, we saw many people change how they take care of their health, as restaurants and fast food places were not allowed to have people in the restaurants since many governments enacted social distance policies. But even with the social distancing protocols, people could still "eat out" as most places used delivery apps or had a delivery service. So we hope to see if the number of people with diabetes will change because of how the Pandemic has changed how we view our health.

## Description of source of data
The datasets come from the National Health and Nutrition Examination Survey. https://www.cdc.gov/Nchs/Nhanes/about_nhanes.htm
We were able to get three datasets from a diabetes study that they had, with each dataset having the following variables (data1_patient_info.csv, data2_patient_tests.csv, data3_patients_results.csv).

* Patient Info dataset, which contains:
  * personID
  * age
  * sexID
  * height 
  * weight 
  
* Patient_tests dataset
  * BMI
  * SBP 
  * DBP 
  * FPG
  * Cholesterol
  * Triglyceride
  * HDL DECIMAL 
  * LDL DECIMAL 
  * ALT DECIMAL
  * AST DECIMAL
  * BUN DECIMAL
  * CCR DECIMAL 
  * FPG_finalvisit
 
* Patient results dataset
  * diabetes
  * smokerID 
  * drinkerID 
  * famhistID 

## Questions we hope to answer:
* What are the variables that are key identifiers in determining if someone has diabetes? 
* Has the total number of people with diabetes changed due to the pandemic?

## Project Outline:
* Patient Health and Demographic data is collected, analyzed and cleaned up using Pandas and Numpy libraries. Using Sklearn packages we created a KNN supervised machine learning model to split data and predict which patients have type 2 diabetes. Data is seperated into features and taget variables (diabetes). Features include blood pressure, BMI, age, and other factors. A confusion matrix and accuracy score are given as part of the model. 
* A dashboard is created using Javascript/HTML/CSS to display the data in an easy to view and simple format that also allows for users to interact with graphs/figures and select data. 

## Description of Communitcation Protocol
To ensure we are able to communicate with each other when we have ideas, any problems , or for any other reason we created a slack group chat. We will also meet at least once a week outside of class and more if needed. There is also a shared google folder where we can upload any resources that could be useful, and it has a document where we track all of our ideas and it allows us to go back and review each others ideas.
