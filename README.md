# Loan Status Prediction

### About
This is a Mini-Project for CZ1115 (Introduction to Data Science and Artificial Intelligence) which focuses on Loan Status prediction. Our dataset is from Kaggle and it contains information of applicants who are applying for housing loan. The information includes:
1. Loan ID
2. Gender
3. Marital Status
4. No. of Dependents
5. Education Level
6. Self Employed
7. Applicant Income
8. CoApplicant Income
9. Loan Amount
10. Loan Amount Term
11. Credit History
12. Property Area
13. Loan Status

For detailed walkthrough, please view the source code in order from:

### Problem Definition
1. Identify the most important variable that determines loan status
2. Create a model that will help to assess whether a loan will be approve
3. Create a model that will suggest a loan amount to maximize the likelihood of getting approval

### Contribution
1. @wteo026 - EDA, Decision Tree and RandomForest Regression for loan status prediction

### Model Used
1. Decision Tree 
2. RandomForest Regression
3. As most of the variables are categorical variables, we also make use of Cramers V Value and Point Biserial Correlation Coefficient to determine the relationship between the predictors and response variable. 

### Conclusion
1. Credit_History is the most significant variable affecting Loan_Status
2. Our model is able to predict Loan_Status with an accuracy of 92%

### What did we learnt from this project?


### References
1. https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction
2. https://www.geeksforgeeks.org/random-forest-regression-in-python/
3. https://scikit-learn.org/stable/modules/tree.html
4. https://machinelearningmastery.com/how-to-connect-model-input-data-with-predictions-for-machine-learning/
5. https://datatab.net/tutorial/point-biserial-correlation
6. https://www.statology.org/interpret-cramers-v/
