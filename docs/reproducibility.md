```markdown

\# Reproducibility instructions



This document describes how to reproduce the main experiments reported in the manuscript.



\## Computational environment



The experiments were conducted in a Kaggle notebook environment using GPU acceleration. Mixed-precision training was used where appropriate.



\## Random seed



A fixed random seed of 42 was used for Python, NumPy, and PyTorch operations.



\## Main experimental stages



The workflow consists of three main stages:



1\. Baseline architecture screening and fine-tuning

2\. GLU-Net training and validation-level ablation analysis

3\. Official test-set evaluation, category-level analysis, threshold analysis, and heatmap-alignment analysis



\## Notebook order



Run the notebooks in the following order:



```text

notebooks/01\_baseline\_screening.ipynb

notebooks/02\_glunet\_training\_ablation.ipynb

