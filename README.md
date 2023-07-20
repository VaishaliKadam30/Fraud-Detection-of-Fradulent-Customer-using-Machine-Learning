# Fraud-Detection-of-Fradulent-Customer-using-Machine-Learning
Problem definition
A payment transaction dataset is provided. The task is to create an supervised machine learning to predict wether the transic were fraud.

Data Exploration
Prepare the dataset for machine learning Create an unsupervised machine learning model Measure the accurancy of the model

About Dataset
This case requires trainees to develop a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan. Data for the case is available in CSV format having 6362620 rows and 10 columns. Candidates can use whatever method they wish to develop their machine learning model. Following usual model development procedures, the model would be estimated on the calibration data and tested on the validation data. This case requires both statistical analysis and creativity/judgment. We recommend you spend time on both fine-tuning and interpreting the results of your machine learning model

Methodology
General Overview: Have a General Overview of the data EDA: Perform Exploratory Data Analysis(EDA) to gain more clear insights of the data Data Preprocessing: With the information gained after performing EDA, Preprocess the Data accordingly Model Building: Once the data is properly cleaned and preprocessed, use this data to build a Machine Learning Model Performance: Assess the Performance of the Model on the Testing data set Predictions: Make Predictions on the Testing data set

Data Understanding
step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation). type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER. amount - amount of the transaction in local currency. nameOrig - customer who started the transaction oldbalanceOrg - initial balance before the transaction newbalanceOrig - new balance after the transaction nameDest - customer who is the recipient of the transaction oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants). newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants). isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system. isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

Your task is to execute the process for proactive detection of fraud while answering following questions.

Data cleaning including missing values, outliers and multi-collinearity.
Describe your fraud detection model in elaboration.
How did you select variables to be included in the model?
Demonstrate the performance of the model by using best set of tools.
What are the key factors that predict fraudulent customer?
Do these factors make sense? If yes, How? If not, How not?
What kind of prevention should be adopted while company update its infrastructure?
Assuming these actions have been implemented, how would you determine if they work?
