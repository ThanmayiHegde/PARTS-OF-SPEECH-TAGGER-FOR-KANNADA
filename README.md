# MI-PROJECT
Part-of-Speech tagging is one of the most basic natural language processing tasks where each word of a sentence is tagged with appropriate syntactic labels such as noun, pronoun, verb, adjective and so on. 

**A tag set of 14 tags has been used to perform the part-of-speech tagging :**

-CC coordinating conjunction

-CD cardinal digit

-DT determiner

-EX existential there

-FW foreign word

-IN preposition/subordinating conjunction

-JJ adjective

-NN noun.

# SCOPE. 
1. POS tagging finds applications in Named Entity Recognition (NER), sentiment analysis, question answering, and word sense disambiguation.

2. Tags help social marketers group and categorize posts for flexible reporting on content, creative and campaigns. Customers across industries use them to unlock key performance insights and move their strategies forward.


# Dataset
The dataset includes the corpus.txt file which has different KANNADA words and their corresponding POS tags.There are 6799 words in the corpus.


# Files
Its consists of two .ipynb files namely,


1)------------.ipynb 
This contains all the python codes for feature extraction from the corpus that we have considered. Also includes Conditional Random Field Model to predict the appropiate POS Tags for the words considered.

2)------------.ipynb
This files contains Bidirectional Long Short Term Memory Model (BiLSTM) fpr predicting and asigning the POS Tags for the given list of kannada words from the corpus.

# Modelling
We have implemented this using one machine learning - "Conditional Random Field" and one deep learning model - "Bidirectional Long Short Term Memory". Accuracy for each of the models and found out.Test set words with their predicted tags are also being display in form of list of tuples.

# 1) Conditional Random Fields :








