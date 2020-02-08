# Spam-Detection
The simplest way to identify mail as spam or not

Implementation of RNN for email spam-detection using TensorFlow  
The idea is simple - given an email you’ve never seen before, determine whether or not that email is Spam or not.

It is simple ,but very efficient as I reached 98.3% accuracy. I used Tokenizer for giving a specific number to every word and pad_sequences to equalize the length of all sentences.
I used stopwords as well. Stopwords are the word who have no weightage to identify word as spam or not. For ex: "a", "about", "above", "after", etc


*The code is tested on python 3.6 and should work on python 3.x and TensorFlow 2.1.0*

-------------------------------------------------------------------------------------------------------------------------
## Files description:

The data provided is from a csv file spam.csv 

- `spam.csv` FILE contains 5572 mails both in Ham labelled as 1 and Spam labelled as 2


#### NOTE:
*In the notebook U will find how the model works , and how to authenticate a mail*


