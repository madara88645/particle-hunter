# Particle Hunter

Particle Hunter is an experiment to detect Higgs Boson events in the CERN dataset. The project focuses on building an efficient classification model using the XGBoost algorithm with future support for Bayesian hyper-parameter optimization via Optuna.

## Dataset

- **Source**: [Kaggle Higgs Boson Dataset](https://www.kaggle.com/competitions/higgs-boson/data)
- **Description**: Simulated events labeled as either signal (Higgs Boson) or background. After downloading, place `training.csv` inside a folder named `data/` at the project root.

## Methodology

1. **Exploratory Data Analysis (EDA)** for initial understanding and visualization.
2. **Baseline Model Creation** using XGBoost.
3. **Handling Data Imbalance** via techniques such as SMOTE or undersampling.
4. **Hyper-parameter Optimization** with Bayesian methods (Optuna).

## Results

*To be updated once optimization is complete.*

- **Best Model**: TBD
- **AUC Score**: TBD

## Installation

```bash
# Clone repository
git clone https://github.com/madara88645/particle-hunter

# Navigate to the project folder
cd particle-hunter

# Install dependencies
pip install -r requirements.txt
```

## Usage

Detailed training scripts will be provided in future updates. After installing dependencies and preparing the dataset, refer to forthcoming documentation for running experiments.

