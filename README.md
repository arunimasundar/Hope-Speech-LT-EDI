# Hope-Speech-LT-EDI

This repository contains code pertaining to the the paper titled **"Hope Speech Detection for Dravidian languages using 
Cross-lingual embeddings with Stacked Encoder Architecture"**. 

The work done involves the identification of Hope Speech in YouTube comments. The datasets are provided by the **LT-EDI-EACL** task organizers and is given in the **original datasets** folder.
These comments are of code-mixed nature belonging to the languages mentioned below:
- Tamil-English
- Malayalam-English

We have segregated this repository based on the language of the datasets. 

## Tamil
This folder contains the notebooks used for preprocessing the dataset. Along with this, we have also included [our approach](https://github.com/arunimasundar/Hope-Speech-LT-EDI/blob/main/Tamil/Tamil_training_testing.ipynb) to identify Hope Speech in texts.


We have extracted language agnostic embeddings from texts in the dataset in order to derive more meaning from them. These embeddings are passed on to an encoder framework in order to learn
and classify sentences. 

## Malayalam
This folder contains the notebooks used for preprocessing the dataset. A [similar approach](https://github.com/arunimasundar/Hope-Speech-LT-EDI/blob/main/Malayalam/Malayalam_training_testing.ipynb) to the Tamil language model is adopted. 


