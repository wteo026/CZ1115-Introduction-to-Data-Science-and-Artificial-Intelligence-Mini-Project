# Loan Status Prediction

### About
This is a Mini-Project for CZ1115 (Introduction to Data Science and Artificial Intelligence) which focuses on Loan Status sourced from Kaggle's [Loan Status Prediction Dataset](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction).

For detailed walkthrough, please view the source code in order from:
1. [Data Extraction](https://github.com/wteo026/CZ1115-Introduction-to-Data-Science-and-Artificial-Intelligence-Mini-Project/blob/main/Data-Extraction.ipynb)
2. [EDA](https://github.com/wteo026/CZ1115-Introduction-to-Data-Science-and-Artificial-Intelligence-Mini-Project/blob/main/EDA.ipynb)
3. [Prediction Model for Loan Status](https://github.com/wteo026/CZ1115-Introduction-to-Data-Science-and-Artificial-Intelligence-Mini-Project/blob/main/Prediction%20Model%20for%20Loan%20Status.ipynb)
4. [Loan Amount Prediction](https://github.com/wteo026/CZ1115-Introduction-to-Data-Science-and-Artificial-Intelligence-Mini-Project/blob/main/Loan%20Amount%20Suggestion.ipynb)

### Problem Definition
1. Identify the most significant variable that affects loan status
2. Create a model that will help to assess whether a loan will be approve
3. Create a model capable of recommending an optimal loan amount to enhance approval prospects

### Contribution
1. @wteo026 - EDA, Decision Tree and RandomForest Classifier for loan status prediction
2. @pigcansiwm - Decision Tree for loan status prediction
3. @C230071 - Random Forest Regression for loan amount prediction

### Model Used
1. Decision Tree & RandomForest Classifier
2. RandomForest Regression
3. Cramers V
4. Point Biserial Correlation Coefficient

### Conclusion
1. The majority of variables within the dataset exhibit minimal influence on Loan Status.
2. Credit History emerges as the most pivotal factor influencing Loan Status.
3. Predominantly, our variables are categorical, represented by values such as Y, N, 0, and 1.
4. Our model demonstrates a 93% accuracy in predicting Loan Status.
5. Our model is able to suggest an optimal loan amount based on applicant's profile

### What did we learnt from this project?
1. Handling imbalanced datasets using resampling methods
2. Utilizing Random Forest Regression & classification techniques.
3. Employing Cramer's V for categorical variable analysis.
4. Implementing Point Biserial correlation for examining associations between continuous and dichotomous variables.
5. The technique of tuning hyperparameters

### References
1. https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction
2. https://www.geeksforgeeks.org/random-forest-regression-in-python/
3. https://scikit-learn.org/stable/modules/tree.html
4. https://machinelearningmastery.com/how-to-connect-model-input-data-with-predictions-for-machine-learning/
5. https://datatab.net/tutorial/point-biserial-correlation
6. https://www.statology.org/interpret-cramers-v/
