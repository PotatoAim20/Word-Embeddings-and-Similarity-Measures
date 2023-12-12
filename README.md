# Word Embeddings and Document Similarity Analysis

## Overview
This repository contains a Jupyter notebook showcasing the generation of word embeddings and the calculation of document similarity. The notebook covers the entire process, including code for embedding words, computing document similarity, and visualizing the relationships between different texts using heatmaps and multidimensional scaling (MDS).

## Key Features
1. **Word Embeddings Generation:**
   - Utilizes popular word embedding techniques (Word2Vec) to represent words in a vector space.

2. **Document Similarity Calculation:**
   - Implements algorithms to calculate the similarity between documents based on their word embeddings.
     - Cosine Similarity: Measures the cosine of the angle between two vectors. It is widely
                          used for comparing documents represented as vectors in a high-dimensional space.
                          Cosine Similarity ranges from -1 (completely dissimilar) to 1 (completely similar), with 0
                          indicating orthogonality.
     - Jaccard Similarity: Computes the intersection over the union of two sets. In the context
                            of document similarity, the sets are the sets of words present in each document. Jaccard
                            Similarity ranges from 0 to 1, with 1 indicating identical sets.
     - Euclidean Distance: Measures the straight-line distance between two points in space.
                            In the context of document similarity, it quantifies how far apart the documents are in the
                            vector space. Smaller distances indicate greater similarity.
       

3. **Visualization Techniques:**
   - Visualizes document similarities using heatmaps to provide an intuitive representation of relationships.
   - Applies multidimensional scaling (MDS) to visualize high-dimensional data in a lower-dimensional space.
