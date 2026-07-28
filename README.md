<div align="center">

# 🌆 UrbanBot AI
### 🚀 AI-Powered Smart City Management Ecosystem

<p align="center">
<img src="https://github.com/user-attachments/assets/b72188fa-57cd-4b05-b661-81f7a9e0f392" width="100%">
</p>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Deep%20Learning-purple?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit)
![AWS](https://img.shields.io/badge/AWS-Cloud-232F3E?style=for-the-badge&logo=amazonaws)
![MySQL](https://img.shields.io/badge/Amazon_RDS-MySQL-4479A1?style=for-the-badge&logo=mysql)
![Groq](https://img.shields.io/badge/Groq-LLM-black?style=for-the-badge)

### 🏙️ Building Safer, Smarter & More Sustainable Cities with Artificial Intelligence

</div>

---

# 🌟 Project Overview

UrbanBot AI is an integrated **Smart City Management Platform** that combines **Computer Vision**, **Machine Learning**, **Cloud Computing**, **Generative AI**, and **Real-Time Analytics** into a single application.

The platform continuously monitors city infrastructure and traffic using AI models, helping authorities improve public safety, traffic management, environmental monitoring, and citizen services.

---

# ✨ Core Features

## 🚑 Accident Detection

- Real-time accident detection using **YOLOv8**
- Automatic emergency email notifications
- Incident logging
- Live camera monitoring

---

## 🚦 Traffic Analytics

- Vehicle detection
- Traffic density estimation
- Congestion monitoring
- Intelligent traffic insights

---

## 👥 Crowd Monitoring

- Crowd density estimation
- Public gathering detection
- Real-time monitoring
- Safety alerts

---

## 🛣️ Road Damage Detection

- Pothole detection
- Road crack detection
- Infrastructure monitoring
- Maintenance recommendations

---

## 🌿 Air Quality Prediction

Machine Learning model predicts air quality based on environmental data.

Outputs include:

- AQI Prediction
- Pollution Analysis
- Health Recommendations

---

## 🤖 UrbanBot AI Assistant

Powered by **Groq Llama 3.1**

Features:

- Natural Language Questions
- SQL Database Retrieval (RAG)
- Smart City Information
- Citizen Assistance

---

## 📢 Citizen Complaint Management

Citizens can submit complaints regarding

- Roads
- Traffic
- Waste Management
- Public Safety
- Infrastructure

Authorities can monitor and manage complaints efficiently.

---

# 🏗️ System Architecture

```text
               Smart City Cameras
                       │
                       ▼
             YOLOv8 Detection Models
                       │
        ┌──────────────┬───────────────┬
        ▼              ▼               ▼
   Accident      Traffic & Crowd   Road Damage
    Detection        Analytics        Detection
        │              │               │
        └──────────────┴───────────────┘
                       │
                       ▼
                 Amazon RDS (MySQL)
                       │
                       ▼
               Streamlit Dashboard
                       │
         ┌─────────────┴─────────────┐
         ▼                           ▼
  Groq AI Chatbot            Email Alerts
```

---

# 💻 Technology Stack

## Programming

- Python

## Computer Vision

- YOLOv8
- OpenCV

## Machine Learning

- Scikit-Learn
- Pickle

## Generative AI

- Groq Llama 3.1
- Retrieval-Augmented Generation (RAG)

## Database

- Amazon RDS (MySQL)

## Cloud

- AWS EC2 (Ubuntu)

## Frontend

- Streamlit

## Email Service

- SMTP

---

# 📂 Project Modules

| Module | Description |
|---------|-------------|
| 🚑 Accident Detection | Detects road accidents in real time |
| 🚦 Traffic Analysis | Vehicle counting and congestion monitoring |
| 👥 Crowd Detection | Crowd density estimation |
| 🛣️ Road Damage | Detects potholes and road defects |
| 🌿 Air Quality | Predicts AQI using ML |
| 📢 Citizen Complaints | Complaint registration & management |
| 🤖 UrbanBot Chatbot | AI assistant with RAG |
| 📊 Dashboard | Interactive Smart City Dashboard |

---

# 📸 Application Screenshots

## 🏠 Introduction

<img src="https://github.com/user-attachments/assets/b72188fa-57cd-4b05-b661-81f7a9e0f392"/>

---

## 📊 Dashboard

<img src="https://github.com/user-attachments/assets/4e830363-652f-473b-9e19-080bb41cc713"/>

---

## 🚑 Accident Detection

<img src="https://github.com/user-attachments/assets/c5ba10d3-b52e-4587-93f1-973b4a074c1f"/>

---

## 🚦 Traffic Detection

<img src="https://github.com/user-attachments/assets/0aec80cc-e82c-422e-9c2a-00d1691e611e"/>

---

## 👥 Crowd Detection

<img src="https://github.com/user-attachments/assets/7d8f2509-b07a-4a7b-b096-1f1a42af371e"/>

---

## 🛣️ Road Damage Detection

<img src="https://github.com/user-attachments/assets/4fdcfae1-95fb-4156-bb42-73ad6209947f"/>

---

## 🌿 Air Quality Prediction

<img src="https://github.com/user-attachments/assets/c0c06bf1-3421-431f-b6c5-746978343d3b"/>

---

## 📢 Citizen Complaint Portal

<img src="https://github.com/user-attachments/assets/6385ce8b-7eca-455f-a60e-cd0b536063c1"/>

---

## 🤖 UrbanBot AI Chatbot

<img src="https://github.com/user-attachments/assets/c742c1b8-52f5-45b3-81f6-a4a428bab181"/>

---

# 🚀 Installation

```bash
git clone https://github.com/selvakumaran416-sketch/UrbanBot-Smart-City-Intelligence.git

cd UrbanBot-Smart-City-Intelligence

pip install -r requirements.txt

python -m textblob.download_corpora

streamlit run Main_App.py
```

---

# 🔐 Environment Variables

Create a `.env` file and configure:

```env
DB_HOST=
DB_PORT=
DB_USER=
DB_PASSWORD=
DB_NAME=

GROQ_API_KEY=

EMAIL_USER=
EMAIL_PASS=

EMERGENCY_EMAIL=
```

---

# ☁️ AWS Deployment

- Amazon EC2 (Ubuntu 24.04)
- Amazon RDS (MySQL)
- Streamlit Application
- SMTP Email Service

---

# 📈 Future Improvements

- 📱 Mobile Application
- 🌍 GIS Interactive Maps
- 📡 IoT Sensor Integration
- ☁️ Kubernetes Deployment
- 🔔 Push Notifications
- 📹 Multi-Camera Support
- 📊 Predictive Traffic Analytics
- 🧠 AI Decision Support

---

# 👨‍💻 Developer

## SELVAKUMARAN MUTHUSAMY

**Data Science | Machine Learning | AI | Cloud Computing**

📧 Email: selvakumaran416@gmail.com

💼 LinkedIn: https://linkedin.com/in/selvakumaran-muthusamy-376831379

🐙 GitHub: https://github.com/selvakumaran-datascience

---

<div align="center">

# ⭐ If you like this project...

### ⭐ Star the Repository
### 🍴 Fork the Repository
### 🚀 Follow for More AI Projects

### ❤️ Built with Python, YOLOv8, AWS, Streamlit & Generative AI

</div>
## ☁️ Deployment Architecture
* The system is architected for high availability on AWS. The Streamlit frontend resides on EC2, while all incident logs and system states are persisted in Amazon RDS.

