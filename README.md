# Springboard_RelaxInc
## EDA
* Total number of users: 12,000
* Total number of adopted users: 2,440 (20.4%)
* Creation source that has the highest percentage of adopted users: 'PERSONAL_PROJECT'
* Top 10 organizations by number of adopted users: 
    ** Organization Id: 0, Number of adopted users: 27
    ** Organization Id: 4, Number of adopted users: 24
    ** Organization Id: 7, Number of adopted users: 23
    ** Organization Id: 9, Number of adopted users: 23
    ** Organization Id: 1, Number of adopted users: 22
    ** Organization Id: 2, Number of adopted users: 21
    ** Organization Id: 6, Number of adopted users: 20
    ** Organization Id: 3, Number of adopted users: 19
    ** Organization Id: 5, Number of adopted users: 17
    ** Organization Id: 8, Number of adopted users: 16
* Organizations that do not have adopted users: 
  ** Organization Id: 183
  ** Organization Id: 355
  ** Organization Id: 412
  ** Organization Id: 416
* 5 users with the most invitation:
  ** 10741.0    13
  ** 2527.0     12
  ** 1525.0     11
  ** 11770.0    11
  ** 2308.0     11
## Model Selections
List of classifiers:
  * MultinomialNB
  * SVM
  * Logistic Regression
  * KNeighbors
  * Decision Tree
  * Bagging
  * AdaBoost
  * Random Forest
  * Voting
Best classifier:
* KNeighbors
  ** Cross-validation scores: [0.76480209 0.79326137 0.80536474 0.8083088  0.81151832]
  ** Mean accuracy: 0.7966510643326534
  ** Model performance:
     ** Accuracy: 0.9141666666666667
     ** Confusion Matrix:
      [1911, 0]
     [206, 283]
  ** Classification Report
![image](https://github.com/dqminhv/Springboard_RelaxInc/assets/73676962/1dc2e515-d7e9-437a-99b7-f5157763cb62)


## Features Importance
* With Random Forest Classifier
* ![image](https://github.com/dqminhv/Springboard_RelaxInc/assets/73676962/4c49dc69-0878-46ff-9e17-c1649d177a05)


**From the features importance plot, we see that three most importance features are:**
  * **Last login time**
  * **If the account is for a personal project.**
  * **If a user is invited by another user.**

