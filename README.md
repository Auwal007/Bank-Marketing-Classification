# 🧠 Bank Marketing Classification Project

This project explores and evaluates multiple machine learning models to predict whether a client will subscribe to a term deposit based on features from a direct marketing campaign. The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing).

---

## 📁 Dataset

- **Source**: [Bank Marketing Dataset - UCI](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **File Used**: `bank-full.csv`
- **Delimiter**: Semicolon (`;`)
- **Target Variable**: `y` (binary: `yes` or `no`)


It contains information on:

- Demographic data (age, job, marital status, education, etc.)
- Banking history (balance, housing loan, personal loan)
- Campaign data (last contact, previous outcome, etc.)

## 📊 Project Workflow

1. **Data Preprocessing**
   - Handling missing values (e.g., dealing `"unknown"` entries)
   - Encoding categorical features
   - Removing or capping outliers
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for categorical and numerical features
   - Correlation matrix and heatmaps
   - Class imbalance visualization
   - Answering some interested Questions

3. **Model Training and Evaluation**
   Multiple classification models were trained and evaluated:
   
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - XGBoost

   Evaluation Metrics:
   - Accuracy
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

4. **Model Comparison**
   - All models were compared based on accuracy and other metrics
   - Visualizations provided using heatmaps for confusion matrices
   - Use **RandomizedSearchCV** to optimize hyperparameters

## ✅ Results

Final model performance showed that **XGBoost** and **Random Forest** provided the most accurate and reliable predictions. Detailed evaluation was performed with confusion matrices and classification reports.

## 🛠️ Tools and Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

