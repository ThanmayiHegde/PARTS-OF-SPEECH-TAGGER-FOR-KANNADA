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


1)**POS_Tagger_CRF.ipynb**
This contains all the python codes for feature extraction from the corpus that we have considered. Also includes Conditional Random Field Model to predict the appropiate POS Tags for the words considered.

2)**POS_Tagger_BiLSTM.ipynb**
This files contains Bidirectional Long Short Term Memory Model (BiLSTM) fpr predicting and asigning the POS Tags for the given list of kannada words from the corpus.

# Modelling
We have implemented this using one machine learning - "Conditional Random Field" and one deep learning model - "Bidirectional Long Short Term Memory". Accuracy for each of the models and found out.Test set words with their predicted tags are also being display in form of list of tuples.

# 1) Conditional Random Fields :



# 2) Bidirectional Long Short Term Memeory:



# References
1)[1] Shriya Atmakuri, Bhavya Shahi, Ashwath Rao B∗ and Muralikrishna SN, "A comparison of features for POS tagging in Kannada", International Journal of Engineering & Technology.

**Available : [https://www.researchgate.net/publication/328773946_A_comparison_of_features_for_POS_tagging_in_Kannada]**


2)Ketan Kumar Todi, Pruthwik Mishra, and Dipti Misra Sharma, “Building a Kannada POS Tagger Using Machine Learning and Neural Network Models”, CICLING-2018\

**Available:
[https://arxiv.org/abs/1808.03175]**


3)M. Rajani Shree & B. R. Shambhavi (2020) “POS tagger model for Kannada text with CRF++ and deep learning approaches”, Journal of Discrete Mathematical Sciences and Cryptography.

**Available: [https://www.tandfonline.com/doi/abs/10.1080/09720529.2020.1728902]**



4)International Journal of Emerging Trends & Technology in Computer      Science (IJETTCS),POS Tagger for Kannada Sentence TranslationMallamma V Reddy1, Dr. M.   Hanumanthappa2 2012.

**Available at:
[https://www.academia.edu/1770618/POS_Tagger_for_Kannada_Sentence_Translation]**



5)Parts of Speech Tagging for Kannada and Hindi Languages using ML and DL    models.

**Available at:   [https://www.academia.edu/35295207/Parts_Of_Speech_POS_Tagger_for_Kannada_Using_Conditional_Random_Fields_CRFs]**


6)Parts Of Speech (POS) Tagger for Kannada Using Conditional    Random Fields (CRFs),Bangalore, India,08-10 July 2022.

**Available at: https://ieeexplore.ieee.org/document/9865745**

7)Alebachew Chiche,Betselot Yitagesu, "Part of speech tagging: a systematic review of deep learning and machine learning approaches",Chiche and Yitagesu Journal of Big Data,2022.

**Available at: https://doi.org/10.1186/s40537-022-00561-y**

8)C´ıcero Nogueira dos Santos,Bianca Zadrozny , "Learning Character-level Representations for Part-of-Speech Tagging",31st International Conference for Machine Learning,21 June 2014. 

**Available at: 
https://www.researchgate.net/publication/274380525_Learning_Character-level_Representations_for_Part-of-Speech_Tagging**


9)Ketan Kumar Todi, Pruthwik Mishra,Dipti Misra Sharma, "Building a Kannada POS Tagger Using Machine Learning and Neural Network Models",Conference  CICLING At  Vietnam, April 2018.

**Available: https://www.researchgate.net/publication/324546027_Building_a_Kannada_POS_Tagger_Using_Machine_Learning_and_Neural_Network_Models**














