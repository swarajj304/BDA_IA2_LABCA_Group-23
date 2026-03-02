# Scalable Intelligence for Financial Integrity  
## Detecting Anomalies in Global Data Ecosystems  

**BDA IA2 - LAB CA, Group 23**  
Swaraj Jagtap - 16014223086  
Somaiya Vidyavihar University  

---

## 📌 Project Overview

This project implements a scalable anomaly detection framework for identifying irregular financial activity within decentralized blockchain ecosystems. The study focuses on Ethereum transaction data and applies unsupervised machine learning techniques to detect abnormal transactional behavior.

The objective is to demonstrate how scalable intelligence can be leveraged to maintain financial integrity in large-scale distributed systems.

---

## 🎯 Objectives

- Analyze Ethereum blockchain transaction data
- Perform data preprocessing and feature scaling
- Apply Isolation Forest for anomaly detection
- Identify suspicious transaction patterns
- Visualize anomalous activity
- Demonstrate scalable anomaly detection in financial ecosystems

---

## 📊 Dataset

The dataset used in this project consists of Ethereum blockchain transaction records.

It includes transactional metadata such as:

- Transaction value
- Gas usage
- Gas price
- Timestamp information
- Other numerical transaction attributes

The dataset represents decentralized financial transaction behavior within a global blockchain network.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## ⚙ Methodology

1. Data Loading and Exploration  
2. Handling Missing Values  
3. Feature Selection (Numerical attributes)  
4. Feature Scaling using StandardScaler  
5. Anomaly Detection using Isolation Forest  
6. Extraction of Suspicious Transactions  
7. Visualization of Results  

Isolation Forest was selected due to its scalability and effectiveness in detecting anomalies in high-dimensional financial datasets.

---

## 🚀 How to Run the Project

### Option 1: Using Google Colab

1. Upload `ethereum.csv`
2. Open `BDA_IA2.ipynb`
3. Run all cells sequentially

### Option 2: Run Locally

1. Clone the repository:
2. Install dependencies:
3. Launch Jupyter Notebook:
4. Open `BDA_IA2.ipynb`

---

## 📈 Output

The model classifies transactions as:

- `1` → Normal
- `-1` → Anomalous

Detected anomalies may represent:

- Abnormal transaction values
- Suspicious gas usage
- Irregular behavioral patterns
- Potential fraudulent or high-risk wallet activity

---

## 📚 Academic Context

This implementation supports the technical report titled:

**"Scalable Intelligence for Financial Integrity: Detecting Anomalies in Global Data Ecosystems."**

The project demonstrates the application of scalable machine learning techniques to decentralized financial infrastructures.

---

## 👤 Author

**Swaraj Jagtap**  
Roll No: 16014223086  
Department of Information Technology  
Somaiya Vidyavihar University  

---

## 📄 License

This project is licensed under the MIT License – see the LICENSE file for details.

This repository is developed for academic purposes as part of the BDA IA2 Lab Continuous Assessment.
