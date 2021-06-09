### Natural Language Inference: Sentence Models & Relation Extraction Methods

This project shows implementation of the LSTM model and Sum Embedding models for the NLI task using the SNLI corpus.  
It was inspired by _A large annotated corpus for learning natural language inference_ by Bowman et al. (2015) and _Supervised Learning of Universal Sentence Representations from Natural Language Inference_ by Conneau et al. (2018).

There are three models that the project implements: 
- Sum Embedding Model (Bowman et al., 2015)
- LSTM model + Concatenation (Bowman et al., 2015)
- LSTM model + 3-relation-extraction-method (Bowman et al., 2015; Conneau et al., 2018)

#### Files
- LSTM_only.ipynb file has all the models described above.
- NLI_Exploratory_Data_Analysis.ipynb shows some exploratory data analysis and some baseline models as part of model evaluattion.  

#### Preparation
The code requires tensorflow, sklearn, numpy, and pandas to run. 
The SNLI corpus can be downloaded [here](https://nlp.stanford.edu/projects/snli/snli_1.0.zip/). 

If the link doesn't work, you can go to the [The Stanford Natural Language Processing Group](https://nlp.stanford.edu/projects/snli/) website.

The project makes use of the GloVe to create word embeddings. The glove.840B.300d.txt file can be retrieved [here](https://www.kaggle.com/takuok/glove840b300dtxt). 

More details about the project can be found in this blog post [here](https://jessjkim-1.medium.com/natural-language-inference-exploring-sentence-models-and-relation-extraction-methods-6fe27b3e0d43?source=friends_link&sk=308cf2bcbb984e173183ade0a74af987). 

