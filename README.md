# Sentiment Analysis using Machine and Deep Learning Techniques for Predicting Real Disaster in Tweets


## Brief 
A sentiment analysis project in submission to a Natural Language Processing problem

## Objective 
To classify if a tweet is addressing a real disaster or not.

## Corpus Preprocessing
Regex functions for tweet cleanup
Lemmatisation with Part-of-Speech tagging using treebank tags is used to transform tokenised content into its root form. 

## Feature Exctraction
The following features are extracted: 
1. TF-IDF (word and n-gram levels) 
2. Glove Embedding
3. Keywords

## Classifiers Used:
1. Naive Bayes Classifier
2. Maximum Entropy Classifier (Logistic Regression)
3. Long-Short Term Memory (LSTM) Classifier

## Results
F1-Scores obtained on the validation set which is derived from a randomised subset of the labelled training set

| Model  | Accuracy | F1-Micro | F1-Macro |
| ------------- | ------------- | ------------- | ------------- |
| Naive Bayes	  | 0.797768	| 0.797768 |	0.787868 |
| Maximum Entropy	| 0.793171	| 0.793171 |	0.784938 |
| LSTM	|0.785949 |	0.785949 |	0.768959|

