# Kaggle 2025 Bank Classification

Binary classification on bank marketing data for the August 2025 Kaggle Playground Series.

## 🔍 Problem Statement

Predict whether a client will subscribe to a bank term deposit.

This is a binary classification problem:  
- `1` = subscribed  
- `0` = did not subscribe

## 📁 Project Structure

```
├── data/               # Raw and processed datasets (excluded from Git)
├── notebooks/          # Jupyter notebooks (EDA, modeling, etc.)
├── src/                # Python modules (data cleaning, model training, etc.)
├── models/             # Saved models (excluded from Git)
├── outputs/            # Plots, tables, or other generated artifacts
├── requirements.txt    # Python dependencies
├── README.md           # Project overview
└── .gitignore
```

## ⚙️ Environment Setup

```bash
pip install -r requirements.txt
```

Python version: 3.9+

## 📊 Notebooks

- `eda.ipynb`: Exploratory data analysis
- `baseline_model.ipynb`: First pass model with minimal tuning
- `model_v2.ipynb`: Improved pipeline with feature engineering + tuning

## 🔧 Scripts

- `src/preprocess.py`: Preprocessing functions to clean the Kaggle Bank data
- `src/train.py`: Model Training

## 📈 Evaluation Metric

 (Need to figure out what Kaggle will use and insert it here)

## 📎 Data Source

Data provided via [Kaggle Playground Series – August 2025](https://www.kaggle.com/competitions/playground-series-s5e8)

## 📝 Notes

- Data and trained models are excluded from Git. See `.gitignore`.
