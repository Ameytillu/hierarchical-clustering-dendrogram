## Hierarchical Clustering & Dendrogram Visualization

This project demonstrates the use of **hierarchical clustering** to uncover hidden patterns and relationships within a dataset. A dendrogram is used to visually represent the merging process of clusters based on feature similarity.

## Objective

To explore the internal structure of a dataset using **unsupervised machine learning**, specifically through:
- Hierarchical clustering using various linkage methods
- Visual interpretation via dendrograms
- Identification of natural cluster groupings

## Dataset Overview

The dataset consists of numerical features representing individual data points. These points are grouped into clusters based on their feature similarity using a distance-based approach.

## Methodology

### Preprocessing
- Data loading and inspection using pandas
- Optional scaling or normalization of features (depending on dataset)

### Clustering
- **Linkage computation** using `scipy.cluster.hierarchy.linkage()`
  - Common methods used: `'ward'`, `'average'`, `'complete'`
- **Dendrogram plotting** using `scipy.cluster.hierarchy.dendrogram()`

### Interpretation
- The dendrogram visually shows the step-by-step merging of clusters
- Large vertical distances between merges suggest strong cluster boundaries
- Users can choose a cut-off point to define the number of clusters

## Visualization

A dendrogram provides a tree-like structure showing how clusters are formed. It helps to:
- Determine the optimal number of clusters visually
- Understand hierarchical relationships in the data

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy (for clustering and dendrogram generation)

## Outcome

This project highlights how hierarchical clustering can be used to segment data when labels are unavailable. The dendrogram provides a useful visual tool for determining natural cluster groupings.

