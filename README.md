# Loan-Prediction-using-Logistic-Regression

The main aim of the algorithm was to identify whether or not an individual's loan will get approved based on a given dataset.
For the algorithm, the python libraries used were :
  Pandas
  Numpy
  Seaborn
  Matplotlib
  Scikit-Learn
  
The dataset had following columns : 
Loan_ID', 'Gender', 'Married', 'Dependents', 'Education','Self_Employed', 'ApplicantIncome', 'CoapplicantIncome', 'LoanAmount', 'Loan_Amount_Term', 'Credit_History', 'Property_Area', 'Loan_Status'.

The dataset had categorical data, ordinal data and numerical data. Exploratory data analysis and feature engineering was done on the dataset. The NaN walues were filled and then logistic regression was used on it.

The parameters for logistic regression were :

LogisticRegression(C=1.0, class_weight=None, dual=False, fit_intercept=True, 
                   intercept_scaling=1, max_iter=100, multi_class='ovr', n_jobs=1,
                   penalty='l2', random_state=1, solver='liblinear', tol=0.0001, verbose=0, warm_start=False)
                   
The algorithm gave an accuracy of 0.8324324324324325.


For a much larger dataset, we can use Stratified K-fold with logistic regression to obtain better results. 
