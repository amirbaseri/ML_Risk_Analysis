# ML_Risk_Analysis
Using unsupervised machine learning algorithms to evaluate credit risk.  


## Resampling Quesitons


Question 1: Which model had the best balanced accuracy score?

>Log Regression w/ SMOTE Oversampling: 0.7712812821272772    

Question 2: Which model had the best recall score?


>Log Regression w/ SMOTE Oversampling: 0.80   


Question 3: Which model had the best geometric mean score?
> **The following two models had the same geometric mean score based on our analysis:**
>Log Regression w/ Niave Random Oversampling BAC: 0.77  
>Log Regression w/ SMOTE Oversampling: 0.77    


## Ensemble Learning Questions

Question 1: Which model had the best balanced accuracy score?
>EasyEnsemble had the best BAC value at 0.9243824,

Question 2: Which model had the best recall score?
>Easy Ensemble had the best recall score at 0.94

Quesiton 3: Which model had the best geometric mean score?
>Easy Ensemble had the best Geometric mean score at 0.92

Question 4: What are the top three features?
>**The top three features where:**
> 'last_pymnt_amnt',
> 'total_rec_princp',
> 'total_rec_int'