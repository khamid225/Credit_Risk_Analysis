# Credit Risk Analysis

## Overview

 This challenge uses machine learning to predict credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 
 Will use different machine learning techniques such as oversampling, undersampling and boosting to build and evaluate machine learning algorithms to predict credit risk. 
 These algorithms will be evaluated to see how well they predict a credit problem. 

This techniques include:

1. Resampling Models
2. SMOTEENN Algorithm
3. Ensemble Classifiers

## Resources
- Data Source: This analysis was performed using the ***LoanStats_2019Q1.csv*** dataset.  
- Software: Python 3.9, scikit-learn, Jupyter Notebook and Pandas. **NOTE**: Started doing it Google Colab but it uses Python 3.7 and fitting a BalancedRandomForestClassifier fails so I did it locally on Python 3.9

## Results: 
- The balanced accuracy score and the precision and recall scores of all six machine learning models are shown: 

#### Random Oversampler:

![Screenshot](Screenshot%20from%202021-09-18%2021-54-35.png)

#### SMOTE Oversampler:

![Screenshot](Screenshot%20from%202021-09-18%2021-57-18.png)

#### ClusterCentroids Undersampler:

![Screenshot](Screenshot%20from%202021-09-18%2022-01-01.png)

#### SMOTEENN combinationsampler:

![Screenshot](Screenshot%20from%202021-09-18%2022-02-05.png)

#### Balanced Random Forest Classifier:

![Image](Screenshot%20from%202021-09-18%2022-08-14.png)

#### Easy Ensemble AdaBoost Classifier:

![Image](Screenshot%20from%202021-09-18%2022-09-53.png)


## Summary:

- The Easy Ensemble AdaBoost Classifier had the highest accuracy (**94%**) and provided the highest sensitivity of all models. 
- The precision and the F1 scores were low for all models. 
