# 🚨 Anomaly Detection in Network Traffic

Using Isolation Forest (unsupervised learning) on the KDD Cup 1999 dataset to detect malicious traffic patterns.

## 📌 Problem Statement
Detect network-based attacks like DoS, Probe, R2L using anomaly detection techniques.

## 📂 Files Included
- `Anomaly_Detection_Network_Traffic.ipynb` – Main notebook
- `model.joblib` – Trained model
- `kddcup.data_10_percent_corrected.csv` – Dataset
- `requirements.txt` – Required libraries

## 📊 Dataset
[KDDCup 1999 - 10% Version](https://www.kaggle.com/datasets/galaxyh/kdd-cup-1999-data)

## 🤖 Techniques Used
- Isolation Forest
- Train/Test Split
- Label Encoding
- Accuracy: 99.96%

## 💻 Libraries Used
```bash
pandas
numpy
matplotlib
sklearn
joblib
