# Titanic Survival Prediction

## Project Overview

This project predicts passenger survival on the Titanic dataset using machine learning classification models.

The goal of the project was not only to improve prediction accuracy, but also to learn a complete machine learning workflow including preprocessing, pipelines, cross-validation, model evaluation, and Kaggle submission workflow.

---

## Dataset

Kaggle Titanic dataset:

* train.csv
* test.csv

Target variable:

* `Survived`

---

## Main preprocessing steps

* Removed identifier/text-heavy columns:

  * Name
  * Ticket
  * Cabin
  * PassengerId

* Filled missing values:

  * Age → mean
  * Embarked → mode

* Encoded categorical variables:

  * Sex mapping
  * One-hot encoding for Embarked

* Feature engineering:

  * Family_size = SibSp + Parch + 1

---

## Models Used

* Logistic Regression
* Random Forest Classifier

---

## Evaluation Methods

* Train/validation split
* Cross-validation
* Confusion matrix
* Classification report
* Feature importance (Random Forest)

---

## Kaggle Results

| Model               | Public Score |
| ------------------- | ------------ |
| Logistic Regression | 0.77033      |
| Random Forest       | 0.75358      |

Logistic Regression generalized better on the hidden Kaggle test set.

---

## Key Concepts Learned

* Data preprocessing
* Feature engineering
* StandardScaler
* Pipelines
* Cross-validation
* Data leakage prevention
* Confusion matrix interpretation
* Feature importance
* Kaggle submission workflow

---

## Final Observations

Logistic Regression generalized better than Random Forest on the hidden Kaggle test set.

Possible reason:

* Titanic is a relatively small and simple dataset.
* Random Forest may overfit training patterns more easily compared to Logistic Regression.

This project helped me practice and understand several important machine learning concepts:

* data preprocessing
* feature engineering
* scaling with StandardScaler
* pipelines
* cross-validation
* confusion matrix interpretation
* feature importance
* preventing data leakage
* Kaggle submission workflow

---


## Future Improvements

* More advanced feature engineering
* Hyperparameter tuning
* Gradient Boosting / XGBoost
* Better handling of categorical features

<img width="1486" height="894" alt="image" src="https://github.com/user-attachments/assets/8f139590-9aff-4c9c-8f9e-df81c22a96dc" />
