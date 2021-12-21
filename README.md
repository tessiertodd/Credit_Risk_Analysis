# Credit_Risk_Analysis

## Overview of Analysis
We are working with Jill from Fast Lending a peer-to-peer lending services company who is looking to use machine learning to predict credit risk. To help Fast Lending to understand how machine learning could be used to evaluated credit risk, we will be using a credit card credit dataset from LendingClub to looking at various algorithms in machine learning to help us predict the credit worthiness of individuals. We will be looking at 6 different models and will make a recommendation on weather they should be used by the bank to more accurtely and quickly predict credit worthiness individuals looking for credit.

We will now review the performance of each of the 6 different machine learning models we worked with.

### Cluster Centroids (undersampling)
![Cluster Centroids](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%201%20-%20Cluster%20Centroids%20(undersampling).png)
This model...

### Naive Random Oversampling
![Naive Random](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%201%20-%20Naive%20Random%20Oversampling.png)
This model...

### SMOTE (oversampling)
![SMOTE](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%201%20-%20SMOTE.png)
This model...

### SMOTEENN (over and under sampling)
![SMOTEENN](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%202%20-%20SMOTEENN.png)
This model...

### Balanced Random Forest Classifier
![Balanced Random Forest](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%203%20-%20Balanced%20Random%20Forest%20Classifier.png)

This model...
![Balanced Random Forest-Rank](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%203%20-%20Balanced%20Random%20Forest%20Classifier%20-%20Ranking.png)

### Easy Ensemble Classifier
![Easy Ensemble](https://github.com/tessiertodd/Credit_Risk_Analysis/blob/main/Images/Deliverable%203%20-%20Easy%20Ensemble%20Classifier.png)
This model has an accuracy of 93.2%, recall of 92% on high-risk and 94% on low-risk and 

## Summary
With so many options of machine learning models and the variability in their predictive ability as we have seen here, its important to explore the best option for each situation given the business you are in as the data you are analysing. In this case the Easy Ensemble Classifier was better than all others in terms of accuracy, precision and sensetivity, but that may not always be the case... there may be trade offs in certain situations if one model does not have a clear advantage in predictive ability.

I would recommend the Easy Ensemble Classifier be used in this case as the metrics are so high with accuracy at 93%, recall of 92% on high-risk and 94% on low-risk and finally has a sensitivity of 9% which is much higher than the other models. .  This model has a good balance between precision and sensitivity, along with being quite accurate.
