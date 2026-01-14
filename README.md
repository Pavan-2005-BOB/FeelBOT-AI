Predictive Modeling of Credit Scores Through Logistic Regression
# Predictive Modeling of Credit Scores Through Logistic Regression

![PySpark](https://img.shields.io/badge/PySpark-3.0%2B-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This project implements a scalable **Credit Scoring Model** using **Apache Spark (PySpark)**. It automates the risk assessment process by analyzing financial behaviors (such as debt ratio, age, and payment history) to predict the likelihood of serious delinquency in the next 2 years.

## 🚀 Key Features
* **Distributed Processing:** Utilizes PySpark MLlib to handle large-scale financial datasets.
* **Feature Engineering:** Implements `VectorAssembler` to aggregate 10+ financial features.
* **Predictive Modeling:** Uses **Logistic Regression** for binary classification (Risk vs. No Risk).
* **Evaluation:** Validated using **AUC-ROC** metrics to ensure high precision.

## 🛠️ Tools & Technologies
* **Language:** Python
* **Library:** PySpark (MLlib, SQL)
* **Environment:** Google Colab / Jupyter Notebook
* **Dataset:** "Give Me Some Credit" (Financial Distress Prediction)

## 📊 Results
| Metric | Value |
| :--- | :--- |
| **Algorithm** | Logistic Regression |
| **AUC-ROC** | ~0.81 |
| **Accuracy** | ~93% |

## 💻 How to Run
1.  Open the **[Google Colab Notebook](https://colab.research.google.com/github/Pavan-2005-BOB/FeelBOT-AI/blob/main/Predictive_Modeling_of_Credit_Scores_Through_Logistic_Regression.ipynb)**.
2.  Upload the `cs-training.csv` file (available in this repo).
3.  Run all cells to execute the Training and Evaluation pipeline.

## 📜 Credits
* **Author:** Pavan Kumar Naika N
* **Institute:** Yenepoya Institute of Technology
* **Organization:** Tata Consultancy Services (TCS) Industry Project
