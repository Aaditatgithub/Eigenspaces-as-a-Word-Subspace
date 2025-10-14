# Eigenspaces as a Word Subspace

This project explores the geometric structure of word relationships in vector space, treating collections of word pairs expressing a relation as a subspace (or "eigenspace") within various word embedding models.

## Overview

- **Motivation:** Natural language relations (like "country-capital" or "object-material") are typically represented as pairs in embedding space. This project investigates how these relations can be described as lower-dimensional subspaces, capturing the essence of each relation geometrically.

- **Core Notebooks:**
  - [`Relation_PCA.ipynb`](https://github.com/Aaditatgithub/Eigenspaces-as-a-Word-Subspace/blob/main/Relation_PCA.ipynb):  
    - Finds low-dimensional subspaces that capture 95% of the variance for a given relation.
    - Projects relation pairs into these subspaces and measures how "leaky" (orthogonal) off-relation pairs are.
    - Finds nearest neighbors in embedding space for given words.
    - Supports multiple embeddings: Word2Vec, Glove, BERT, RoBERTa, SBERT, LABSE.
    - Contains curated sets of word pairs for many semantic relations (e.g., agent-verb, patient-verb, country-capital, part-whole, etc.).
  - [`Subspace_Similarity.ipynb`](https://github.com/Aaditatgithub/Eigenspaces-as-a-Word-Subspace/blob/main/Subspace_Similarity.ipynb):  
    - (Compares similarity between different relation subspaces and investigates their overlaps using the above geometrical framework.)

- **Reference Paper:**  
  - [`IEEE-Paper.pdf`](https://github.com/Aaditatgithub/Eigenspaces-as-a-Word-Subspace/blob/main/IEEE-Paper.pdf): Formal write-up of the approach, methods, and findings.

## Features

- **Relation Subspace Extraction:**  
  Extracts and analyzes lower-dimensional subspaces for a wide variety of semantic relations using PCA and deflation methods.

- **Multi-embedding Support:**  
  Works across popular embedding architectures (Word2Vec, Glove, BERT variants, etc.).

- **Code Modularization:**  
  Includes functions for embedding loading, pairwise similarity, and subspace operations.

- **Rich Relation Data:**  
  Provides hand-curated lists of word pairs for dozens of everyday and knowledge-intensive semantic relations.

## Getting Started

1. Install Python packages: numpy, pandas, matplotlib, tensorflow, torch, transformers, etc.
2. Open the notebooks in Jupyter or Colab.
3. Run the cells to analyze relations, visualize subspaces, and compare embedding models.

## Applications

- Linguistic relation probing
- Analogy and analogy-solving tasks
- Embedding space diagnostics
- Cross-model comparison of semantic structure

---

For details on methodology, see the notebooks and the included IEEE paper.
