# Credit_Risk_Analysis
Project Overview
•	The purpose of this project is to assist Fastlending, a peer-to-peer lending services company, in their implementation of machine learning to assess credit risk.
•	 Fastlending wants to use machine learning to predict credit risk, as they believe this will provide a quicker and more reliable loan experience for their borrowers.
•	 Fastlending thinks that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. 
•	We will be helping Jill, leading data scientist at Fastlending to implementing the plan by building and evaluating several machine learning models or algorithms to predict credit risk.  We will be using techniques like resampling and boosting as part of the project. 

Deliverable 1 - Use Resampling Models to Predict Credit Risk
•	Deliverable 1.1 - Naive Random Oversampling
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%201.1-%20Naive%20Random%20Oversampling.PNG 
![image](https://user-images.githubusercontent.com/93049541/156892016-36762c9c-69cb-4b9d-af74-90d4abcbedcd.png)
 
•	Deliverable 1.2 - SMOTE Oversampling
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%201.2-%20SMOTE%20Oversampling.PNG
![Deliverable 1 2- SMOTE Oversampling](https://user-images.githubusercontent.com/93049541/156892023-34a3e376-e03b-457f-84e8-c4093dc24ac6.PNG)

 

•	Deliverable 1.3 – Undersampling
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%201.3-%20Undersampling.PNG
 
![Deliverable 1 3- Undersampling](https://user-images.githubusercontent.com/93049541/156892031-9b49e8d9-dac2-4ed7-9e8f-a6483e098d16.PNG)

Deliverable 2 - Use the SMOTEENN algorithm to Predict Credit Risk
•	Deliverable 2 - Combination (Over and Under) Sampling 
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%202%20-%20Combination(Over%20and%20Under)%20Sampling.PNG
 
![Deliverable 2 - Combination(Over and Under) Sampling](https://user-images.githubusercontent.com/93049541/156892037-09ceaa10-82f5-43a9-b207-4e6fc9c5edbe.PNG)


Deliverable 3 - Use Ensemble Classifiers to Predict Credit Risk
•	Deliverable 3.1-Balanced Random Forest Classifier
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%203.1-%20Balanced%20Random%20Forest%20Classifier.PNG
 
 ![Deliverable 3 1- Balanced Random Forest Classifier](https://user-images.githubusercontent.com/93049541/156892041-b44e3e05-5f53-4bda-869a-c5013e4cfa42.PNG)

•	Deliverable 3.2-Balanced Random Forest Classifier
https://github.com/sachinnabar/Credit_Risk_Analysis/blob/main/Deliverable%203.2-%20Easy%20Ensemble%20AdaBoost%20Classifier.PNG
 
![Deliverable 3 2- Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/93049541/156892049-50ca9d9a-3c84-45dd-a492-779707878c32.PNG)



Results
•	Accuracy Score
•	Accuracy: the difference between its predicted values and actual values.
Naïve Random Oversampling Accuracy Score: 0.6405 = 64%
SMOTE Oversampling Accuracy Score: 0.6585 = 66%
Undersampling Accuracy Score: 0.6585 = 66%
Combination (Over and Under) Sampling Accuracy Score: 0.5442 = 54%
Balanced Random Forest Classifier Accuracy Score: 0.7959 = 80%
Easy Ensemble AdaBoost Classifier Accuracy Score: 0.9197 = 91%

•	Precision Score
•	Precision: Precision = TP/(TP + FP) Precision is a measure of how reliable a positive classification is.
Naïve Random Oversampling Precision Score: 99%
SMOTE Oversampling Precision Score: 99%
Undersampling Precision Score: 99%
Combination (Over and Under) Sampling Precision Score: 99%
Balanced Random Forest Classifier Precision Score: 99%
Easy Ensemble AdaBoost Classifier Precision Score: 99%

•	Recall (Sensitivity) Score
•	Sensitivity = TP/(TP + FN) Sensitivity is a measure of the probability of a positive test, conditioned on truly having the condition.
Naïve Random Oversampling Sensitivity Score: 0.56 = 56%
SMOTE Oversampling Sensitivity Score: 0.69 = 69%
Undersampling Sensitivity Score: 0.40 = 40%
Combination (Over and Under) Sampling Sensitivity Score: 0.57 = 57%
Balanced Random Forest Classifier Sensitivity Score: 0.91 = 91%
Easy Ensemble AdaBoost Classifier Sensitivity Score: 0.94 = 94%

•	F1 Score
•	F1 = 2(Precision * Sensitivity)/(Precision + Sensitivity) A pronounced imbalance between sensitivity and precision will yield a low F1 score.
Naïve Random Oversampling F1 Score: 0.71 = 71%
SMOTE Oversampling F1 Score: 0.81 = 81%
Undersampling F1 Score: 0.56 = 56%
Combination (Over and Under) Sampling F1 Score: 0.72= 72%
Balanced Random Forest Classifier F1 Score: 0.95 = 95%
Easy Ensemble AdaBoost Classifier F1 Score: 0.97 = 97%

Summary
•	Based on the above accuracy scores, we can see that AdaBoost Classifier machine learning model had the highest rate of accuracy with the ability to predict the correct values 91% of the time. 
•	Taken individually, the resampling models had similar accuracy scores falling between 64% and 66%, with the Smote oversampling and the undersampling techniques actually receiving the same accuracy score. While this may lead one to think that the combination of the two methods for testing would lead to a similar accuracy, we can see that this is not the case, with the combination machine learning model having the lowest accuracy score of all six learning models with a score of 54%. While there is not enough information to clearly state why the combination model had such a low score compared to the other models, we can speculate that a potential reason was due to the data being manipulated to the point where it was no longer accurate to the actual population. 
•	The precision scores for all six machine learning models yielded the same precision score of 99%. This means that machine learning models can be relied upon to likely predict a positive classification 99% of the time. 
•	The sensitivity scores effectively tell us how reliable in our prediction our tests are. Based on the above scores, it is evident Ensemble Classifiers were better tuned to correctly predict credit risk potential. The Balanced Random Forest Classifier had a recall score of 91%, while the Easy Ensemble AdaBoost Classifier had a recall score of 94%, once again ranking it as the most effective machine learning models for prediction. Compared to the resampling models, which had significantly lower scores, particularly the undersampling method which had the lowest recall score of 40%, it is evident that best machine learning model to be used based on sensitivity is the Easy Ensemble AdaBoost Classifier.
•	The F1 scores of each model effectively tell us is there is a pronounced imbalance between sensitivity and precision; a pronounced imbalanced will yield a low F1 score. Based on this, we can again see that resampling methods fall short compared to the Ensemble Classifier machine learning models, with the undersampling technique having the lowest F1 score of 56% and with the Easy Ensemble AdaBoost Classifier having the largest F1 score of 97%, thereby demonstrating the least disparity between sensitivity and precision.
•	Based on the results and the subsequent analysis of the data, it is recommended that the Easy Ensemble AdaBoost Classifier machine learning model be adopted for use in predicting credit risk. It consistently had the highest scores, particularly in accuracy, precision, and sensitivity, and thus correctly made the correct predictions compared to the other models.
