# Extending CheMLT-F for Polymer Property Prediction
This work constitutes the polymer branch of the CheMLT-F (Mun & Fazli, 2025) project. While CheMLT-F provides a general framework for standardized chemical processing and pretrained multitask transformer models (DeBERTa) aimed at drug analysis and binding affinity prediction, this branch focuses exclusively on polymer data representation and polymer property modeling. 
## Installation and Setup

This project was developed using a Conda environment with Python 3.10.19.  
To reproduce the environment, follow the steps below.

### 1. Create and activate the Conda environment

```bash
conda create -n polymer python=3.10.19 -y
conda activate polymer
```
### 2. Install Python dependencies

```bash
pip install -r requirements.txt
```
### 3. Datasets

Download the datasets from the repository and keep them in the provided datasets/ directory. The data files are already organized in the correct structure for the notebook to load them.

## Running the code

The main notebook is in directory Training/Stratified_CheMLT-F.ipynb

To reproduce the project your active workspce should be organized as follows:
```
polymer/
│
├── Datasets
├── GrandBookData
├── Stratified_CheMLT-F.ipynb
```

Run all cells in order from top to bottom.

Data loading, preprocessing, model training, evaluation, and result visualization are all handled inside the notebook.

Dataset paths can be adjusted in the fourth configuration cell, if it is needed.

## References
Mun, V., & Fazli, S. (2025). CheMLT-F: Multitask learning in biochemistry through transformer fusion. Bioinformatics, 1–12.