# Classification-Algorithms:
# Problem Statement: 
In this project, we will predict whether an applicant should be approved a Credit Loan or not. To predict this, we will build the following classification algorithms and compare the accuracies with Confusion Metrics for each of the classification algorithms. 
#- Credit loan approval prediction: We have a dataset of credit loan approval. We have 11 dependent features in this dataset, such as:
'Gender' : Male or Female (Categorical data type)
'Married' : Yes or No (Categorical data type)
'Dependents': Number of dependent persons on the applicant (Integer data type)
'Education': Education of the applicant. "Graduate" or "not Graduate"
'Self_Employed': Yes or No(Categorical data type)
'ApplicantIncome': Income of the applicant(Float Type)
'CoapplicantIncome': Income of co-applicant(Float type)
'LoanAmount': Required Loan Amount (Float data type)
'Loan_Amount_Term': Tenure of the loan (Float data type)
'Credit_History': 1 or 0 ( Good or Bad,Categorical data type)
'Property_Area': Urban ir Rural (Categorical data type)
'Loan_Status': Yes or No, loan approved por not (Categorical data type)

#- Technical Features of the project:
From a technical point of view, the main aspects of python covered throughout the notebook are:

Libraries: Pandas, Numpy, Sklearn
data manipulation: pandas, numpy
modeling: Logistic Regression, Decision Tree, Random Forest, Adaptive Boosting, Naive Bayes,
Visualization : matplotlib
Evaluation: Confusion metrics, ROC curve. 

#-Exploratory Data Analysis We have performed EDA by dropping the rows which have missing values. Then we have converted the categorical data into numeric form. The input of Boruta Must be an Array, hence we have converted the data frame into array.
#- Model building:
After EDA, we applied classification algorithms and compared the accuracies of the algorithms. 
The accuracies with respect to all the algorithms we got is as below:
#- Accuracies:
1) Logistic regression: 87.8571%
2) Decision tree: 73.6040%
3) Random Forest: 75.1269%
4) Adaptive Boosting: 74.1116%
5) Naive Bayes: 43.6548%

#- Conclusion:
Hence, we can conclude that, Logistic Regresion has performed well among the other classification algorithms.

