# 💳 Credit Card Fraud Detection 

## 🚀 Project Overview  
This project is a **Machine Learning-based Credit Card Fraud Detection System** designed to identify fraudulent transactions using historical transaction data.

The goal of this project is to:
- Understand real-world imbalanced data  
- Apply data preprocessing  
- Train and evaluate a classification model  
- Analyze model performance using metrics beyond accuracy  

---

## 📂 Dataset  
The dataset contains anonymized transaction records with numerical features and a binary target variable:

| Column | Description |
|--------|-------------|
| V1–V28 | PCA-transformed features |
| Amount | Transaction amount |
| Class  | 0 = Legit, 1 = Fraud |

⚠️ The dataset is highly **imbalanced**, which makes this a realistic ML problem.

---

## 🛠️ Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  

---

## 🧠 Model Used  
We used:

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
