# Homophobia-Transphobia-Detection-on-social-media-comments

In this repository we implemented Leveraging Pretrained Language
Models for Detecting Homophobia and Transphobia in Social Media Comments  
https://aclanthology.org/2022.ltedi-1.18.pdf

We took reference from (https://github.com/vitthal-bhandari/Homophobia-Transphobia-Detection)
Homophobia-Transphobia-Detection 

This repository contain the dataset  and a paperReplication.ipynb file 
this file contains all the replicated modes 


To use download all the files into a single folder and run the ipnb file or open the file n colab and upload all the tsv files.

Milestone -2 
Expeiments consits of all the expreimented performend
Data folder consited of datasets used for the experiments
Balanced-Balanaced dataset
translated cotains all the translated versions of the datasets.
To run the expriments:Open the notebook in colab and upload required dataset from the datafolder as per the experiment.



The translation and agumentation is done using the files in Utilities folder.
In Expreiements folder: 
Mbert_Expreiments.ipynb,Indibert_Expreiments.ipynb,XLMroberta_Expreiments.ipynb and XLNet_Expreiments.ipynb : containd zero short expreiemts on each model  along with robustness tests

Multilingual_mbert.ipynb, Multilingual_indibert.ipynb ,Multilingual_xlmroberta.ipynb and Multilingual_XLnet.ipynb    : contins experiment on models where we trained the model with all other languages and evalutated on different language testsets.

 Utilities folder consists of: 
eng_translation.ipynb, tam_translation : translation of the dataset in to other languages.
balance_englih_data.ipynb: consists of augumentation and balancing the dataset for out expreiments
hyperparamerte_tuning.ipynb: consists of expirement on out models for different learning rates.







