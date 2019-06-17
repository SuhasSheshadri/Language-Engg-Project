# Topic modelling

Used for finding topic (group of words) from a collection of documents that represents the information in the collection or in other words assigning multiple tags to a text. (Unsupervised Document Classification) Methods Used :

NMF - Non-negative Matrix Factorization
LSA - Latent Semantic Analysis
LDA - Latent Dirichlet Allocation

Steps: 
Create the term-document matrix. 
Perform topic modelling by giving number of topics. 
Get the topics (groups of words). 
Assign labels to each topic. 
To retrieve similar documents: Perform classification to retrieve the top n similar documents using unsupervised nearest neighbours.

Conclusions:
For classification tasks, Topic modelling can be used as features.
LSA is much faster to train than LDA.
But LSA has lower accuracy.
LDA performs better comparatively.