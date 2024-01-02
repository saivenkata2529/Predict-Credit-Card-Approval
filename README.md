# Predict-Credit-Card-Approval
The project is total based on the banking sector. How much important the credit card of daily life for the people. How much money the customers can take money for every day on credit card. Important details
About Dataset Explanation:
A Credit Card Dataset for Machine Learning!

Context Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.

Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.

At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

columns: Ind_ID,Gender,car_Owner,Propert_Owner,Children,Annual_income,Type_Income,EDUCATION,Marital_status,Housing_type, Birthday_count,Employed_days,Mobile_phone,Work_Phone,Phone,EMAIL_ID,Type_Occupation,Family_Members

The main aim of this project is to demonstrate the basics of Data Analysis and Machine Learning.
We will follow the steps mentioned below:

1.Data Loading 
2.Exploratory Data Analysis 
3.Data Preprocessing Cleaning Blank 4
.Data Preparation --Train Test Split 
5.Training and Evaluation 
--Model Selection 
--Model Evaluation

I am used model was Random Forest
RMSE of the Random Forest Regressor: 104579.3492066565
Accuracy of the Random Forest Regressor: 0.2926829268292683

I am used Linear regeression also
RMSE of the Linear Regression model: 107787.32884777452
To determine which model is best for evaluating credit card data, we need to compare the performance of the Random Forest Regressor and the Linear Regression model based on their RMSE values:
Random Forest Regressor RMSE: 93974.29 Linear Regression Model RMSE: 107787.33 The model with the lower RMSE is considered to have a better fit because it indicates a smaller average deviation of the predicted values from the actual values. In this case, the Random Forest Regressor has a lower RMSE compared to the Linear Regression model, suggesting that it may be the better model for this particular dataset and task.
