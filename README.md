## Cluster Analysis of Bio-Contaminating Algae in Port Jackson Bay

### Repository Contents
    ml-clustering-lab
    └───data
        │   harbour_metals.csv
    └───images
        │   Hierarchical Clustering Dendrogram : hierarchical-clustering-dendrogram.png
        │   Scatter Plot of K-Means Clusters with K=3: k-means-clustering.png
        │   Line Plot of TWSS and K (to determine optimal K): optimal-k.png
    │   README.md
    │   .Rmd
    │   .Rproj

### Context

This project was completed for my Machine Learning class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis using appropriate machine learning techniques.

### Question

What are the major clusters of bio-contaminating algae in the Port Jackson Bay, in terms of the expected ranges of metal content across five types of metal (Cd, Cr, Cu, Mn, and Ni)?

### Analysis Summary

Implemented K-means clustering algorithm with data on metal contents (Cd, Cr, Cu, Mn, and Ni) in algae at 10 sample sites around Port Jackson Bay to plot the Total Within Sum of Square (TWSS) for different numbers of clusters and determine the optimal number of clusters that indicate distinct types of bio-contaminating algae. In addition, calculated Euclidean distance matrix to build hierarchical clustering model and inspect the resulting dendrogram for outlier points.

### Datasets
- CSV of Metal Content in Algae at 10 Sample Sites around Port Jackson Bay

### Data References
- David A. Roberts, Emma L. Johnston, Alistair G.B. Poore, Contamination of marine biogenic habitats and effects upon associated epifauna, Marine Pollution Bulletin, Volume 56, Issue 6, 2008, Pages 1057-1065, ISSN 0025-326X, https://doi.org/10.1016/j.marpolbul.2008.03.003.
