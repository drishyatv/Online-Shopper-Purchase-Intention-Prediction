# Online-Shopper-Purchase-Intention-Prediction
To predict whether a user will make a purchase based on their browsing behavior during an online shoping session
# 🛒 Online Shopper Purchase Intention Prediction

This project predicts whether an online shopper will make a purchase based on their session behavior using machine learning algorithms: **Logistic Regression**, **Random Forest**, and **XGBoost**.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository  
- **Target**: `Revenue` (1 = Purchase, 0 = No Purchase)  
- **Features**: Pages visited, bounce rates, exit rates, visitor type, month, etc.

---

## 🧪 Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

---

## 🔄 Workflow

1. Load & Explore Data (EDA)  
2. Preprocessing (Label Encoding, Scaling)  
3. Train-Test Split  
4. Model Training:  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
5. Evaluation: Accuracy, F1-score, Confusion Matrix  
6. Conclusion

---

## 📊 Model Results

| Model              | Accuracy | F1-score (Purchase) |
|--------------------|----------|---------------------|
| Logistic Regression| 86.9%    | 0.47                |
| Random Forest      | 89.6%    | 0.64                |
| XGBoost            | 88.8%    | 0.62                |

🔹 **Random Forest** performed best overall.

---

## 🧾 Conclusion

We predicted purchase intention based on online session behavior.  
**Key features** like `PageValues`, `ExitRates`, and `VisitorType` were crucial.  
The **Random Forest** model delivered the best performance.  
These insights help businesses target high-intent users and increase conversions.

---

## 🚀 Future Work

- Handle class imbalance (SMOTE, class weights)  
- Hyperparameter tuning  
- Model deployment (Streamlit/Flask)

---

## 👩‍💻 Author

**Drishya T V**  
📬 Feel free to connect or collaborate!
