# classification-challenge

## Description

Classifying SPAM

## Execution

### Dependencies

[Pandas](https://pandas.pydata.org/)

[Scikit-learn](https://scikit-learn.org/stable/)

* [sklearn.preprocessing.StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
* TBC

### Data source(s)

Original Dataset Source: [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase)

This code uses a copy stored at;  [https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

### Command

    Open spam_detector.ipynb in your preferred Jupyter Notebook editor.

## Process

The below process was roughly followed in spam_detector.ipynb

<div style="visibility:hidden">
1. Ingest cryptocurrency pricing data using Pandas
1. Cleansing the raw input data was not needed because all rows contained non-null floats.
1. Normalize the features by adjusting the scale of the numeric features using sklearn.preprocessing.StandardScaler
1. Create clusers using sklearn.cluster.KMeans specifying the ideal k value.
    1. First using the original set of features
    1. Then again using a set of features modified using Princpal Compononent Analysis. In the real world, PCA would likely not be required for this amount of data.
</div>

<details>
    <summary> Associated Lesson</summary>

## Lesson 12 and 13 - Supervised Learning

Concepts covered:

* Using *Standard Scaling* to normalize data.
* Using *Principal Component Analysis (PCA)* to reduce the number of features requiring analysis to cluser the data
</details>