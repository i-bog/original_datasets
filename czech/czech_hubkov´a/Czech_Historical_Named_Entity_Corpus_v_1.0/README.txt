==========================================================================================================
       Czech Historical Named Entity Corpus v 1.0
==========================================================================================================

BASIC INFORMATION
--------------------
Czech Historical Named Entity Corpus v 1.0 is a collection of annotated texts for historical Czech named-entity recognition. It is composed of Czech texts from newspaper "Posel od Čerchova" from the second half of 19th century. 

We specified following the basic NE-types: Personal names, Institutions, Geographical names, Time expressions and Artifact names / Objects. More in annotation_manual.pdf.

Every  token  is  placed  in  a  separate  line  which contains four columns, each column separated by a space. The first column is the token, whereas the second one is reserved for lemma (non-specified in our case, represented by an underscore symbol). The third column contains information about the language. Most tokens are Czech ones (”CZ”),  but we can also find some tokens in German (”DE”), French ("FR") or Latin (”LA”). The last column is used to describe the named entity type.

We also used "IOB" notations to indicate the first word in a multiword entity (tag "B" as "beginning"), and inside words for all other NE units (tag "I" as "internal"). All tokens that are not a named entity are tagged as "O" - "outside". 

Each sentence is separated by empty line.


Technical Details
------------------------

This corpus is available only for research purposes for free. Commercial use in any form is strictly excluded. 

AUTHORS
------------------------

- Helena Hubkova hhubkova(at)kiv.zcu.cz
- Pavel Kral pkral(at)kiv.zcu.cz


25th November 2019

