## Breast Cancer Dataset Analysis
This pet project aims to analyze breast cancer datasets using various machine learning techniques, including data scaling, dimensionality reduction using t-SNE (t-Distributed Stochastic Neighbor Embedding), and clustering using K-means and hierarchical clustering algorithms
# Steps
1. Data Preprocessing:
   The dataset is preprocessed to handle missing values, encode categorical features if any, and normalize the data
2. Dimensionality Reduction
   t-SNE (t-Distributed Stochastic Neighbor Embedding) is employed to reduce the high-dimensional breast cancer dataset into a lower-dimensional space while preserving the structure of the data.
3. Clustering:
   K-means clustering is performed on the reduced dataset to partition it into distinct clusters based on similarities.
Hierarchical clustering is also utilized to create a hierarchy of clusters, revealing the underlying structure of the data.
# Results
KMeans: ARI = 0.6707206476880808
Agglomerative CLustering: ARI = 0.5750409366326297
