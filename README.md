# 🚨 Multimodal Content Moderation Tool

An AI-powered **content moderation system** capable of detecting **NSFW images** and **hate speech in text**.  
Built as a **group project** for the **Namma Suraksha Hackathon (Finalist)**.

---

## ✨ Features
- 🖼️ **Image Classification** → Detects explicit/NSFW images  
- 💬 **Text Classification** → Flags toxic or hateful content in text  
- 📡 **Real-time API** → Sends moderator alerts via email  
- 🔒 **Environment Configurable** → Secure `.env` file for credentials  

---

## ⚙️ Setup Instructions

### 1. Create Virtual Environment
```bash
python -m venv venv
# Activate
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
3. Configure Environment
Create a .env file in the root folder with:

env
Copy
Edit
ALERT_MAIL_SENDER=<sender_mail>
ALERT_MAIL_RECIPIENT=<recipient_mail>
ALERT_MAIL_USER=<sender_mail>
ALERT_MAIL_PASS=<user_mail_passkey>
4. Run the Application
bash
Copy
Edit
python main.py
📊 Tech Stack
Backend: Python, Flask/FastAPI

ML/DL Models: TensorFlow / PyTorch

NLP: HuggingFace Transformers

Email Alerts: SMTP with .env credentials

👥 Group Project
This project was developed collaboratively.
My Contribution: Implemented the text classification pipeline for hate speech detection.
