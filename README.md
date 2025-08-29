# Online-Shopper-Purchase-Intention-Prediction

📌 Project Overview

This project focuses on predicting whether an online shopper will make a purchase(Revenue 1) or not(Revenue 0) based on their browsing behavior. Using the UCI Online Shoppers Purchasing Intention Dataset, I perform data exploration, outlier handling, preprocessing, and apply machine learning models to classify purchase intention.

The goal is to identify the most accurate model for predicting customer purchase behavior.


📂 Steps in the Project

✅ Step 1: Import Libraries & Load Dataset

Imported essential Python libraries (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost).

Loaded the dataset into a Pandas DataFrame.

✅ Step 2: Exploratory Data Analysis (EDA)

Checked dataset shape, column types, and summary statistics.

Verified missing values and duplicates.

Performed univariate and bivariate analysis using histograms, boxplots, and countplots.

Created a correlation heatmap to understand relationships.

✅ Step 3: Outlier Handling (IQR Method)

Applied Interquartile Range (IQR) technique.

Instead of removing outliers, capped them within the upper and lower bounds.

Applied to key numerical features like Duration, BounceRates, ExitRates, PageValues.

✅ Step 4: Data Preprocessing

Encoded categorical columns (Month, VisitorType, Weekend).

Converted target column Revenue into binary integers.

Standardized numerical features using StandardScaler.
✅ Step 5: Train-Test Split

Split dataset into training and testing sets.

Used 80% training, 20% testing with random_state=42 for reproducibility.

✅ Step 6: Model Building & Evaluation

Implemented 3 Machine Learning models:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Evaluated models using Accuracy, F1-score, and Confusion Matrix.

Visualized confusion matrices for performance comparison.


📊 Results & Conclusion

Random Forest and XGBoost performed the best.

Both models achieved higher F1-score and accuracy compared to Logistic Regression.

These models are most suitable for predicting Online Shopper Purchase Intention.

📁 Dataset

The dataset used in this project is from the UCI Machine Learning Repository.


🚀 Technologies Used

Python 🐍

Pandas, NumPy → Data Handling

Matplotlib, Seaborn → Data Visualization

Scikit-learn → Preprocessing, ML models

XGBoost → Gradient Boosted Trees

Jupyter Notebook / Google Colab


📌 Final Note

This project demonstrates how EDA + Preprocessing + Outlier Handling + ML Models can effectively be combined to solve a real-world classification problem.
.
