# Toxic_comment_classification_challenge

![kaggle-challenge](https://user-images.githubusercontent.com/68955340/198861528-e2d70abb-9514-4e7d-99fa-bcde92138b23.png)


# Context

During our year of Post Master's Degree in Big Data at Télécom Paris, we carried out a three-month project on the identification and classification of online toxic comments.
More details about Télécom Paris here.

This project stems from the Kaggle challenge of the same name, organized by Jigsaw and Conversation AI.
The objective of this challenge was to build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.
More details about Perspective here.

In our study, several deep learning approaches are used and compared. Logistic regression (LR), Long Short-Term Memory Networks (LSTM), Convolutional Networks (CNN) combined with language processing techniques (NLP) and word representation methods (Word Embedding) are studied. These different approaches are evaluated using training and test sets provided by the actors of the Kaggle competition. These datasets are composed of approx 160k human labelled comments from Wikipedia Talk pages including 6 types of label : toxic, severe toxic, insult, threat, obscene and identity hate. Finally, a web application is developed and deployed to allow anyone to check the toxicity of a comment. 

# Contents
* Imporing data
* Exploring Data
* Text preprocessing
* vectorizing words
* Training and evaluating LSTM model
* Training and evaluating Bidirectional LSTM model
* Training and evaluating GRU model
