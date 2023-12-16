# NLP-POS-Tagging-Comparison: HMM vs. RNN

## DESCRIPTION ##
POS-tagging is one of the key steps in Natural Language Processing. We compare the classical approach-Hidden Markov Model (HMM) with some variants of Recurrent Neural Network (RNN). 


## CODE ##
This repository contains two separate files for the implementation of POS-tagging models:
1. File: HMM.ipynb - Implementation of the classical Hidden Markov Model for POS-tagging
2. File: RNN.ipynb - Implementation of various Recurrent Neural Network variants for POS-tagging

## FINDINGS ##

<img width="815" alt="Comparison" src="https://github.com/cccodinglab/NLP-Pos-Tagging-HMM-RNN/assets/112675719/dc9f8493-7d69-44db-9f9a-3651503419dc">

LSTMs’ ability to forget, remember and update the information contained in the entire corpus pushes it one step ahead of HMM. Bidirectional LSTM network outperforms all the other models with the training and testing accuracy reached above 98%. However, the time taken is almost double than of a normal LSTM network as well.
