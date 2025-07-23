# 🚨 Anomaly Detection in Network Traffic using Unsupervised Learning

This project detects anomalies in network traffic using the **KDD Cup 1999 dataset** and **unsupervised learning** (Isolation Forest). It aims to improve network security by identifying unusual patterns in real time.

---

## 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `Anomaly_Detection_KDD.ipynb` | Main Google Colab notebook with full code |
| `model.joblib` | Trained Isolation Forest model saved (optional but useful) |
| `kddcup.data_10_percent_corrected.csv` | The dataset (too big for GitHub, link provided below) |

---

## 📊 Dataset Info

We used the KDD Cup 1999 10% corrected dataset.

🔗 **Download Dataset Manually** (Required in Colab):  
https://kdd.ics.uci.edu/databases/kddcup99/kddcup.data_10_percent.gz

After download, upload `kddcup.data_10_percent_corrected.csv` to Colab during notebook execution.

---

## ▶️ How to Run (Step-by-Step)

1. Open the notebook in **Google Colab**:
   [Colab Notebook Link](https://colab.research.google.com/)

2. Upload the CSV dataset manually (if not using `files.upload()` already in notebook).

3. Run all cells step-by-step:
   - Load dataset
   - Clean and preprocess
   - Train model (Isolation Forest)
   - Predict anomalies
   - Visualize results

4. The trained model is saved as `model.joblib`.

---

## ✅ Output

- Cleaned dataset (without missing or invalid rows)
- Fitted unsupervised model
- Anomaly predictions shown visually and numerically
- Accuracy and confusion matrix (if labels used)

---

## 📌 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab
- Isolation Forest (Unsupervised ML)

---

## 🙋 Author

**Shridhar Singh**  
📧 Email: [singhshridhar916@gmail.com](mailto:singhshridhar916@gmail.com)  
🔗 GitHub: [shridharsinghh](https://github.com/shridharsinghh)  
🔗 LinkedIn: [linkedin.com/in/shridhar-singh-](https://www.linkedin.com/in/shridhar-singh-)  

---


