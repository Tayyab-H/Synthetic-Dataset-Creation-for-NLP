# Synthetic-Dataset-Creation-for-NLP

Using the power of word2vec, the notebooks showcase how to create synthetic NLP data for classification from a very small basic balanced manually inputted dataset. It is capable of expanding an NLP dataset of only 30 samples to one of over 1000 samples. This is incredibly powerful for specific NLP tasks.

The pretrained google word2vec is not included in the git repository due to size. You will have to download it seperately and extract it into your working directory from the following link:
https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz

First run the dataset expansion notebook. Then go through the training notebook.


Dependancies: 

Numpy

Keras, tensorflow

Gensim

win32com (Only for email access)

Pandas

pyttsx3

sklearn
