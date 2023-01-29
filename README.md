# A-Comparative-Study-of-Machine-learning-Algorithms-for-Heart-Disease-Prediction

In this project, I applied common Machine-learning algorithms in Python to predict whether a patient have heart disease. I found best parameters by grid search and model with best performance by comparing accuracy scores and test errors. The dataset I used is 2020 annual CDC survey data of 400k adults related to their health status. It has 319,795 entries and 18 variables.

In the data pre-processing part, I first rescaled the numerical variables, did one-hot encoding for the categorical variables and then standardized the data.

Then, for the model application, I applied Logistic Regression, K-NN, SVM, Decision Tree and Neural Network for classification.

Finally, I implemented GridSearchCV to find the best parameter and improve model performance. The results showed that Neural Network has the best performance with test error = 0.06529.
