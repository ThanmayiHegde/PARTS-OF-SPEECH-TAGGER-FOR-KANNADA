# PARTS OF SPEECH TAGGER FOR KANNADA
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


1)**POS_Tagger_CRF.ipynb**:
This contains all the python codes for feature extraction from the corpus that we have considered. Also includes Conditional Random Field Model to predict the appropiate POS Tags for the words considered.

2)**POS_Tagger_BiLSTM.ipynb**:
This files contains Bidirectional Long Short Term Memory Model (BiLSTM) fpr predicting and asigning the POS Tags for the given list of kannada words from the corpus.

# Modelling
We have implemented this using one machine learning - "Conditional Random Field" and one deep learning model - "Bidirectional Long Short Term Memory". Accuracy for each of the models and found out.Test set words with their predicted tags are also being display in form of list of tuples.

# 1) Conditional Random Fields :

We use Linear Chain Conditional Random Fields model (log-linear) to train and predict the part-of-speech tags of the words in the corpus.

The accuracy obtained when we use this model is **66.85714**.


# 2) Bidirectional Long Short Term Memeory:

The character embeddings were learned with the help of a biLSTM network. The output of the biLSTM was the representation of the word by using the character embeddings of individual letters present inside the word which helps in improving the accuracy.
It combines the word embedding with the character embedding where a better syntactic representation is learned to gain character level information.

The accuracy obtained when we use this model is **74.00615**




# Conclusion
Based on the accuracy values we can conclude that BiLSTM model outperforms CRF model for tagging POS for kannada.




# How to run?
- Keep the corpus in the same directory as the two .ipynb files.
- Install required package in order to run codes.
- Load corpus to run the codes.
- Run all the cells in sequential manner.
- Interpret the results obtained from models.
