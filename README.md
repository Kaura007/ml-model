# Diabetes Prediction Web App with Streamlit

A machine learning-based web application for predicting diabetes risk using patient health metrics. Built with Python, Scikit-learn, and Streamlit.

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Local Installation](#local-installation)
- [Running the App](#running-the-app-locally)
- [Deployment](#deployment-on-streamlit-community-cloud)
- [Troubleshooting](#troubleshooting)
- [License](#license)

---

## Features
- User-friendly interface for health metric input
- Diabetes risk prediction using SVM classifier
- Responsive design with Streamlit components
- Model interpretability section
- Mobile-friendly layout

---

## Prerequisites

- Python 3.8+
- pip package manager
- GitHub account (for deployment)
- Streamlit account (free)

---

## Local Installation

### 1. Clone Repository
```bash
git clone https:(https://github.com/Kaura007/ml-model)
cd ml-model
****2. Create Virtual Environment**
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate  # Windows
**3. Install Dependencies**
pip install -r requirements.txt
**Running the App Locally
Start Streamlit server**
streamlit run app.py
Local URL: http://localhost:8501
Network URL: http://192.168.x.x:8501




Input patient health metrics and get predictions!

Deployment on Streamlit Community Cloud
1. Prepare for Deployment
Ensure requirements.txt exists

Commit code to GitHub repository

Verify app.py is in root directory

2. Deploy via Streamlit
Log in to Streamlit Community Cloud

Click "New app"

Configure:
