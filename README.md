# 🛡️ AegisCare - Empowering Elderly Care with Multi-Agent AI

AegisCare is an AI-powered, multi-agent system designed to revolutionize elderly care by ensuring safety, health monitoring, daily activity assistance, and emotional well-being for seniors living independently.

---

## 📌 Problem Statement

With the global elderly population growing, there is a rising need for smart, autonomous systems to:

- Prevent missed medications and appointments  
- Enable faster emergency response in case of falls or anomalies  
- Reduce isolation by providing emotional support  
- Integrate various care aspects seamlessly through intelligent agent communication  

---

## 🧠 Solution Overview

AegisCare introduces a **multi-agent architecture**, where each AI agent is responsible for a specific domain and collaborates with others in real time:

- 🩺 `Health Agent`: Monitors vital signs like heart rate, BP, glucose  
- ⚠️ `Behavior Agent`: Detects falls and prolonged inactivity  
- ⏰ `Reminder Agent`: Sends voice reminders for meds and routines  
- 🚨 `Alert Agent`: Notifies caregivers and medical personnel  
- 🎵 `Emotional Agent`: Engages user through music, news, and friendly chat  

---

## 🔧 System Architecture

```text
AegisCare/
├── frontend/              # UI - React or Flutter
├── backend/               # FastAPI-powered backend
│   ├── app.py
│   ├── agents/
│   │   ├── health_agent.py
│   │   ├── behavior_agent.py
│   │   ├── reminder_agent.py
│   │   ├── alert_agent.py
│   │   └── emotional_agent.py
│   ├── utils/
│   └── models/
├── ml-models/             # Trained ML models for anomaly detection
├── sensors/               # IoT code (Raspberry Pi / Arduino)
└── README.md              # Project documentation
