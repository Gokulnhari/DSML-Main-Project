# 🛡️ Phishing URL Detection Using Machine Learning

This project aims to detect **phishing URLs** using machine learning techniques. It leverages a dataset with various URL-based features and builds a model to classify whether a given URL is **legitimate** or **phishing**.

## 📁 Project Structure

- `PhishingURL.ipynb`: Main Jupyter notebook containing data analysis, feature engineering, model training, and evaluation.
- `PhiUSIIL_Phishing_URL_Dataset.csv`: Dataset used for training and testing.
- `README.md`: Project documentation.

## 📊 Dataset Overview

The dataset consists of URL-based features (e.g., number of digits, presence of '@' symbol, domain length, etc.) along with a `label` column indicating:
- `0`: Legitimate URL
- `1`: Phishing URL

## 🛠️ Features of the Project

- Data preprocessing (removal of constant features)
- Feature scaling and selection using `SelectKBest`
- Model training using `RandomForestClassifier` and `SVC`
- Evaluation metrics: Accuracy, F1 Score, Confusion Matrix
- Data visualizations using `Seaborn` and `Matplotlib`

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https:https://github.com/Gokulnhari/DSML-Main-Project.git
   
