# random-forest-classification
This repository contains my implementation of Random Forests (RF) for classification using Python and Scikit-learn. I used a telecommunications customer churn dataset to predict whether customers will stay or leave based on various demographic, account, and service-related features.
# Random Forests (RF) for Classification with Python

I have completed this project to implement **Random Forests** for classification using **Python** and **Scikit-learn**.  
In this project, I used a **telecommunications customer churn dataset** to predict whether a customer will stay or leave the company.  
I created this repository to share my work, code, and learning from this project.

---

## Project Overview
In this project, I implemented a **Random Forest Classifier**, which is an **ensemble learning method** that builds multiple decision trees and aggregates their predictions for better accuracy.  
I also calculated the **average correlation** between individual trees in the forest to understand predictor diversity.

---

## Objectives
- Understand **Random Forests** and how they improve classification performance
- Load and preprocess a real-world **telecommunications customer churn dataset**
- Train a **Random Forest Classifier** using Scikit-learn
- Evaluate model performance using accuracy and correlations between predictors
- Analyze feature importance for customer churn prediction

---

## About the Dataset
I used a **telecommunications dataset** that contains historical customer data, where each row represents one customer.  
The goal is to **predict customer churn** — whether a customer will stay or leave the company.

**Dataset Information:**
- **Target Column:** `Churn` → Whether the customer left within the last month
- **Features Include:**
    - Services signed up for: phone, internet, online security, streaming, etc.
    - Customer account info: contract type, payment method, monthly & total charges
    - Demographics: gender, age, partners, and dependents

**Business Insight:**  
Since retaining existing customers is less expensive than acquiring new ones,  
the analysis focuses on predicting potential churners to improve retention strategies.

---

## Installation
To run this project locally, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/random-forest-classification.git
cd random-forest-classification
pip install -r requirements.txt
