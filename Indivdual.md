## Summary
### Topic
For our Dashboard, we wanted to try and see if we could accurately predict if someone has diabetes and what are some of the main factors that highly contribute to someone being diagnosed with diabetes. We wondered if the pandemic had caused people to review their lifestyles and if this would eventually cause a decline in people having diabetes.

### Machine Model
The Machine Model that we decided to use was the Balanced Random Forest Classifier because the dataset that we chose to use in the end, a majority of the records, were people who did not have diabetes, and the Forest Classifier is able. To fix the sampling issue, we used the SMOTE function to help balance the data.

### Results
In the end, our model got an accuracy of 98.6%, with it being 99% precise with predicting if someone does not have diabetes and it is 61% precise when indicating if someone has diabetes. We also saw that the following variables were the top five contributors for determining if someone has diabetes, FPG, age, BMI, Triglyceride, and HDL.

## Team Assessment
Our biggest strengths were our communication and organization. To ensure that we all could communicate with each other, we created a Slack group chat so we could ask questions if we had any or if we needed to meet with each other. To also help keep track of our ideas and to help organize our tasks, we used a Google Doc that we all had access to. Also, to ensure we were fine, we met every Monday to ensure we were on track and to see if anyone needed assistance with their task. The biggest challenge was ensuring that our codes could merge, as we needed help knowing what each other's variables were. To solve this issue, we met and worked together to see what each of our variables did. To help with this for next time, I would create a spreadsheet so to help organize the variable names, and then we would know what names to use, and make merging the codes easier. 

## Self Assessment
Throughout this project, I took up different roles to complete our Dashboard. At the start, I created the Github Repository and branches to organize our project; I also
helped analyze the other datasets we potentially wanted to use for our Dashboard. Another task I had was creating the machine learning model and finding the different attributes that would help improve the model's accuracy and precision. I also assisted my teammates with their roles by reviewing their code and helping with creating the tables in our SQL database by discussing what variables we thought were essential for the final table. The greatest challenge that I had for this project was
creating the connection between the SQL database with the Machine Learning Model. I overcame this challenge by researching the code to connect to the database and how you need the connection string, the database name, password, and login id.
