# End-to-End Chest Cancer Classification with MLflow

## Overview
This project delivers a reproducible, MLflow-tracked workflow for binary chest cancer classification from medical images or tabular features.

## Features
- Modular data preprocessing, training, and evaluation scripts
- Experiment tracking with MLflow
- Visualizations of results (accuracy, loss, ROC curves)


## Quickstart
git clone https://github.com/GirishKGit/end-to-end-chest-cancer-classification-with-mlfow.git
pip install -r requirements.txt
python train.py --config configs/default.yaml
python evaluate.py --model outputs/best_model.pth
mlflow ui

## Repo Structure
data_prep.py
train.py
evaluate.py
mlflow_utils.py
configs/
README.md
requirements.txt

## Contact

## 🤝 Contact

Girish Kumar Ramachandra  
[GitHub](https://github.com/GirishKGit)


