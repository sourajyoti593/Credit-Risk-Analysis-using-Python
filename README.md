# Credit Risk Analysis
#### Overview
This project aims to analyze and predict credit risk using a dataset containing 14 features and 450,001 records. The focus is on understanding which factors influence loan approval/rejection (loan_status) and building machine learning models to predict the same. The analysis includes EDA (Exploratory Data Analysis), hypothesis testing, and a comparison of machine learning models such as Bagging, Boosting, Decision Tree, and Support Vector Classifier (SVC).

#### Dataset Information
The dataset consists of the following 14 columns:

Feature Name	Description
person_age	Age of the applicant
person_gender	Gender of the applicant
person_education	Education level of the applicant
person_income	Annual income of the applicant
person_emp_exp	Employment experience of the applicant (in years)
person_home_ownership	Homeownership status of the applicant
loan_amnt	Loan amount requested
loan_intent	Purpose of the loan
loan_int_rate	Interest rate on the loan
loan_percent_income	Percentage of income allocated to the loan
cb_person_cred_hist_length	Length of the applicant's credit history (in years)
credit_score	Credit score of the applicant
previous_loan_defaults_on_file	Whether the applicant has previously defaulted on a loan
loan_status	Loan status (target variable: 1 = Approved, 0 = Rejected)
