
# Naive Bayes algorithm - spam detection
## Introduction
In this project I will be using the Naive Bayes algorithm to create a model that can classify SMS messages as spam or not spam, based on the training I give to the model.

It is important to have some level of intuition as to what a spammy text message might look like. Usually they have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and my objective here is to train a model to do that for me!

Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as I will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

## About the data set
#### SMS Spam Collection v.1

Available to download here https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection.
