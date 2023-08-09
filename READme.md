# Overview
The following repository provides the full code in Python to a mBERT-based reverse dictionary (RD) for German, Italian and Japanese untranslatable words.

Specifically, this project consists of a replication of Yan and colleagues' (2020) experiment on a crosslingual, unaligned RD. 
The paper of reference can be found at the following link https://aclanthology.org/2020.findings-emnlp.388/. 
As for the full original code, this is available on github at https://github.com/yhcc/BertForRD.git 

Besides the full script, two folders containing the datasets used for the implementation are here given: "MyMono" and "MyUWD". For a detailed description, please consult the corresponding READme files within each folder.

#### Python Packages required 

transformers==3.1.0

torch torchvision

fastNLP==0.7.0

fitlog

numpy==1.19.2

huggingface_hub == 0.5.0






