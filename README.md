# LoanApprovalPrediction
This is an end -to-end machine learning project in python for precise loan approval prediction based on historical data &amp; applicant’s key features.

The dataset contains 13 features : 

1) Loan	 - A unique id 
2) 	Gender	 - Gender of the applicant Male/female
3)	Married	 - Marital Status of the applicant, values will be Yes/ No
4)	Dependents  -	It tells whether the applicant has any dependents or not.
5)	Education	 - It will tell us whether the applicant is Graduated or not.
6)	Self_Employed	 - This defines that the applicant is self-employed i.e. Yes/ No
7)	ApplicantIncome	 - Applicant income
8)	CoapplicantIncome	 - Co-applicant income
9)	LoanAmount	 - Loan amount (in thousands)
10)	Loan_Amount_Term	 - Terms of loan (in months)
11)	Credit_History	 - Credit history of individual’s repayment of their debts
12) Property_Area 	- Area of property i.e. Rural/Urban/Semi-urban 
13) Loan_Status	 - Status of Loan Approved or not i.e. Y- Yes, N-No 

Libraries & Tools used : Jupyter , NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Since this is a classification problem so we will be using these models : 
1) KNeighborsClassifiers
2) RandomForestClassifiers
3) Support Vector Classifiers (SVC)
4) Logistics Regression

To predict the accuracy we will use the accuracy score function.
