# Neural Machine Translation
Machine translation is the process of automatically translating a text material from one language to another without human intervention. 
Neural machine translation (NMT) is an enhancement of machine translation that allows building neural models to understand the linguistic patterns 
and predict the correct translated word that will fit the setting (context) of the material.

The below list of paired lang files were picked from [here](https://statmt.org/wmt14/translation-task.html)
1. [Europarl v7](https://statmt.org/wmt13/training-parallel-europarl-v7.tgz)
2. [Commoncrawl Corpus](https://statmt.org/wmt13/training-parallel-commoncrawl.tgz)
3. [News Commentary](https://statmt.org/wmt14/training-parallel-nc-v9.tgz)

to enable **English to German** and **German to English** translation of texts. Pre-processing activities were performed on the full data 
comprising **45 million** pairs of English & German sentences. Base models were built by consuming only **0.05 million** pairs of sentences
and data size increased to **0.1 million** pairs of sentences for neural model building.

Visualization to depict proportion of data-size after merging the three lang files 

![image](https://user-images.githubusercontent.com/68213405/221483712-4163dfea-83e2-4dd9-8321-c2d36bff2c34.png)

### PRE-PROCESSING
The below techniques were applied to clean the source data

• Duplicate text removal

• Text Normalization 

• Expansion of Contractions

• Invalid character removal

• Punctuation removal

• URL and email address removal

• Extra White space removal

![image](https://user-images.githubusercontent.com/68213405/221495876-f7dc106d-4eef-47e8-84fd-f7e6fd3896d0.png)


### MODELS
1. Simple RNN
2. LSTM w/o GloVe
3. Bidirectional LSTM w/o GloVe
4. Encoder-Decoder with GloVe

![image](https://user-images.githubusercontent.com/68213405/221496212-83dfd058-bfa1-4192-ab29-14e899c5afc1.png)
