# New Eigenvectors from Eigenvalues Calculation
This repository implements this [paper](https://arxiv.org/pdf/1908.03795.pdf) that allows us to calculate eigenvectors from eigenvalues elegantly through PyTorch that allows your code to run on your CPU, GPU, or TPU.

Easily run it on your browser through Google Colab or copy the function locally.

## Run Notebook on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ritchieng/eigenvectors-from-eigenvalues/blob/master/notebooks/comparison.ipynb)

## Core Equation: Lemma 2

**Lemma 2.** __The norm squared of the elements of the eigenvectors are related to the eigenvalues and the submatrix eigenvalues,__

$$
| v_{i, j} | ^ 2 \prod_{k=1; k \neq i}^{n} (\lambda_i (A) - \lambda_k (A)) = \prod_{k=1}^{n - 1}  (\lambda_i (A) - \lambda_k (M_j))
$$


## Authors and Abstract
Peter B. Denton, Stephen J. Parke, Terance Tao, and Xining Zhang
```
We present a new method of succinctly determining eigenvectors
from eigenvalues. Specifically, we relate the norm squared of the elements of
eigenvectors to the eigenvalues and the submatrix eigenvalues.
```

## Dependencies
- PyTorch 1.9.1 (can be most versions of PyTorch as I used very core basic PyTorch functions)
- Python 3.8 (doesn't matter much as I use basic operations)

## Code Repository Citation
- If you would like to give some credit to this code implementation, these are the relevant links.
    - [![DOI](https://zenodo.org/badge/221868248.svg)](https://zenodo.org/badge/latestdoi/221868248)
    - [Eigenvectors from Eigenvalues CPU and GPU Implementation](https://www.researchgate.net/publication/337322294_Eigenvectors_from_Eigenvalues_CPU_and_GPU_Implementation)

## License
MIT
