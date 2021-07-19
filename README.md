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

## BibTeX Citations
We would appreciate using the following citations upon usage of our work in scientific publications. 
```
@inproceedings{chakravarthi-muralidaran-2021-findings,
    title = "Findings of the Shared Task on Hope Speech Detection for Equality, Diversity, and Inclusion",
    author = "Chakravarthi, Bharathi Raja  and
      Muralidaran, Vigneshwaran",
    booktitle = "Proceedings of the First Workshop on Language Technology for Equality, Diversity and Inclusion",
    month = apr,
    year = "2021",
    address = "Kyiv",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.ltedi-1.8",
    pages = "61--72",
    abstract = "Hope is considered significant for the well-being, recuperation and restoration of human life by health professionals. Hope speech reflects the belief that one can discover pathways to their desired objectives and become roused to utilise those pathways. To encourage research in natural language processing towards positive reinforcement approach, we created a hope speech detection dataset. This paper reports on the shared task of hope speech detection for Tamil, English, and Malayalam languages. The shared task was conducted as a part of the EACL 2021 workshop on Language Technology for Equality, Diversity, and Inclusion (LT-EDI-2021). We summarize here the datasets for this challenge which are openly available at https://competitions.codalab.org/competitions/27653, and present an overview of the methods and the results of the competing systems. To the best of our knowledge, this is the first shared task to conduct hope speech detection.",
}

@inproceedings{chakravarthi-2020-hopeedi,
    title = "{H}ope{EDI}: A Multilingual Hope Speech Detection Dataset for Equality, Diversity, and Inclusion",
    author = "Chakravarthi, Bharathi Raja",
    booktitle = "Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.peoples-1.5",
    pages = "41--53",
    abstract = "Over the past few years, systems have been developed to control online content and eliminate abusive, offensive or hate speech content. However, people in power sometimes misuse this form of censorship to obstruct the democratic right of freedom of speech. Therefore, it is imperative that research should take a positive reinforcement approach towards online content that is encouraging, positive and supportive contents. Until now, most studies have focused on solving this problem of negativity in the English language, though the problem is much more than just harmful content. Furthermore, it is multilingual as well. Thus, we have constructed a Hope Speech dataset for Equality, Diversity and Inclusion (HopeEDI) containing user-generated comments from the social media platform YouTube with 28,451, 20,198 and 10,705 comments in English, Tamil and Malayalam, respectively, manually labelled as containing hope speech or not. To our knowledge, this is the first research of its kind to annotate hope speech for equality, diversity and inclusion in a multilingual setting. We determined that the inter-annotator agreement of our dataset using Krippendorff{'}s alpha. Further, we created several baselines to benchmark the resulting dataset and the results have been expressed using precision, recall and F1-score. The dataset is publicly available for the research community. We hope that this resource will spur further research on encouraging inclusive and responsive speech that reinforces positiveness.",
}

@inproceedings{s-etal-2021-ssn,
    title = "ssn{\_}di{BERT}sity@{LT}-{EDI}-{EACL}2021:Hope Speech Detection on multilingual {Y}ou{T}ube comments via transformer based approach",
    author = "S, Arunima  and
      Ramakrishnan, Akshay  and
      Balaji, Avantika  and
      D., Thenmozhi  and
      B, Senthil Kumar",
    booktitle = "Proceedings of the First Workshop on Language Technology for Equality, Diversity and Inclusion",
    month = apr,
    year = "2021",
    address = "Kyiv",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.ltedi-1.12",
    pages = "92--97",
    abstract = "In recent times, there exists an abundance of research to classify abusive and offensive texts focusing on negative comments but only minimal research using the positive reinforcement approach. The task was aimed at classifying texts into {`}Hope{\_}speech{'}, {`}Non{\_}hope{\_}speech{'}, and {`}Not in language{'}. The datasets were provided by the LT-EDI organisers in English, Tamil, and Malayalam language with texts sourced from YouTube comments. We trained our data using transformer models, specifically mBERT for Tamil and Malayalam and BERT for English, and achieved weighted average F1-scores of 0.46, 0.81, 0.92 for Tamil, Malayalam, and English respectively.",
}
```


