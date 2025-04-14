# Kidney Stone Detection using IBM Watson (No Code Project)

## 🧠 Project Overview

This project focuses on detecting **kidney stones** using IBM Watson’s **no-code AI tools**, especially **Watson AutoAI**. By utilizing AutoAI and Watson Machine Learning, we built and deployed a machine learning model that classifies whether a patient is likely to have kidney stones based on diagnostic data.

The goal is to demonstrate the **power of no-code AI** in healthcare diagnostics and enable quick, efficient solutions without writing a single line of code.

---

## 🔧 Tools & Technologies

- **IBM Watson Studio**
- **Watson AutoAI**
- **Watson Machine Learning**
- **IBM Cloud Object Storage**

## 🚀 Steps to Build the Project

### 1. Upload Data
- Open **IBM Watson Studio**
- Create a new **AutoAI experiment**
- Upload `kidney_stone_data.csv` to IBM Cloud Object Storage

### 2. Train Model Using AutoAI
- Launch the AutoAI experiment
- Select the target column (`Diagnosis`)
- AutoAI will automatically:
  - Clean and preprocess the data
  - Perform feature engineering
  - Train multiple models
  - Evaluate and compare performance (accuracy, F1 score, etc.)

### 3. Select and Deploy the Best Model
- Choose the best performing model
- Click on **"Deploy"** to create a **Web Service**
- Note the **Deployment URL** and **API Key**

---
