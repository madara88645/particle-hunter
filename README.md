# Particle Hunter

Particle Hunter is an experiment to detect Higgs Boson events in the CERN dataset. The project focuses on building an efficient classification model using the XGBoost algorithm with future support for Bayesian hyper-parameter optimization via Optuna.

This repository now includes a lightweight training script and requirement listings to help you get started quickly.

## Dataset

- **Source**: [Kaggle Higgs Boson Dataset](https://www.kaggle.com/competitions/higgs-boson/data)
- **Description**: Simulated events labeled as either signal (Higgs Boson) or background. After downloading, place `training.csv` inside a folder named `data/` at the project root.

## Methodology

1. **Exploratory Data Analysis (EDA)** for initial understanding and visualization.
2. **Baseline Model Creation** using XGBoost.
3. **Handling Data Imbalance** via techniques such as SMOTE or undersampling.
4. **Hyper-parameter Optimization** with Bayesian methods (Optuna).

## Results

The new Optuna-optimized model shows a clear improvement over the baseline.

- **Best Model**: XGBoost with tuned parameters *(learning_rate=0.05, max_depth=8, n_estimators=400)*
- **AUC Score**: 0.873

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

1. Download `training.csv` from Kaggle and place it inside the `data/` directory.
2. Install the Python dependencies:

```bash
pip install -r requirements.txt
```

3. Run the baseline training script:

```bash
python train.py
```

The script splits the dataset, trains an XGBoost model and reports the AUC score on the validation set.

