## MACHINE LEARNING BASED CLASSIFICATION PROJECT

### Content

## PROBLEM STATEMENT

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and 
after that company validates the customer eligibility for loan.
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.These details are Gender,Marital 
Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers
segments that are eligible for loan amount so that they can specifically target these customers. 



Data Dictionary
Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status'

Variable	
Loan_ID	
Gender	
Married	
Dependents	
Education	
Self_Employed	
ApplicantIncome	
CoapplicantIncome	
LoanAmount	
Loan_Amount_Term	
Credit_History	
Property_Area	
Loan_Status	


Test file: CSV containing the customer information for whom loan eligibility is to be predicted

Variable	
Loan_ID
Gender	
Married
Dependents	
Education	
Self_Employed
ApplicantIncome	
CoapplicantIncome	
LoanAmount	
Loan_Amount_Term	
Credit_History
Property_Area	Urban/ Semi Urban/ Rural

![PngItem_1606390](https://user-images.githubusercontent.com/66259814/102383174-47d8f080-3ff1-11eb-9a0c-826a8fa986f1.png)

## Overview:
This is a Classification problem, in this project tried to predct the Applicant would get a loan approval or not. on the basis of 13 attributes and got to know that Applicant Gender, Applicant is Self_Employed or not, CoapplicantIncome, LoanAmount, Property_Area	Urban/ Semi Urban/ Rural don't matter for loan approval.

### Goal
1- Exploratory Data Analysis(EDA)
2- Handle Missing Values
3- Handle Categorical feature
4- Apply Transformation Technique's to make Normally Distributed
5- Feature Selection
6- Feature Scaling
7- Model Selection
8- Model Training
9- Hyperparameter Tuning
10- Prediction on Test Dataset 
