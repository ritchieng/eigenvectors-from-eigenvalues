# New Eigenvectors from Eigenvalues Calculation
This repository implements this new [paper](https://arxiv.org/pdf/1908.03795.pdf) that allows us to calculate eigenvectors from eigenvectors elegantly through PyTorch.

Full credits given to the **original authors** and the **numpy implementation by Leo Dirac**. 

I ported this to PyTorch as a lot of my workflows are on the GPUs with PyTorch.

## Run Notebook on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ritchieng/eigenvectors-from-eigenvectors/blob/master/notebooks/comparison.ipynb)


## Core Equation
![./images/lemma2.png]

This is the core equation you will notice being referenced as `equation 2` in the code.

## Dependencies
- PyTorch 1.3.1
- Python 3.6

## Full Credits
- [Original authors' paper](https://arxiv.org/pdf/1908.03795.pdf)
- [Leo Dirac numpy implementation](https://github.com/leopd/geometric-intuition/blob/master/linear-algebra/eigenvectors%20from%20eigenvalues.ipynb)

## License
MIT
