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


#### References
Bowman, S. R., Angeli, G., Potts, C., & Manning, C. D. (2015). A large annotated corpus for learning natural language inference. Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing (EMNLP).

Conneau, A., Kiela, D., Schwenk, H., Barrault, L., & Bordes, A. (2018). Supervised Learning of Universal Sentence Representations from Natural Language Inference Data. ArXiv:1705.02364 [cs.CL]. Retrieved April 10, 2021, from https://arxiv.org/pdf/1705.02364v5.pdf

Merity, S. (2017). Keras SNLI baseline example. Retrieved April 15, 2021, from https://github.com/Smerity/keras_snli/ blob/master/snli_rnn.py

Poliak, A., Naradowsky, J., Aparajita, H., Rudinger, R., & Van Durme, B. (2018). Hypothesis Only Baselines in Natural Language Inference. Proceedings of the 7th Joint Conference on Lexical and Computational Semantics (SEM), 180–191. https://www. aclweb.org/anthology/S18–2023.pdf
