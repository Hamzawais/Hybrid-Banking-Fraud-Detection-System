# Fraud Detection (Banking)

This project implements fraud detection for banking transactions using machine learning and deep learning rules.  
It includes a Jupyter Notebook, supporting Python script, and sample output.

## Project Contents
- **fraud_detection.ipynb** — Main notebook with data exploration, feature engineering, model training, and evaluation.  
- **fraud_detection_rules_deeplearning.py** — Supporting script with rule-based and deep learning logic.  
- **fraud_out.json** — Example output/config file.  
- **requirements.txt** — List of dependencies.  
- **SPLIT_GUIDE.md** — Instructions for mapping original bundle files into this repo.  

## Features
- Transaction data preprocessing and cleaning  
- Handling imbalanced data (undersampling/oversampling)  
- ML models: Logistic Regression, Random Forest, XGBoost  
- Rule-based fraud detection (deep learning rules in `fraud_detection_rules_deeplearning.py`)  
- Metrics: Precision, Recall, F1-score, ROC-AUC  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Then open and run `fraud_detection.ipynb`.

## Notes
- Include only anonymized sample data.  
- Full data should be linked externally for privacy/compliance.
