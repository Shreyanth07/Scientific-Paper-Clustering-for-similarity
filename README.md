# Scientific-Paper-Clustering-for-similarity

This project is designed to cluster scientifical papers in the arxiv database based on their abstract using unsupervised ML methods. This clusters the papers that are similar and helps us to find the relevant paper for reference.

Ising clustering for labelling along with dimensionality reduction for visualization, the collection of papers are represented as a scatter plot. 
Papers of highly similar topics will share a label and plotted near one another. Furthermore I have used topic modelling to find the keywords of each cluster. 
This can help us to find publications with similar research backgrounds and compare them.

The data must be prepared accordingly so that it can be processed by a clustering model. I have used NLP to prepare the data. 
I have also tested on how certain preprocessing steps could affect the quality of the clusters (stops word removing, handling different languages, different vectorization strategies).

The approach I followed for this project includes,
1. Loading Data
2. EDA and some data-cleaning / feature engineering
2. Parse the text from the abstract of each paper & Pre-processing using NLP (Natural Language Processing)
3. Convert each abstract into a feature vector using TD-IDF (Term Frequency–inverse Document Frequency).
4. Use PCA (Principal Component Analysis) for dimensionality reduction.
5. Applying Dimensionality Reduction to each feature vetor using t-SNE (t-Distributed Stochastic Neighbor Embedding) & umap (Uniform Manifold Approximation and Projection)
6. Applying k-Means for clustering.
Visualize clusters as an iterative scatter plot.
7. Apply topic modelling for each clusters.

![t-SNE with Kmeans Labels](https://user-images.githubusercontent.com/70295717/190561676-e6869763-1794-40f3-be25-db2d68d3fc0e.png)

![umap with Kmeans Labels](https://user-images.githubusercontent.com/70295717/190561823-33728471-b5fc-4b12-8c1e-1944624fe701.png)
