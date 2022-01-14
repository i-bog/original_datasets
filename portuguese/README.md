From the paper "Embeddings for Named Entity Recognition in
Geoscience Portuguese Literature"

Citation:
Consoli, B., Santos, J., Gomes, D., Cordeiro, F., Vieira, R., & Moreira, V. (2020, May). Embeddings for named entity recognition in geoscience portuguese literature. In Proceedings of The 12th Language Resources and Evaluation Conference (pp. 4625-4630).

BibTex:
@inproceedings{consoli-etal-2020-embeddings,
    title = "Embeddings for Named Entity Recognition in Geoscience {P}ortuguese Literature",
    author = "Consoli, Bernardo  and
      Santos, Joaquim  and
      Gomes, Diogo  and
      Cordeiro, Fabio  and
      Vieira, Renata  and
      Moreira, Viviane",
    booktitle = "Proceedings of the 12th Language Resources and Evaluation Conference",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2020.lrec-1.568",
    pages = "4625--4630",
    abstract = "This work focuses on Portuguese Named Entity Recognition (NER) in the Geology domain. The only domain-specific dataset in the Portuguese language annotated for NER is the GeoCorpus. Our approach relies on BiLSTM-CRF neural networks (a widely used type of network for this area of research) that use vector and tensor embedding representations. Three types of embedding models were used (Word Embeddings, Flair Embeddings, and Stacked Embeddings) under two versions (domain-specific and generalized). The domain specific Flair Embeddings model was originally trained with a generalized context in mind, but was then fine-tuned with domain-specific Oil and Gas corpora, as there simply was not enough domain corpora to properly train such a model. Each of these embeddings was evaluated separately, as well as stacked with another embedding. Finally, we achieved state-of-the-art results for this domain with one of our embeddings, and we performed an error analysis on the language model that achieved the best results. Furthermore, we investigated the effects of domain-specific versus generalized embeddings.",
    language = "English",
    ISBN = "979-10-95546-34-4",
}

Dataset Link:
https://github.com/jneto04/geocorpus

Notes:
BIO encoding