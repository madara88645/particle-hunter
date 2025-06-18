# Particle Hunter

This project aims to distinguish signal (Higgs Boson) events from background events using CERN's Higgs Boson dataset. The primary goal is to build an efficient classification model using the XGBoost algorithm.

## Dataset

- **Source**: [Kaggle Higgs Boson Dataset](https://www.kaggle.com/competitions/higgs-boson/data)
- **Description**: The dataset consists of simulated events labeled as either signal (Higgs boson events) or background. Download the dataset from the above Kaggle link and place it inside the `data/` folder.

## Methodology

The project includes the following steps:

1. **Exploratory Data Analysis (EDA)**: Initial understanding and visualization of the data.
2. **Baseline Model Creation**: Developing a basic model using XGBoost.
3. **Handling Data Imbalance**: Applying techniques such as SMOTE or undersampling to address class imbalance.
4. **Hyperparameter Optimization**: Tuning XGBoost parameters using Bayesian Optimization (optuna).

## Results

*(To be updated upon final optimization)*

- **Best Model**:
  - AUC Score: TBD
  - Classification Report: TBD

## Installation & Usage

To set up and run the project:

```bash
# Clone repository
git clone <(https://github.com/madara88645/particle-hunter)>

# Navigate to the project folder
cd particle-hunter

# Install dependencies
pip install -r requirements.txt
