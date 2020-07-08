# Latent Dirichlet Allocation

## Introduction

> The aim of this repository was to implement and train LDA generative model based on publication: 

    Blei, David M., Andrew Y. Ng, and Michael I. Jordan. "Latent dirichlet allocation." Journal of machine Learning     research 3.Jan (2003): 993-1022.



## LDA

> LDA is ".... a generative probabilistic model for collections of discrete data such as text corpora. LDA is a three-level hierarchical Bayesian model, in which each item of a collection is modeled as a finite mixture over an underlying set of topics. Each topic is, in turn, modeled as an infinite mixture over an underlying set of topic probabilities. In the context of text modeling, the topic probabilities provide an explicit representation of a document. We present efficient approximate inference techniques based on variational methods and an EM algorithm for empirical Bayes parameter estimation. We report results in document modeling, text classification, and collaborative filtering, comparing to a mixture of unigrams model and the probabilistic LSI model" 
Source: http://www.jmlr.org/papers/v3/blei03a



## Implementation details

> Model was implemented using Pytorch and Pyro and Jupyter notebook. Sample training documents come form resources of CLARIN-PL (a research consortium): http://clarin-pl.eu/en/uslugi/