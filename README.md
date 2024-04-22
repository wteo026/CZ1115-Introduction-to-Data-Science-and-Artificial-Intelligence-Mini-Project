# Loan Status Prediction

### About
This is a Mini-Project for CZ1115 (Introduction to Data Science and Artificial Intelligence) which focuses on Loan Status prediction from kaggle's [Loan Status Prediction](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction).

For detailed walkthrough, please view the source code in order from:
1. Data Extraction
2. Data Visualization
3. 

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
1. Most variable does not affect Loan Status
2. Credit_History is the most significant variable affecting Loan Status
3. Our model is able to predict Loan Status with an accuracy of 92%

### What did we learnt from this project?
1. Changing data to allow

### References
1. https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction
2. https://www.geeksforgeeks.org/random-forest-regression-in-python/
3. https://scikit-learn.org/stable/modules/tree.html
4. https://machinelearningmastery.com/how-to-connect-model-input-data-with-predictions-for-machine-learning/
5. https://datatab.net/tutorial/point-biserial-correlation
6. https://www.statology.org/interpret-cramers-v/
