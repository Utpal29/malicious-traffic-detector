# Malicious Traffic Detector on a Network using Machine Learning

A machine learning–based intrusion detection system (IDS) trained on the NSL-KDD dataset to classify network traffic as normal or malicious.  
The project compares multiple ML models to determine the most effective one for detecting network intrusions.

---

## 🧠 Algorithms Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Multi-Layer Perceptron (Neural Network)  
- Support Vector Machine  
- Naïve Bayes  
- AdaBoost  
- XGBoost

---

## 📊 Dataset
**NSL-KDD Dataset**  
Public dataset by University of New Brunswick  
[https://www.unb.ca/cic/datasets/nsl.html](https://www.unb.ca/cic/datasets/nsl.html)

---

## ⚙️ Workflow
1. **Data Collection:** Convert NSL-KDD `.txt` to `.csv`, load into pandas.
2. **Preprocessing:** Encode categorical columns, normalize numeric features.
3. **Visualization:** Plot attack type distributions.
4. **Model Training:** Train multiple ML classifiers with 80–20 train-test split and k-fold cross-validation.
5. **Evaluation:** Compare accuracy, precision, recall, F1-score, ROC-AUC.
6. **Result:** Random Forest achieved the best performance (≈99% accuracy).

---

## 🧩 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- xgboost

---

## 📈 Results
| Model | Accuracy | Precision | Recall | F1-score |
|--------|-----------|------------|---------|-----------|
| Random Forest | 0.99 | 0.99 | 0.99 | 0.99 |
| MLP | 0.99 | 0.98 | 0.99 | 0.99 |
| SVM | 0.98 | 0.98 | 0.97 | 0.97 |
| Decision Tree | 0.96 | 0.95 | 0.95 | 0.95 |

---

## 📘 Reference Paper
See detailed explanation in `summary.md`
