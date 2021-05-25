# Heart-Attack-Risk
Train a model to predict whether this person have a chance of heart attack or not.

## Introduction
###Question of Interest
You have been provided with medical data about multiple patients where each row corresponds to a unique patient. There are 2 files: `heart_train.csv` for training and `heart_test.csv` for testing. Use the data in `heart_train.csv` to train a simple machine learning model that is able to identify if a patient has a high risk of heart attack in the near future in the heart_test.csv file ( 0 = No, 1 = Yes). 



Start by doing Exploratory Data Analysis, finding any interesting insights about the data and then moving on to the modeling. The deliverables will be as follows:
• A Python/R notebook with the code and outputs for EDA, visualizations and the model
• A csv file containing the test data along with the predicted values(0/1)

#### Columns/Features of the Training data
• **Age** : Age of the patient 

• **Sex** : Sex of the patient 

• **exang**: exercise induced angina (1 = yes; 0 = no)

• **ca**: number of major vessels (0-3) 

• **cp** : Chest Pain type chest pain type 

  o Value 1: typical angina 

  o Value 2: atypical angina 

  o Value 3: non-anginal pain 

  o Value 4: asymptomatic 

• **trtbps** : resting blood pressure (in mm Hg) 

• **chol** : cholestoral in mg/dl fetched via BMI sensor 

• **fbs** : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

• **rest_ecg** : resting electrocardiographic results o Value 0: normal o Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) o Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria 

• **thalach** : maximum heart rate achieved 

• **target** : 0= no chance of heart attack 1= very high chance of heart attack

## Methods and Results

Initially EDA(Explorary Data Analysis) is done on data to understand the data better. After the data analysis if there is any missing values in the data or correlations between features. This is a binary classfication problem. I will be using logistic regression modelling. First the logistic regression model is trained on the `heart_train.csv`. Model evaluation is done to understand the model. After that it the trained model is used to predict on testing data (`heart_test.csv`)whether the person is at risk of heart attack or not.
