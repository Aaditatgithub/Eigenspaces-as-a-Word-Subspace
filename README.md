# Eigenspaces as a Word Subspace

Quantifying semantic relations using top k principal components. Can be looked at as an optimization problem of L2 Norm orthogonal components of relation vectors in the Grassmannian.

## Overview

This project explores the idea of representing semantic relations as subspaces in a high-dimensional vector space, using eigenspace decomposition (principal component analysis) to extract the top-k principal components. The approach treats the problem as an optimization over the L2 norm of orthogonal components of relation vectors, leveraging concepts from the Grassmannian manifold.

## Features

- **Quantifies semantic relations** between words using principal component analysis (PCA).
- **Extracts top-k principal components** to represent key semantic directions.
- **Formulates the problem as an optimization** over L2 norm orthogonal components in the Grassmannian.
- **Jupyter Notebook-based workflow** for interactive exploration and visualization.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Common scientific libraries: numpy, scipy, scikit-learn, pandas, matplotlib

Install the requirements using pip (if a requirements.txt is present, otherwise install manually):

```bash
pip install numpy scipy scikit-learn pandas matplotlib jupyter
```

### Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Aaditatgithub/Eigenspaces-as-a-Word-Subspace.git
    cd Eigenspaces-as-a-Word-Subspace
    ```

2. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

3. Open the main notebook and follow the instructions inside to run the experiments.

## Project Structure

- **Notebooks/**: Contains Jupyter notebooks with code and experiments.
- **data/** (if present): Datasets or embeddings used for experiments.
- **README.md**: Project documentation (this file).

## Concepts

- **Semantic Relation Vectors**: Represent word relationships as vectors in embedding space.
- **Principal Component Analysis (PCA)**: Used to find the directions (principal components) that capture the most variance in the relation vectors.
- **Grassmannian Manifold**: The space of all k-dimensional subspaces in n-dimensional space; used here to frame the optimization problem for subspace selection.

## Citation

If you use this repository or its ideas, please cite or reference the project.

## License

This project is provided under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or feedback, please open an issue or contact [Aaditatgithub](https://github.com/Aaditatgithub).
