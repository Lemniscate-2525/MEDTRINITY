# 🩺 MedTrinity – Disease Prediction System (ML + Flask)

MedTrinity is a machine learning–powered disease prediction system that estimates the **probability (in %)** of disease using models trained on structured **CSV medical datasets**. It demonstrates a complete **data → model → API → web interface** pipeline.


## **🔍 Project Overview**

This application allows users to input medical parameters through a web interface. The backend loads trained ML models and returns a **risk percentage** for disease likelihood.

All **3 models** were trained using **CSV files**, preprocessed in Python, and integrated into a **Flask web application** for real-time inference.


## **🧠 Machine Learning Pipeline**

```
CSV Datasets
      ↓
Data Cleaning & Validation
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering & Selection
      ↓
Train-Test Split
      ↓
Model Training (3 ML Models)
      ↓
Model Evaluation & Tuning
      ↓
Model Serialization (.pkl)
      ↓
Flask Backend Integration
      ↓
REST API Inference Endpoint
      ↓
Web UI (Frontend)
      ↓
User Inputs → Real-Time Prediction (%)
```

---

## **🛠 Tech Stack**

* **Programming Language:** Python
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Backend Framework:** Flask
* **Data Format:** CSV files
* **Deployment:** Flask local server


## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Lemniscate-2525/MEDTRINITY.git
cd MEDTRINITY

python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate   # Mac/Linux

pip install -r requirements.txt

python app.py

http://127.0.0.1:5000/




## **👥 Contributors**

* **Akshat** – Machine Learning models, training pipeline, integration
* **Garv** – Frontend + Flask UI
* **Manas** – Frontend + UI styling

---

## **⚠ Disclaimer**

This project is for **educational purposes only** and is **not a medical diagnostic system**.

