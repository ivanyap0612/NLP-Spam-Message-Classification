# NLP-Spam-Message-Classification

## Introduction
In this project, the aim is to use the SMS Spam Collection dataset to perform text classification and build a prediction model that will accurately classify which texts are spam. Natural Language Processing(NLP) technique has been applied to classify the message as "spam" or "ham" correctly.

## Dataset
- [spam.csv](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

## Details
Some common techniques of Natural Language Processing(NLP) has been applied:

- Punctuation and Stopwords Removal
- Stemming
- Tokenizer
- Bag of words
- Term frequency inverse document frequency (TF-IDF)

6 different models have been trained to classify unknown messages as spam or ham:

- AdaBoost Classifier
- Multinomial Naive Bayes Classifier
- Logistic Regression
- K-Nearest Neighbors Classifier
- Bagging Classifier
- Gradient Boosting

## Conclusion
Logistic Regression has the highest accuracy score and AUC-ROC among all the 6 models. It obtained an accuracy score of 0.9874 and AUC-ROC of 0.98, with 1 being the perfect score. It is proved that Logistic Regression can be used to accurately classify which texts are spam.

In the future, fine-tuning of Logistic Regression will be carried out in order to improve the accuracy score and AUC-ROC of the model. Since Logistic Regression is able to detect spam messages accurately in this dataset, this model may be used for text classification for other aspects.
