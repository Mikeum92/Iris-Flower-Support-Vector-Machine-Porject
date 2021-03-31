# Iris-Flower-Support-Vector-Machine-Project

In This Support Vector Machine Project!  We will be analyzing the famous iris data set!

## The Data
For this series of lectures, we will be using the famous [Iris flower data set](http://en.wikipedia.org/wiki/Iris_flower_data_set). 

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis. 

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.

The rundown of the project:
    * EDA - Identifying the most separable iris species using seaborn parplot visualivation 
    * Model Training with SVC() model from sklearn 
    * Model Evaluation with classification_report
    * Gridsearch with GridSearchCV from sklearn.model_selection (Searching the best hyperparameters) 
    * Model Reevaluation with GridSearch parameters 
 
 Model Performance without GridSearchCV
 
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        16
  versicolor       0.92      0.92      0.92        13
   virginica       0.94      0.94      0.94        16

    accuracy                           0.96        45

 
 Model Performance with GridSearchCV
 
               precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        16
  versicolor       1.00      1.00      1.00        13
   virginica       1.00      1.00      1.00        16

    accuracy                           1.00        45
    
    
    
