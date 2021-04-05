# Employee-Attrition-in-Organisation
---

## Project Overview

- Objective : To predict Employee Attrition in an organisation 
- Classification Model
- Data cleaning and Data preprocessing has been done
- Exploratory Data Analysis
- Various classification models like Logistic Regression, KNN, SVM, Kernel SVM, Naive Bayes, Decision Tree, Random Forest, ANN, XGBosst and CatBoost  are used.
- Model Performance Comparison
- Conclusion: Top Reasons why employees are leaving an organisation.

<img src="https://github.com/SidSolanki28/Sid_Portfolio/raw/master/images/employee-attrition.jpg" width="400" height="250">

---

## About Project

We are developing classification models for companies to determine whether an employee is going to quit or not. 
These models are based on an extensive dataset which is easily available by HR.
This project helps to avoid attrition of working employees and hiring of new employees which need time, capital and skills.

---

## Code and Resources used

- Python version: 3.7.6
- Packages: Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Tensorflow and Catboost
- Resources used:

  * Analytics Vidya
  * towards data science
  * Kaggle

---

## Web Scraping

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists.

Dataset URL: https://www.kaggle.com/c/rossmann-store-sales/data

### Data fields

Features:

* TV: advertising dollars spent on TV for a single product in a given market (in thousands of dollars)
* Radio: advertising dollars spent on Radio
* Newspaper: advertising dollars spent on Newspaper

Target:

* Sales budg

---

## Model Performance

Model
Classification Matrix
Logistic Regression
             precision    recall  f1-score   support

           0       0.91      0.97      0.94       255
           1       0.67      0.36      0.47        39

    accuracy                           0.89       294
   macro avg       0.79      0.67      0.70       294
weighted avg       0.88      0.89      0.88       294
KNN
             precision    recall  f1-score   support

           0       0.88      1.00      0.93       255
           1       0.80      0.10      0.18        39

    accuracy                           0.88       294
   macro avg       0.84      0.55      0.56       294
weighted avg       0.87      0.88      0.83       294
SVM
             precision    recall  f1-score   support

           0       0.92      0.97      0.94       255
           1       0.68      0.44      0.53        39

    accuracy                           0.90       294
   macro avg       0.80      0.70      0.74       294
weighted avg       0.89      0.90      0.89       294
Kernel SVM
             precision    recall  f1-score   support

           0       0.90      1.00      0.94       255
           1       0.91      0.26      0.40        39

    accuracy                           0.90       294
   macro avg       0.90      0.63      0.67       294
weighted avg       0.90      0.90      0.87       294
Naive Bayes
             precision    recall  f1-score   support

           0       0.92      0.68      0.78       255
           1       0.23      0.62      0.33        39

    accuracy                           0.67       294
   macro avg       0.57      0.65      0.56       294
weighted avg       0.83      0.67      0.72       294
Decision Tree
             precision    recall  f1-score   support

           0       0.87      0.86      0.87       255
           1       0.16      0.18      0.17        39

    accuracy                           0.77       294
   macro avg       0.52      0.52      0.52       294
weighted avg       0.78      0.77      0.77       294


Random Forest
             precision    recall  f1-score   support

           0       0.87      0.98      0.93       255
           1       0.43      0.08      0.13        39

    accuracy                           0.86       294
   macro avg       0.65      0.53      0.53       294
weighted avg       0.82      0.86      0.82       294
ANN
             precision    recall  f1-score   support

           0       0.91      0.95      0.93       255
           1       0.50      0.36      0.42        39

    accuracy                           0.87       294
   macro avg       0.70      0.65      0.67       294
weighted avg       0.85      0.87      0.86       294
XGBoost
             precision    recall  f1-score   support

           0       0.90      0.96      0.93       255
           1       0.55      0.28      0.37        39

    accuracy                           0.87       294
   macro avg       0.72      0.62      0.65       294
weighted avg       0.85      0.87      0.86       294
CatBoost
             precision    recall  f1-score   support

           0       0.88      0.99      0.93       255
           1       0.67      0.15      0.25        39

    accuracy                           0.88       294
   macro avg       0.78      0.57      0.59       294
weighted avg       0.86      0.88      0.84       294


---

## Conclusion

Top Reasons why Employees leave the Organization:

- **No Overtime** This was a surprise, employees who don't have overtime are most likely to leave the organization. This could be that employees would like to have a higher amount of income or employees could feel that they are underused.
- **Monthly Income** As expected, Income is a huge factor as why employees leave the organization in search for a better salary.
- **Age** This could also be expected, since people who are aiming to retire will leave the organization.
Knowing the most likely reasons why employees leave the organization, can help the organization take action and reduce the level of Attrition inside the organization.

---

## Further Improvements

To further improve the model, below options can be considered:

- Try to make this balanced dataset
- Tune all classification models
- Use cross-validation and grid-search
- Compare models with Accuracy, Recall, Precision, F1 score and AUC/ROC Curve
-
---
