# German-Credit-Card-
In depth Analysis of German Credit Card.
Following Data contains columns such as:
checking_balance        
months_loan_duration    
credit_history          
purpose                 
amount                  
savings_balance         
employment_duration     
percent_of_income       
years_at_residence      
age                    
other_credit            
housing                 
existing_loans_count    
job                     
dependents              
phone                   
default                 


The Machine learning algorithms that were used to build the models were:

1) Logistic Regression

2) Random Forest Classifier

3) Gradient Boosting

4) K-Nearest Neighbors (KNN)

The best-fit model among the ones created based on performance metrics was “Gradient Boosting”

Data-Set Accuracy Precision f1-Score Recall

0         82       83          83      83
1                  80          81      81
The top 5 features for Random Forest and Gradient Boosting are

Checking_Balance, Amount, Age, Months_loan_duration, and Saving_balance.

he importance score is normalized and shows the relative importance of features.


#Conclusion

According to me the best algorithm for this dataset is the Gradient Boosting machine learning algorithm.

Gradient Boosting has consistently demonstrated to be one of the most impressive algorithms to developed the predictive model.

The one main reason the Gradient boosting algorithm is very good because it can easily overfit on a training data set.

Different hyperparameters can be used to counter the overfitting. The Calculated Accuracy for this data set is 82% which

is better than Random Forest with 80%, KNN with 74%, and Logistic Regression with 74%.
