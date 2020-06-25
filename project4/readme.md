# Analyzing Presidential Speeches

### Overview

Analyzing the topics of any large set of documents can be a daunting process, and is usually done manually by good old fashion reading. However, natural language processing can aid or even replace this manual process. The varied content of presidential speeches offer an excellent test of automated topic analysis.

The goal of this project is to extract coherent topics from a corpus of presidential speeches found [here](http://www.thegrammarlab.com/?nor-portfolio=corpus-of-presidential-speeches-cops-and-a-clintontrump-corpus). 

### Results

Two topic analysis methods proved effective. The first, latent dirichlet analysis (LDA), is a completely unsupervised method which was good at discovering topics across the documents. The second method, [CorEx](https://github.com/gregversteeg/corex_topic), is a semi-supervised method that was good at analyzing user specified topics.

### Project Files

To replicate the results, run the jupyter notebooks in the order they are numbered.

LDA analysis is done in `3 topic modeling.ipynb`, and CorEx analysis is done in `4 semi-supervised topics and UMAP.ipynb`.

