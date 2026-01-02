-

## 📌 AML / Transaction Monitoring Project (SQL)

### 🔍 Project Overview

This project focuses on **Anti–Money Laundering (AML) transaction monitoring** using SQL. The objective is to analyze transactional data to identify **suspicious patterns, high-risk accounts, and fraud indicators** commonly used in banking and financial compliance teams.

The analysis is performed on a **simulated transaction dataset** (PaySim-style), representing real-world digital payment behavior.

---

### 🗂 Dataset Description

The dataset contains transaction-level information including:

* Sender and receiver account IDs
* Transaction type (TRANSFER, CASH_OUT, etc.)
* Transaction amount
* Simulated time variable (`step`, representing hours)
* Fraud indicators (`isFraud`, `isFlaggedFraud`)

The dataset is intentionally kept **small and lightweight** to enable efficient querying and local execution.

---

### ⚙️ Key Analyses Performed

Using SQL, the project implements multiple AML monitoring scenarios, including:

* **High-value transaction detection**
* **High transaction velocity analysis** (multiple transactions in short time windows)
* **Transfer followed by immediate cash-out patterns** (mule account detection)
* **Account-level fraud aggregation and risk ranking**
* **Comparison of actual fraud vs system-flagged fraud** (false positives / false negatives)

---

### 🧠 AML & Compliance Concepts Covered

* Transaction velocity and volume monitoring
* Fraud flag aggregation using SQL (`SUM(isFraud)`)
* Self-joins for transaction pattern detection
* Alert effectiveness evaluation
* Account-level risk profiling

---

### 🛠 Tools & Skills Used

* **SQL** (aggregation, filtering, joins, HAVING clause)
* AML transaction monitoring logic
* Data analysis and risk interpretation
* Compliance and fraud detection concepts

---

### 🎯 Outcome

The project demonstrates the ability to:

* Translate **AML red flags into SQL logic**
* Perform **account-level risk analysis**
* Support **investigation prioritization**
* Align technical SQL analysis with **compliance and regulatory expectations**

---

### 📄 Use Case

This project is suitable for roles in:

* AML / Transaction Monitoring
* Compliance & Financial Crime Analytics
* Risk & Fraud Analytics
* Banking Operations & Controls
