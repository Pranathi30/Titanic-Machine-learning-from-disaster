# Titanic-Machine-learning-from-disaster
my steps to solve the problem
## Data Preprocessing and Modeling steps for applying Logistic Regression algorithm
1)found out the missing  in both training and test data sets

2)imputation of missing values was done apropriately in both training and test set

3)changed the variables of type object to categorical variables in both training and test

4)one hot encoding is done for categorical variables

5)divided the training data into training and validation  data to check the performance of the model

6)Trained the data using logistic regression algorithm

7)10 fold cross validation is done to check the performace of the model

## Data Preprocessing and Modeling steps for applying Random Forest algorithm
1)found out the missing values

2)Random forest takes care of the missing values and outliers

3)changed the variables of type object to categorical variables

4)one hot encoding is done  fo categorical variables

5)divided the training data into training and validation to check the performance of the model

6)build the model using random forest algorithm

7)10 fold cross validation is done to check the performance of the model

## Steps for applying XGBoost model
1)appropriate data cleaning is done for selected columns in training and test data

2)as xgboost takes care of missing values and outliers, missing values are being filled with -999

3)converted specific variables of type object to categorical variables and one hot encoding is done

4)divided the training data into training and validation to check the performance of the data

5)built the model by tuning the hyperparameters

6)checked the performance of the model using 10 fold cross validation

 Performed weighted ensemble average on XGB model, Random forest model and logistic regression model and scored 0.78947 accuracy.

