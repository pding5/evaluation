Machine Translation
====
Introduction
-----
This program is a translation machine that can translate English sentences into French sentences. Used Gated Recurrent Unit (GRU) model to train and test data, and finally compute the BLEU score for the testing data set. The dataset is stored in fra.txt, which contains both English sentences and French sentences. It is used to train a Gated Recurrent Unit (GRU) model using Keras with a Tensorflow back end to create a 64-batch model. Moreover, it used the GRU-Attention mechanism which can improve the performance of the model. Finally, this model can translate English sentences into French sentences and the BLEU score for the testing dataset is 0.76.

Motivation
-----
Although both English and French belong to Indo-European language and 1/3 English vocabulary is from French, there still many differences in English and French. In addition, English belongs to Germanic stock and French belongs to languages Romanies. Since I am interested in both languages, I want to develop a translating machine to implement the translation from English to French. 

Required Python Packages
-----
Numpy
Unicodedata
Tensorflow
Sklearn
Time
io
re
Matplotlib
NTLK

Repository structure
-----
The model is stored in Machine_translation.ipynb. The structure of the code file is as follows.
Load data
Divide data into training and testing using cross-validation
Encode Model
Construct attention layer
Decode Model
Optimizer and Loss Function
Training steps
Testing results
Compute the BLEU score for the testing dataset

The dataset used in this model is stored in fra.txt. 

Example running result
-----

The input English sentence can be translated into a French sentence properly.


The BLEU score of this model for the testing dataset is 0.76.

How to use
-----
Download Machine_translation.ipynb and fra.txt.
Install all the packages listed above
Test the functionality you want to by running the corresponding cell in Machine_translation.ipynb file directly

How to test functionality
-----
Open Machine_translation.ipynb file in Jupyter notebook.
Running testing cell from cell 50 to 55.
Ensure the functionality is working intended. The result should show both the input sentence and the output sentence.
If the translation functionality is working properly, then you can use the translation model.

Acknowledgments
-----
I read a large number of online tutorials for specific parts of the code. Primarily the code that dealt with making a good Gated Recurrent Unit (GRU) and the image processing techniques.

Tensorflow - https://www.tensorflow.org/

Keras - https://keras.io/

