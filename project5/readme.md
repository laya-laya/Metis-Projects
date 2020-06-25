

# Predicting Disease-Gene Associations

### Overview

Finding treatments for diseases often involves targeting the genes that cause the disease. Experimentally validating which genes are associated with a disease can be a costly process, as most genes won't be associated. Computationally predicting which genes are associated with a disease can significantly reduce costs by focusing research on the most probable genes.

I approached this problem as a graph link prediction problem and solved it using a graph neural network.  The general idea is based on [this paper](https://www.biorxiv.org/content/10.1101/532226v1.full.pdf).

### Results

This proof of concept model learned to predict disease-gene links with an F1 score of 0.71, and the only features used were the vectorized clinical descriptions of each disease and gene. Adding more features could improve the model. Disease ontology and gene expression are good candidate features.

### Project Files

The two jupyter notebooks necessary to replicate results are numbered in the order they should be run: `1_data.ipynb` and `2_link_prediction.ipynb`. If you want some pretty visualizations of the data, I included `data_investigation.ipynb` as well.

