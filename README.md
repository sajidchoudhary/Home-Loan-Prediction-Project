#########  PROBLEM STATEMENT   ###########

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and 
after that company validates the customer eligibility for loan.
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.These details are Gender,Marital 
Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers
segments that are eligible for loan amount so that they can specifically target these customers. 



ata Dictionary
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
