# 🛡️ Customer Purchase Risk Checker

A rule-based transaction risk scoring system built using Python to simulate real-world fraud detection and customer validation workflows.

---

## 📌 Overview

This project demonstrates how basic Python concepts can be applied to solve a real-world business problem:  
**evaluating the risk level of a customer transaction before processing it.**

The system analyzes multiple customer attributes and assigns a **risk score** based on predefined rules, then classifies the transaction into:

- ✅ SAFE  
- ⚠️ SUSPICIOUS  
- 🚨 HIGH RISK  

---

## 🎯 Problem Statement

In digital platforms such as **e-commerce, fintech, and online services**, not all transactions are equally safe.

Businesses need a system to:
- detect suspicious behavior early
- prevent financial loss
- enforce validation rules before processing transactions

This project simulates a **simplified risk engine** using rule-based logic.

---

## 💡 Key Features

- Email validation using string parsing
- Rule-based risk detection
- Weighted risk scoring system
- Final risk classification
- Transparent output for debugging & analysis

---

## 🧠 System Logic (Risk Rules)

Each condition contributes to a risk score:

| Condition                        | Score |
|---------------------------------|------|
| Invalid email                   | +2   |
| Age below 18                    | +1   |
| Transaction value > 1,000,000   | +1   |
| Payment status is False         | +2   |

---

## 📊 Risk Classification

| Score Range | Label        |
|------------|-------------|
| 0 – 2      | SAFE         |
| 3 – 4      | SUSPICIOUS   |
| 5 – 6      | HIGH RISK    |

---

## 🏗️ System Design (Engineering Thinking)
Input Data
↓
Data Validation (Email, Age, etc.)
↓
Rule Evaluation
↓
Risk Scoring
↓
Decision Classification
↓
Output Reporting


This mirrors real-world systems such as:
- fraud detection pipelines
- transaction validation engines
- rule-based decision systems

---

## 🛠️ Technologies Used

- Python (Core)
- Jupyter Notebook

---

## 📂 Project Structure

```text
customer-purchase-risk-checker/
│
├── notebooks/
│   └── customer_purchase_risk_checker.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

This project follows a structured pipeline:
