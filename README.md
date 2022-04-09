# sarcasm detection
Scikit-learn (machine larning tool for python) for using implementations of classification algorithms. 

2 types of classification
1. binary 
2. Multiclass

For binary class, i need to classify if a tweet is sarcastic or not. For multi class i
have to classify the sarcastic tweet into one of the five categories 
1.irony
2.satire
3.understatement
4.overstatement
5.rhetorical question. 

The given datasets is labelled. For multiclass, only used the tweets that have label of sarcastic as 1.

Split the data into train and test set by using “train_test_split(DataSet)” of scikit. 

Implemention of feature extraction methods. 
1. Bag of words based on raw counts
2. Bag of words based on TfIDF
3. ngrams (bigrams, trigrams)

Classifiers used: 
1. Naïve Bayes
2. Logistic Regression
3. Random Forest
4. SVM
5. Perceptron

Calculated accuracy, Precision, Recall and F-score for all classifiers and reported the results in
tables in file Sarcasm detection report. Made separate tables for binary and multiclass classification. For multiclass 
classification, reported both micro average and macro average of all measures. 
