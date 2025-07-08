# 🚨 Automated Insurance Claim Fraud Detection System

This project uses supervised (XGBoost) and unsupervised (Isolation Forest) learning to detect potentially fraudulent insurance claims and rank them for human investigation.

---

## 🧠 Features
- XGBoost Classifier with fraud probability
- Isolation Forest anomaly detection
- SHAP explainability (per-claim & global)
- Data preprocessing (handling missing/categorical/numeric)
- Output export with predicted labels and fraud risk scores

---

## 📁 Folder Structure

- `data/` – Input datasets and output CSVs
- `models/` – Trained ML models and preprocessing pipeline
- `notebooks/` – Jupyter notebook for training and evaluation
- `outputs/` – Visualizations (SHAP plots, etc.)

---

## 🚀 How to Run

```bash
# Clone repo
git clone https://github.com/your-username/fraud-detection-system.git
cd fraud-detection-system

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/01_fraud_detection_pipeline.ipynb

