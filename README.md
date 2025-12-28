## MACHINE LEARNING APPROACHES FOR PREDICTING ESTROGEN RECEPTOR STATUS FROM BREAST CANCER GENE EXPRESSION DATA
Predictive Analytics and Machine Learning Project Work 2025 WS. Breast cancer gene expression and patient's metadata analysis with machine learning tools. 

### Overview

This repository contains a structured machine learning analysis how breast cancer gene expression (GEX) data encodes clinically relevant targets, with a particular focus on estrogen receptor (ER) status. A range of unsupervised and supervised learning techniques are explored, including dimensionality reduction, clustering, classification, model evaluation, and an LLM-augmented feature selection analysis.The project is organised into six sequential parts, each implemented as a Jupyter notebook, reflecting a machine learning workflow in biomedical data analysis.

### Directory Structure

```
├── Part_0/
│   └── 00_data_exploration.ipynb
├── Part_1/
│   └── 01_dim_red.ipynb
├── Part_2/
│   └── 02_clustering.ipynb
├── Part_3/
│   └── 03_prediction_v02.ipynb
├── Part_4/
│   └── 04_evaluation_v02.ipynb
├── Part_5/
│   └── check_the_genes.ipynb # checks if LLM-selected genes are present in the dataset
│   └── 05_LLM_VS_all_VS_PCA.ipynb
├── environment.yml
└── README.md
```

### Reproducibility
#### Local
1. Set up [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) environment
Conda environment file is provided to fully reproduce the setup used in this project.

Create the environment using:
```
conda env create -f ML_env.yml
```

2. Activate the environment:
```
conda activate ML_env
```
3. Start Jupyter Notebook

4. Run the notebooks in order: Part_0 → Part_5

Note: in each Jupyter Notebook, at the data loading step, the path to the input files should be changed to the directory where the files are saved on your local computer


### Author

Daryna Pikulska 

AHI RWTH Predictive Analytics and Machine Learning (2025WS)