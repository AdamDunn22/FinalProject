# Machine Learning Model

### Description of preliminary data preprocessing
First, we removed any records with a null value in them and we removed all duplicate idperson. We then identified that for the following variables smokerid and drinkerid 
had a "no info" record; we decided to remove any record that had "no info" as we regarded this as a null value. We also encoded some of the columns' smokerid,
drinkerid, and famhistid as they offered responses and so we used each response as a new column with a response of 0 = No, and 1 =Yes. We also had to account
for the data being undersampled with people that had diabetes and needed to account for it using the various undersampling and oversampling functions in particular the SMOTE function gave us the best results..

### Description of preliminary feature engineering and preliminary feature selection, including their decision-making process
The preliminary features that we decide to focus on if there was a family history of diabetes, the patient's current health such as their weight, 
BMI, and cholesterol; we also wanted to focus on activities that have a long-lasting effect on someone's health namely smoking and drinking. 

### Description of how data was split into training and testing sets
We split the data 20% for training and 80% for testing, the reason being that we had 57000+ records giving us enough to train the model and to test it with.

### Explanation of model choice, including limitations and benefits
Originally to help predict whether someone has diabetes or not we decided to use a supervised model, namely a KNN model. The reason being we are trying to find a discrete outcome.

* Benefits
	* The KNN model is simple and easy to understand
	* The model has no assumptions
	* KNN models can adapt as more data is inputted
* Limitations
	* As the dataset grows the model gets slower when running
	* It is very sensitive when dealing with outliers
	* It has issues with dealing with imbalanced data

But we then decided on using the Balanced Random Forest Classifier as the data we had was imbalanced as a majority of the patients did not have diabetes, this caused the KNN model to have high accuracy and percision for predicting if some one did not have diabetes but the accuarcy and percision were low for predicting if someone had diabetes. Also, since we are dealing with peoples bodies everyone is different and that gave us some outliers.

So in the end we decided to use a Balanced Random Forest Classifier as we felt the Pros and Cons ssuited our data better.
* Pros
	* Able to work with outliers
	* Can work with a large dataset.
	* Better accuracy than other classification algorithms.
	* Low risk of overfitting.
* Cons
	* Random forests can be bias to categorical variables.
	* Not easy to interpret
