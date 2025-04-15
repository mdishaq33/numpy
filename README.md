# numpy
# 💳 Credit Card Fraud Detection using NumPy

This is a mini data analysis project where I used **NumPy only** to detect suspicious credit card transactions using rule-based logic.

## 📌 Project Overview

- Simulated 100 credit card transactions using NumPy
- Each transaction had:
  - Transaction ID
  - Amount (₹100–₹10,000)
  - Location code (1–5)
  - Time of transaction (0–23 hrs)

## 🚨 Fraud Detection Rules

1. **High-value**: Amount > ₹8000  
2. **Odd hours**: Time between 12 AM – 4 AM  
3. If both → ⚠️ **High-Risk Transaction**

## 📊 Final Output

- Total number of high-risk transactions
- Total amount involved in suspicious activity
- Average amount of flagged transactions

## 🛠️ Technologies Used

- Python
- NumPy
- Google Colab

## 📁 File Info

- `credit_card_fraud_numpy.ipynb` – Main notebook with all code & output
- 
## 🙌 Author

**Anas** — CSE Student & Aspiring Data Scientist  
(https://github.com/mdanas33)
