# Credit Card Fraud Detection
### Project Overview
This data analysis project aims to build a model that identifies fraudulent transactions using logistic regression. We seek to investigate which quantity has a relationship with out target variable and develop algorithm to detect fraud.
### Tools
- MS Excel -Data Cleaning
- Python Programming Language- EDA and visualization
### Libraries
- Jupyter notebook
- Pandas
- Numpy
- SckitLearn
- Seaborne and Martplotlib
### Data Cleaning and Sorting
It involves cleaning data to remove null/missing values or using an imputer class to compute the mean, median or mode where data are missing/null.
### Data Processing
1. Label Encoding: It involves replacing the target variable with numerical classes e.g Legit=0, Fraudulent=1)
2. Feature Engineering:  It involve separating the input variable from the target variable.
3. Data Visualization: It involve displaying the target class in a scatterplot to determine the best model to use based on the data points distribution.
4. Adjusting imbalanced dataset- This is achieved using undersampling or oversampling method with the smote class
### Data Splitting
If the data set are not splitted originally, a test_train_split class from sklearn is used to achieve this. But if the data is seperated into train and test data on differnt spreadsheet. Then it is necessary you tag them as X_train, X_test, Y_train, Y_test.
### Data Rescaling
The StandardScaler is used to fit and Transform the X_train, then transform the X_test to have mean value of 0 and standard deviation of 1.
### Model Training
Based on the distribution of data points, a logistic regression classifier algorithm was used to train the model.
### Evaluation
The model was fitted and the accuracy, precision, recall and f1 score were determined using the classification_report class.
The accuracy was found to be 95%.
### Recommendation
Hyperparameter tuning can be employed to iterate through all other supervised machine learning algorithm to geth the best performer. This involve using GridSearchCV class.
### Limitation
The dataset target class was imbalanced, so there was a need to use smote class for  undersampling technique.
