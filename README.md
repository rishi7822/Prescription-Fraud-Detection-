# Prescription-Fraud-Detection-
A thesis project focused on detecting prescription fraud using machine learning and AI techniques. Developed in collaboration, this solution leverages classification models to identify fraudulent prescriptions based on patterns in medical and pharmacy data.

# 🚀 Prescription Fraud Detection – Fullstack AI-Powered App

An end-to-end web platform designed to **detect prescription fraud** using machine learning, rule-based checks, and SHAP explainability. This project brings together powerful backend intelligence and a modern, interactive frontend dashboard for healthcare analytics and fraud detection.

---

## 🧠 Tech Stack

### ⚙️ Backend
- **FastAPI** (Python)
- **Machine Learning Models** (Isolation Forests, Risk Classifier)
- **SHAP** for feature attribution
- **Pandas, NumPy, Scikit-learn**

### 💻 Frontend
- **Vite + React.js**
- **Tailwind CSS**
- **React Router**
- **Axios for API calls**

---

## 📦 Features

✅ ML + Rule-based medication risk classification  
✅ Dual Isolation Forests (general + patient-specific anomaly detection)  
✅ Real-time SHAP feature importance visualization  
✅ Authenticated access (login)  
✅ Dashboard UI with fraud predictions, confidence levels, and risk scores  
✅ Logs every prediction to a `.csv` for audit trails  
✅ Secure CORS connection between frontend and backend  

---

## 🔌 How to Run the App Locally

### 1. 📡 Backend – FastAPI

```bash

✅ API will be live at: http://localhost:8000


2. 💻 Frontend – React + Vite + Tailwind CSS
bash
Copy
Edit
cd Frontend
npm install
npm run dev
✅ Frontend will run at: http://localhost:5173


cd Backend
pip install -r requirements.txt
uvicorn app:app --reload



API Endpoints
Method	Route	Description
POST	/auth/login	Login (email + password)
POST	/predict	Predict fraud using ML model
GET	/user/...	(Optional) User-specific routes


Sample Output
Prediction Result: Fraud / Not Fraud

Risk Score: 0.0–1.0

SHAP Graph: Top contributing features to decision

Prediction History Log: Backend/predictions.csv

🔐 Security
Password-based login (expandable to OAuth2)

CORS-enabled FastAPI server

Token-ready backend for future JWT integration

🎯 Future Enhancements
✅ Role-based dashboards (Doctor, Admin, Analyst)

✅ Export reports as PDF

🔄 Model retraining on new data

🐳 Docker containerization for easy deployment

☁️ Cloud deployment (e.g., on GCP/AWS)

👥 Team
Developed as part of a thesis project by a cross-functional team of data scientists and developers.
