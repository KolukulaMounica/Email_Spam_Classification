# Email_Spam_Classification
This project is about classifying emails as spam and not spam in an imbalanced data set using different text classification methods. 


Spam via email is when a recipient list is contacted with unwanted or commercial communications
In 2021, it was estimated that 319.6 billion emails were sent and received daily
In Dec 2021, 45.37% of the total emails were considered spam emails
Nearly 96% of phishing attacks are conducted using email. Hence, identifying and detecting spam emails is important. 

Only plain text emails are considered (emails containing image or multimedia content ignored for now)

## Steps in Preprocessing


Understanding fields of an email file

Filtering only the relevant fields required for text mining (To, From, Subject, Content-Type and Body)

Removing stop words, punctuation marks and converting all letters to lowercase

Stemming (reducing a word to its root word)

Count of each words using CountVectorizer

## Transformation of Data
Transforming the data using diverse methods before making prediction.

fit() - Every estimator implements fit(), which takes a sample input data.

fit_transform() -  It is applied to the training data so that we can learn the scaling parameters and scale the training data.

predict() - Predictions on fresh, unseen test data points can be made using the predict() function, which effectively uses the learnt parameters from fit().

Using cross_val_score() for cross-validation. The evaluation will be carried out using the cross_val_score() function, which accepts the dataset and cross-validation setup and returns a list of scores computed for each fold.



