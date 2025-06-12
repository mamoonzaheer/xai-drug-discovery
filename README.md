# Explainable AI for Drug Discovery

This project focuses on developing and implementing explainable AI models for drug discovery, specifically analyzing drug-target interactions and predicting binding affinities.

## Project Overview

The project uses machine learning to analyze drug-target interactions and predict binding affinities (Ki and IC50 values) based on molecular structures and target sequences. The dataset includes:

- ChEMBL IDs for compounds
- Mechanism of action information
- SMILES representations of molecules
- Target protein sequences
- Binding affinity measurements (Ki and IC50 values)

## Dataset

The project uses a comprehensive dataset (`drug_discovery.csv`) containing:
- Compound information (ChEMBL IDs, SMILES)
- Target information (protein sequences)
- Binding affinity measurements
- Mechanism of action data

Note: The dataset file `drug_discovery.csv` is not included in this repository because of size limits on GitHub.

## Features

- Multi-output regression model for predicting binding affinities
- Molecular structure analysis using SMILES representations
- Target sequence analysis
- Explainable AI components for model interpretation

## Model

The project includes a trained multi-output regression model (`multioutput_regressor_model.joblib`) that can predict:
- Ki values (binding affinity)
- IC50 values (inhibitory concentration)

## Getting Started

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. The main analysis and model development can be found in `Drug_Discovery.ipynb`

3. The trained model is available as `multioutput_regressor_model.joblib`

## Requirements

See `requirements.txt` for the complete list of dependencies.

## Project Structure

- `Drug_Discovery.ipynb`: Main Jupyter notebook containing the analysis and model development
- `drug_discovery.csv`: Dataset containing drug-target interaction information
- `multioutput_regressor_model.joblib`: Trained model for predicting binding affinities
- `requirements.txt`: List of Python dependencies
- `README.md`: Project documentation 
