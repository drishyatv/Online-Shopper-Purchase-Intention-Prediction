# 🛍️ Online Shopper Purchase Intention Prediction

## 📌 Overview
This machine learning project predicts whether a user will make a purchase on an e-commerce site using behavioral data. The dataset is from the UCI Machine Learning Repository.

We applied and compared:
- Logistic Regression
- Random Forest
- XGBoost

---

## 📊 Dataset Info
- 🔗 Source: UCI ML Repository  
- 🧾 Rows: 12,330 | Features: 18  
- 🎯 Target: `Revenue` (1 = Purchase, 0 = No Purchase)

---

## 🔎 Steps Followed
1. **EDA** – Understand features & class imbalance  
2. **Preprocessing** – Encoding, scaling, removing duplicates  
3. **Train-Test Split** – 80/20 ratio  
4. **Modeling** – Train & evaluate 3 classifiers  
5. **Metrics** – Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## ✅ Model Results

| Model              | Accuracy | F1-Score (Purchase) | Recall |
|--------------------|----------|---------------------|--------|
| Logistic Regression| 86.9%    | 0.47                | 0.34   |
| Random Forest      | **89.6%**| **0.64**            | 0.55   |
| XGBoost            | 88.8%    | 0.62                | **0.56** |

---

## 📌 Conclusion
- **Random Forest** is the top performer with highest accuracy and F1-score.
- **XGBoost** is better at identifying more buyers (higher recall).
- 🔄 **Recommendation**: Use **Random Forest** for balanced results, **XGBoost** when **recall is priority**.

---

## 🧰 Tools
Python, Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib

---

## 👩‍💻 Author
**Drishya T V**  
_Entri Elevate – Data Science and Machine Learning_
