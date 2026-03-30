# Customer Purchase Risk Checker

A rule-based Python mini project for evaluating transaction risk using customer data and weighted scoring logic.

---

## Overview
This project simulates a simple purchase risk detection system that classifies customer transactions into:

- SAFE
- SUSPICIOUS
- HIGH RISK

The goal is to demonstrate how basic Python concepts can be applied to a real-world business problem using validation, scoring, and decision logic.

---

## Problem Statement
In real-world digital transactions, businesses need a way to detect risky purchases before processing them further.

This project uses simple rule-based logic to evaluate transaction risk based on:
- email validity
- customer age
- transaction amount
- payment status

---

## Features
- Email validation
- Rule-based risk detection
- Weighted risk scoring
- Final risk classification
- Clear output reporting

---

## Risk Rules
- Invalid email → +2
- Age below 18 → +1
- Price above 1,000,000 → +1
- Payment status is False → +2

---

## Risk Threshold
- 0–2 → SAFE
- 3–4 → SUSPICIOUS
- 5–6 → HIGH RISK

---

## Technologies Used
- Python
- Jupyter Notebook

---

## Project Structure
```text
├── README.md
├── requirements.txt
└── .gitignore
