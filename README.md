# Neural Machine Translation
Machine translation is the process of automatically translating a text material from one language to another without human intervention. 
Neural machine translation (NMT) is an enhancement of machine translation that allows building neural models to understand the linguistic patterns 
and predict the correct translated word to will fit the setting (context) of the material.

The below list of paired lang files were picked from [here](https://statmt.org/wmt14/translation-task.html)
1. [Europarl v7](https://statmt.org/wmt13/training-parallel-europarl-v7.tgz)
2. [Commoncrawl Corpus](https://statmt.org/wmt13/training-parallel-commoncrawl.tgz)
3. [News Commentary](https://statmt.org/wmt14/training-parallel-nc-v9.tgz)

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


### MODELS
1. LSTM w/o GloVe
2. Bidirectional LSTM w/o GloVe
3. Encoder-Decoder with GloVe

![image](https://user-images.githubusercontent.com/68213405/221484747-79f42ca6-feb2-4c5c-9e75-c75205d8de83.png)


### SUMMARY

![image](https://user-images.githubusercontent.com/68213405/221484601-76aea1a4-40e7-4c2e-8696-be4eb6c8a32b.png)

