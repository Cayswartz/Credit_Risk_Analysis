# Credit_Risk_Analysis

## Overview of the analysis:
In the project we wanted to get a better understanding of the factors that may attribute to if someone if high or low risk for a loan. The hope for this project is that through the models that we used we will be able to help investors avoid risk.

## Results:
* Naive Random Oversampling: The accuracy score for this model was 65%, the precision for the high_risk is at 1% and the recall is 70%. The precision for low_risk is almost 100% and the recall is 61%

![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/main/Images/Naive_Oversampling.png)

* SMOTE Oversampling:The accuracy score for this model is 65%. The high_risk has a precision of 1% and a recall of 63% and the low_risk as a 100% precision and 69% recall.

![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/5fc31a1277830a8c891540591730caa908ca2726/Images/SMOTE.png)

* Undersampling: The accuracy score is 66%. The high_risk has a precision of 1% and recall of 69% and the low_risk has a precision of 100% and recall of 40%

![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/5fc31a1277830a8c891540591730caa908ca2726/Images/Undersampling.png)

* Combination (Over and Under) Sampling: This model has an accuracy score of 54%. The high_risk has a precision of 1% and a recall of 72% and the low_risk has a precision of 100% and a recall of 57%

![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/5fc31a1277830a8c891540591730caa908ca2726/Images/Combination.png)

* Balanced Random Forest Classifier: This model has an accuracy score of 78%. The high_rish has a precision of 3% and a recall of 70% and the low_risk has a precision of 100% and a recall of 87%

![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/5fc31a1277830a8c891540591730caa908ca2726/Images/Balanced%20Random%20Forest.png)

* Easy Ensemble AdaBoost Classifier: This model has a 93% accuracy score. The high risk has a 93% precision and 92% recall rate. The low_risk has 100% precision and 94% recall rate.
![ScreenShot](https://github.com/Cayswartz/Credit_Risk_Analysis/blob/5fc31a1277830a8c891540591730caa908ca2726/Images/ADA.png)


## Summary:
In the first 4 models we used oversampled and undersampled and then used a combination of bother to see which could best help us predict which loans are higher risk. We then used ensemble classifiers to again try to predict which loans are high and low risk. In the first 4 models we saw a lower accuracy score than for the ensemble classifiers. I would move forward with the Easy Ensemble AdaBoost Classifier due to the accuracy rate being the highest of all the models and the recall and precision rate also being very high. 
