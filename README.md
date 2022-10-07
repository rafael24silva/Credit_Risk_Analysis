# Credit_Risk_Analysis
## Overview
The purpose of this analysis is to use six different models to predict credit risk. We train and evaluate each model with unbalanced classes. Each model is evaluated and we determine which one is best or if any of them are good. 
## Results
The results of each model are listed as follows:
### Naive Random Oversampling
![Screenshot (84)](https://user-images.githubusercontent.com/106933029/194459915-ec5d1589-bcbc-4951-91e9-1f89558e7ce2.png)

* Balanced accuracy score of 0.684510
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.60/0.68
### SMOTE Oversampling
![Screenshot (86)](https://user-images.githubusercontent.com/106933029/194461344-5a0529e2-a5b2-44d4-8dd2-48ffb8c07b6a.png)

* Balanced accuracy score of 0.676780
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.60/0.68
### Undersampling
![Screenshot (87)](https://user-images.githubusercontent.com/106933029/194461618-c50a8ac5-109f-4dc2-9619-566e721b8d3a.png)

* Balanced accuracy score of 0.449985
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.61/0.45
### Combination Under-Over Sampling
![Screenshot (88)](https://user-images.githubusercontent.com/106933029/194461830-a183a3fc-0ea8-46c2-8d27-851255398b13.png)

* Balanced accuracy score of 0.548503
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.70/0.55
### Balanced Random Forest Classifier
![Screenshot (89)](https://user-images.githubusercontent.com/106933029/194462067-6c47292d-ba80-4a27-9739-3cbbe84b68dd.png)

* Balanced accuracy score of 0.787767
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.67/0.91
### Easy Ensemble AdaBoost Classifier
![Screenshot (90)](https://user-images.githubusercontent.com/106933029/194462318-f65366ea-de17-46b5-8485-dfc8e0b47f9d.png)

* Balanced accuracy score of 0.919797
* Precision is low for high-risk loans and high for low-risk loans
* Recall is at high/low 0.90/0.94
## Summary
After analyzing the results, it is clear that the East Ensemble AdaBoost model is best. It has the highest balanced accuracy at 0.919797. None of the other models were able to get to 0.8 accuracy. When looking at the other results, such as precision and recall, precision is similar among all models while recall is highest in the Easy Ensemble AdaBoost model. There is no doubt this model is best. A model is best when accuracy and recall are closest to 1. This requirement is satisfied by the Easy Ensemble AdaBoost model.
