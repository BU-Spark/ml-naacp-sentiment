# NAACP Racial Bias ML Project
## *Li Xi, Jackson Fisk, Jack Li. 2024-02-26

# Research Article Wrap-up
## Jackson:

    https://www.sciencedirect.com/science/article/pii/S0925231223003557 - A systematic review of hate speech automatic detection using natural language processing, 2023

    This paper is analyzing the collective research in this field, giving valuable information about what how other researchers are handling this problem so we can base our implementation on everyone else's

    https://arxiv.org/pdf/2104.02242.pdf - hBert + BiasCorp - Fighting Racism on the Web

    Manually annotated dataset of racist news strings, and hBert implementation of 

    https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9684891 - Racism Detection by Analyzing Differential Opinions Through Sentiment Analysis of Tweets Using Stacked Ensemble GCR-NN Model

    https://www.youtube.com/watch?v=9he4XKqqzvE 

    BERT fine tuning video ^

    https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0237861&type=printable 


## Jack:

    These articles are mainly about the technique we will use in our project to identify the entity referred to by the news article to identify the targeted racial group and the sentiment toward them.

    What is Named Entity Recognition (NER)?
    https://www.turing.com/kb/a-comprehensive-guide-to-named-entity-recognition
    NER essentially extracts and categorizes the detected entity into a predetermined category. The category can be generic like Organization, Person, Location, Time, etc., or a custom category depending on the use case such as Healthcare Terms, Programming Language, etc.

    Detecting Bias in News Articles using NLP Models
    https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1224/reports/custom_116661041.pdf
    The research built a baseline model by implementing a Tensorflow deep-neural-network(DNN) using bag of words to represent the input and TF-IDF as a weighting factor to the DNN data.

    Custom NER using SpaCy
    https://towardsdatascience.com/custom-named-entity-recognition-using-spacy-7140ebbb3718

    LSTM usage on detecting bias in Twitter 
    https://arxiv.org/pdf/2212.00237.pdf

    Kaggle Example for NER dataset
    https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus/data?select=ner_dataset.csv

## Li Xi:
    Papers: 
    Black Americans’ Experiences With News
    https://www.pewresearch.org/journalism/2023/09/26/black-americans-experiences-with-news/
    Pew Research Center conducted a survey and study to understand Black Americans’ experiences, attitudes, and habits around news and information. Black Americans see several problems in news coverage of Black people. Most say that Black people are covered more negatively than people in other racial and ethnic groups. ⅘ black adults believe they see racist or racially insensitive depictions of their race in the news. They believe that educating journalists and hiring black journalists can be helpful in the process for more fair and accurate news coverage. 

    BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
    https://aclanthology.org/N19-1423.pdf
    A new language representation model called BERT, which stands for Bidirectional Encoder Representations from Transformers. Unlike recent language representation models, BERT is designed to pretrain deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers. The pre-trained BERT model can be finetuned with just one additional output layer to create state-of-the-art models for a wide range of tasks. So BERT can be for language inferencing without substantial task-specific architecture modifications. 

    Natural Language Inference
    https://nlpprogress.com/english/natural_language_inference.html
    Natural language inference (NLI) is a task in computational linguistics where the goal is to determine the relationship between a given sentence (the premise) and a hypothesis. The relationship can be categorized as entailment (the hypothesis is true given the premise), contradiction (the hypothesis is false given the premise), or neutral (the hypothesis is neither clearly true nor clearly false given the premise).

    A large annotated corpus for learning natural language inference
    https://aclanthology.org/D15-1075.pdf
    The Stanford Natural Language Inference (SNLI) Corpus contains around 570k hypothesis/premise pairs. Models are evaluated based on accuracy.
    A new, freely available collection of labeled sentence pairs, written by humans doing a novel grounded task based on image captioning. 
    570K -> larger than all other resources of its type. This increase in scale allows lexicalized classifiers to outperform some sophisticated existing entailment models, and it allows a neural network-based model to perform competitively on natural language inference benchmarks for the first time. 

# Open source project - Sentiment Analysis
## XLnet: Generalized Autoregressive Pretraining for Language Understanding    
    Paper: https://dl.acm.org/doi/10.5555/3454287.3454804
    Codebase: https://github.com/zihangdai/xlnet/
    Huggingface Api: https://huggingface.co/xlnet/xlnet-large-cased

