# credit-risk-classification

In this Challenge, various techniques to train and evaluate a model based on loan risk are used. A dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers is used to achieve this. 

## An overview of the analysis

The purpose of this analysis is to use machine learining models to predict loan status to predict if a loan to a borrower would be low or high risk. 

The dataset included the following factors:

- loan_size	
- interest_rate	
- borrower_income	
- debt_to_income	
- num_of_accounts	
- derogatory_marks	
- total_debt	

These factors constitute the features of the dataset (X) with loan_status as the target variable (y).

To accomplish this, the dataset is split into training and testing sets. The Logistic Regression module from SKLearn is then utilized to train the training dataset, followed by testing on the testing set to predict the loan status.

## The results

Below are the results of the Logical Regression model:

- Precision: for low-risk loans (0), the precision is 100%, and for high-risk loans (1), it is 85%.
- Accuracy: the accuracy of the model is 99%.
- Recall: the recall for low-risk loans is 99%, and for high-risk loans, it is 91%.


## A summary

Based on the results of this Logistic Regression model and the confusion matrix, it is evident that the model is very effective at predicting low-risk outcomes. However, its performance is less satisfactory for high-risk loans. Given that the objective of this machine learning exercise is to enhance the prediction of high-risk loans, it is suggested that this might not be the most suitable model to employ.