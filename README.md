# classification-challenge

## Description

Classifying SPAM

## Execution

### Dependencies

[Pandas](https://pandas.pydata.org/)

[Scikit-learn](https://scikit-learn.org/)

* sklearn.preprocessing.StandardScaler
* sklearn.model_selection.train_test_split
* sklearn.metrics.accuracy_score
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier

### Data source(s)

Original Dataset Source: [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase)

This code uses a copy stored at;  [https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

### Command

    Open spam_detector.ipynb in your preferred Jupyter Notebook editor.

## Process

The below process was roughly followed in spam_detector.ipynb

1. Ingest spam data using Pandas
1. Review data.
1. Split data into training and test datasets 
1. Normalize the features by adjusting the scale of the numeric features using sklearn.preprocessing.StandardScaler
1. Instantiate and train models
1. Create test predicitions
1. Calculate accuracy scores
1. Determine which model is a better fit for the problem

Predictions were limited to test data for this exercise.

<details>
    <summary> Associated Lesson</summary>

## Lesson 12 and 13 - Supervised Learning

Concepts covered:

* Splitting data set into training and test data sets using sklearn.model_selection.train_test_split
* Using *Standard Scaling* to normalize data.
* Using *Accuracy Scores* to determing if a model is likely to yield an accurate prediction for the specified dataset
* Using the *Random Forests Classifier* and  *LogisticRegression* models