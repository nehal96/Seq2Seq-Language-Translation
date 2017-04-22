# Sequence to Sequence Language Translation

Using a sequence to sequence RNN model to translate sentences from English to French. The dataset is text files of ~140,000 fairly simple sentences in English and in French. 

This is Project 4 of Udacity's Deep Learning Nanodegree Foundation. The aim of the project is to go through the process of implementing a sequence to sequence model in TensorFlow by building the encoder and decoder architectures, and finally be able to translate simple English sentences to French.

### Files

[Jupyter Notebook](https://github.com/nehal96/Seq2Seq-Language-Translation/blob/master/dlnd_language_translation.ipynb)

### Hyperparameters

Hyperparameter          | Number |
----------------------- | ------ |
Epochs                  | 30     |
Batch size              | 256    |
RNN size                | 100    |
LSTM layers             | 2      |
Encoding embedding size | 100    |
Decoding embedding size | 100    |
Learning rate           | 0.001  |
Keep probability        | 0.9    |
