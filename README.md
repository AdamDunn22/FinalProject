# FinalProject
Reason for Selected Topic: Aging population in Canada, stress on healthcare increasing, need for faster care increasing.  Ontario’s Health system is and has been under immense strain since the start of the pandemic as demand for care exploded, with wait times increasing exponentially. Our Project model provides a solution to the diagnosis of diabetes incindences within a reasonable time frame. 

Description of source of data: WHO, National Institute of Diabetes and Digestive and Kidney Diseases. 

Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: Diabetes pedigree function
* Age: Age (years)
* Outcome: Class variable (0 or 1)
Questions we hope to answer:

Machine Learning Model: Take in data from database 
and output labels for input data 
Supervised model - classification -similar to module 18 for credit risk

Features:Pregnancies: predictors.get_dummies()

Target: [‘Outcome’]
