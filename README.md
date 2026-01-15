

# AI-Driven Fraud Risk Scoring Engine for Financial Transactions

This project builds an AI-powered fraud detection and risk scoring system to identify suspicious financial transactions. The model learns transaction behavior patterns and assigns a fraud risk score to each transaction, enabling proactive fraud prevention and loss reduction.

---

## 📌 Business Problem
Financial institutions process millions of transactions daily, but a small percentage are fraudulent. Manual rule-based systems fail to capture complex fraud patterns. This project uses machine learning to detect fraudulent transactions from highly imbalanced data and produce a risk score for every transaction.

---

## 📊 Dataset
The dataset contains anonymized financial transaction data with:
- Transaction amount  
- Customer behavior indicators  
- Time-based features  
- Transaction type  
- Fraud label (1 = Fraud, 0 = Legitimate)

The data is highly imbalanced, mimicking real-world fraud scenarios.

---

## ⚙️ Approach
1. Data cleaning and preprocessing  
2. Handling imbalanced data  
3. Feature engineering (behavioral and transaction features)  
4. Model training (Logistic Regression & Random Forest)  
5. Model evaluation using Precision, Recall, ROC-AUC  
6. Risk score generation using predicted fraud probability  

---

## 📈 Results
The Random Forest model achieved strong fraud detection performance and generated transaction-level risk scores that can be used to:
- Flag high-risk transactions  
- Prioritize manual investigation  
- Reduce financial losses  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🚀 How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python fraud_risk_engine.py
