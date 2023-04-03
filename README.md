# sms_spam_detection

This is a model that build to classify spam SMS. 
in the model building process there are 4 stages.

* Import Data
* Preprocessing
* Feture extraction
* Training

About the dataset :

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

Link : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download

preprocessing Tasks:

Lower Case
Tokenization
Removing Special Characters
Removing stop words and punctuation
Stemming

Feture Extraction :

TF-IDF vectorizer technique used for the feture extraction process. it used in natural language processing to convert text documents into numerical feature vectors

Model training :

Naive bayes used for the training of the model.
