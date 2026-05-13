\# GLU-Net: An Explainable Global–Local Multi-Task Framework for Industrial Visual Anomaly Detection and Coarse Localization



This repository contains the source code, experimental notebooks, configuration files, evaluation scripts, and reproducibility materials associated with the manuscript:



\*\*GLU-Net: An Explainable Global–Local Multi-Task Framework for Industrial Visual Anomaly Detection and Coarse Localization\*\*  

Submitted to \*The Visual Computer\*.



\## Overview



GLU-Net is an explainable global–local multi-task framework for industrial visual anomaly detection and coarse localization. The framework combines an image-level anomaly classification branch with a U-Net-like local decoder to generate anomaly heatmaps for operator-oriented visual decision support.



\## Repository contents



This repository includes:



\- Baseline architecture screening notebooks

\- SG-GLANet benchmark implementation

\- GLU-Net implementation

\- Training and validation workflow

\- Official test-set evaluation scripts

\- Category-level performance analysis

\- Threshold sensitivity analysis

\- Formal heatmap-alignment analysis

\- Figure and table generation materials

\- Reproducibility documentation



\## Dataset



The experiments were conducted using the Visual Anomaly (VisA) dataset. The raw dataset is not redistributed in this repository due to size and licensing considerations. Please see `docs/data\_access.md` for dataset access instructions, expected directory structure, and preprocessing details.



\## Environment



The experiments were originally conducted in a Kaggle notebook environment with GPU acceleration. To install the required Python dependencies, use:


## Archived release

The peer-review version of this repository is archived on Zenodo with a version-specific DOI:

https://zenodo.org/records/20155544


```bash

pip install -r requirements.txt

