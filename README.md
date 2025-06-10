# 🔐 Phishing URL Detection Using Machine Learning

This project focuses on detecting **phishing websites** by analyzing URL-based features using various supervised machine learning models. The pipeline involves extensive preprocessing, feature selection, and model evaluation to build a robust classifier.

---

## 🎯 Objective

To build a binary classification model that predicts whether a given URL is **legitimate (0)** or **phishing (1)** based on behavioral and structural patterns present in the URL features.

---

## 📂 Dataset

- **Source**: PhiUSIIL Phishing URL Dataset
- **Instances**: ~11,000+ rows
- **Features**: 50+ URL-based numerical features (e.g., presence of "https", URL length, number of special characters, etc.)
- **Target Variable**: `label`  
  - `0`: Legitimate  
  - `1`: Phishing

---

## 🧼 Data Preprocessing

- Removed constant and duplicate features
- Handled missing values (if any)
- Feature selection using `SelectKBest`
- Feature scaling using `StandardScaler`
- Stratified train-test split for balanced representation

---

## 🧠 Models Used

The following supervised machine learning models were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)

---

## 🔍 Feature Selection & Hyperparameter Tuning

- Feature selection: `SelectKBest(score_func=f_classif, k=10)`
- Hyperparameter tuning via `GridSearchCV`
- Evaluation metrics:
  - Accuracy
  - F1-Score
  - Confusion Matrix
  - Visualization with seaborn/matplotlib

---

## 📊 Results

✅ **Final Selected Model (e.g., Random Forest Classifier) Performance on Test Data**:
- **Accuracy**: 96.12%
- **F1-Score**: 0.95

📦 **Model Performance on Unseen Data**:
- **Accuracy**: 95.02%
- **F1-Score**: 0.947

---

## 🧩 Conclusion

This project demonstrates that URL-based features can be highly effective in detecting phishing websites. By applying robust preprocessing, feature selection, and model tuning, the final model achieves high accuracy and is well-suited for deployment in real-time phishing detection systems.

---

## 📌 Tools & Libraries

- Python
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib





   
