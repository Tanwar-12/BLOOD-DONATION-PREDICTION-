# BLOOD DONATION PREDICTION 
![image](https://github.com/Tanwar-12/Blood-Donation-Prediction/assets/110081008/3044efa0-e619-47c4-b55b-67463ca2e9a9)


##  BUSINESSCASE : Predict the person will donate blood or not.
### ABOUT DATASET :
*This data set is about blood donation prediction.This dataset contains blood donation details of regular university visits. The goal is to predict whether the person has donated blood in March 2007. The target is to predict whether a donor will give blood the next time in the blood donation campaign held at the university campus.*

### IMPORTING THE NECESSARY LIBARARIES

## LOADING THE DATA

## DOMAIN ANALYSIS:

**Basic understanding of features:**

1.Unnamed:0 :-This column represents the donor's unique ID.

2.Months since Last Donation :: This is the number of months since this donor’s most recent donation.

3.Number of Donations :This is the total number of donations that the donor has made.

4.Total Volume Donated (c.c.) :: This is the total amount of blood that the donor has donated in cubic centimetres.

5.Months since First Donation ::This is the number of months since the donor’s first donation.

6.Made Donation in March 2007 ::A binary variable representing whether he/she donated blood in March 2007 (1 stands for donating

blood; 0 stands for not donating blood)

### BASIC CHECKS
## EXPLORATORY DATA ANALYSIS:
### UNIVARIATE ,BIVARIATE ANALYSIS & MULTIVARIATE ANALYSIS
![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/d329328a-568c-4f03-9fd4-bf135cead3a1)

![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/2558c12a-0b4a-4773-92c8-000c93c01feb)

![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/80fa27ed-0a21-49cd-8aa6-7bd8b12882e6)

![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/73d96432-87d9-49ce-9cda-879a49cf5ae3)

![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/7092a7c3-b217-4bf9-827c-e02925df6904)

## FEATURE ENGINEERING & DATA PREPROCESSING
![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/c2135fe1-23a6-4700-ae1c-5c01d6572d6f)

### CHECKING OUTLIERS:
![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/92338463-8277-4f46-8302-fa8f633ecf8c)

## SPLIT THE X AND Y
## MODEL CREATION
### MODEL SCORES:
* 'Logistic Regression': 0.6458333333333334,
*  'KNN': 0.7013888888888888,
* 'SVC': 0.6597222222222222,
* 'Decision Tree Classifier': 0.7013888888888888,
* 'RandomForestClassifier': 0.6944444444444444,
* 'XGBClassifier': 0.7222222222222222

  ![image](https://github.com/Tanwar-12/BLOOD-DONATION-PREDICTION-/assets/110081008/f51df2b6-a188-4e27-8186-0dbca36ec3d6)


  ## CONCLUSION:
 
*We have compared the performance of various binary classification algorithms.Fit the data with 77% accuracy with the XGBoosting Classifier.Hence XGBC gives balanced accuracy in every meassures and is considered as the best model with respect to our business case.Since the dataset was small,imbalanced and with very less features ,we have come to a conclusion that the above score that we obtained is the best.*









