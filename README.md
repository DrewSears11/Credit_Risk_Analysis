# Credit_Risk_Analysis
Module 17

## Overview of Analysis

The purpose of this analysis is to help our friend Jill use statistcal reasoning and machine learning to determine the factors that lead to credit risk and help us determine what should be used to predict credit risk.

## Results
  ### Random OverSampling
  * As you can see below, the balanced accuracy score for Random Oversampling is 0.64.  
  ![image](https://user-images.githubusercontent.com/108240844/198165321-194358a9-828a-4ba2-a6f6-6320e30eaaf3.png)
  
  * The precision rating of 0.01 for high risk as seen below doesn't really tell us much because there were so few high risk ratings for the data.  It is the same for     all   4 Samplings done with Over and Under.  The precision rating being the total number of true high risk against the all loan amounts.  The recall (or     sensitivity)   number    of 0.62 for high and 0.65 for low means the data is close together
  ![image](https://user-images.githubusercontent.com/108240844/198158496-e09e70aa-82c0-498b-b664-17742b4b271c.png)
  ### Smote OverSampling
  * The balanced accuracy score for Smote OverSampling is 0.63.  This accuracy is lower than we would like to see.
  ![image](https://user-images.githubusercontent.com/108240844/198165377-114f2d7d-fc3b-4c72-8e6a-fde5201e258e.png)
  * The precision rating is that same as the Random OverSampling model with the recall number very similar as well.
  ![image](https://user-images.githubusercontent.com/108240844/198164996-9aa6bcf1-1f29-4eb4-8a47-53f3ff06552d.png)
  ### UnderSampling
  * The balanced accuracy score for UnderSampling is 0.63
  ![image](https://user-images.githubusercontent.com/108240844/198165550-3bca93ab-0484-4730-85ac-3ae3864074d4.png)
  * The precision is the same as the three above.  There is a substansial difference in the low risk recall accuracy with is 0.45, the lowest we've seen so far.
  
  ![image](https://user-images.githubusercontent.com/108240844/198166160-9c59a07e-d6ea-471e-ae07-7f5278bcabb7.png)
  ### Combination Sampling
  * The balanced accuracy score for Combination Sampling is 0.64.  All 4 of our Over / Under Samplings have been near the same accuracy.
  ![image](https://user-images.githubusercontent.com/108240844/198166294-682af6b9-9dfb-44f3-bb91-0713eb63630e.png)
  *  The precision is the same as the three above.  This has the highest recall number 0.70 than the four have had so far.
  ![image](https://user-images.githubusercontent.com/108240844/198166420-f5b59d5a-613a-4ed0-aca2-9ae6c8103a10.png)
  ### Balanced Random Forest Classifier
  * The balanced accuracy score was the highest so far at 0.66
  ![image](https://user-images.githubusercontent.com/108240844/198167024-29cf1861-0a32-436b-8b85-13a172470251.png)
  * We finally have a good precision we can use for high risk with this model at 0.72
  ![image](https://user-images.githubusercontent.com/108240844/198167187-637ea769-ee7b-4b0e-8f25-0b9f3f1334cf.png)
  ### Easy Ensemble Adaboost Classifer
  * The balanced accuracy score was also 0.66 for the Adaboost Classifier.
  ![image](https://user-images.githubusercontent.com/108240844/198167267-52857277-4973-4c82-8802-3366b7ba8caa.png)
  * We see see the classification report below with the same precision and recall ratings as the other Classifier model.


## Summary


