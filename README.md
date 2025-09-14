# Credit Card Fraud Detection

This project is a Machine Learning model to detect fraudulent credit card transactions using my own dataset (`creditcard.csv`).

---

## Project Overview
- Fraudulent transactions are rare, so the dataset is **imbalanced**.
- Machine learning models are trained to classify whether a transaction is fraud or not.
- Models used:
  - Logistic Regression
  - Random Forest
  - Other classifiers (as explored in the notebook)

---

## Dataset
The dataset used in this project is custom (`ascreditcard.csv`).  
You can download it from Google Drive (view-only):  

 [Download Dataset from Google Drive](https://drive.google.com/file/d/1Xs7mEGoUv_Rt7HBMvnNc7_0_7H7g32SF/view?usp=drive_link)


## Requirements
Install the dependencies before running:

numpy
pandas
matplotlib
seaborn
scikit-learn


If using pip:
```bash
pip install -r requirements.txt

How to Run
1.Clone this repository:

git clone https://github.com/<sd-sujal>/credit-card-fraud-detection.git
cd credit-card-fraud-detection

2.Open the Jupyter Notebook:

jupyter notebook credit_card_fraud_detection.ipynb

3.Run all cells to:

Load the dataset as (creditcard.csv)
Preprocess the data
Train the models
Evaluate performance

Results:
1.Evaluated using:
	Precision
	Recall
	F1-Score
	Confusion Matrix

2.Random Forest achieved better results compared to Logistic Regression.

Future Improvements:

1.Handle imbalance using SMOTE / resampling.
2.Try advanced algorithms like XGBoost or LightGBM.
3.Build a simple web app using Flask or Streamlit for deployment.

Created on Linux (Xubuntu) with Python.