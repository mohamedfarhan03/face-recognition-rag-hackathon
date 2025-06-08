# face-recognition-rag-hackathon
# 🧠 Face Recognition Platform with Real-Time AI Q&A

This project is built for the Katomaran AI Hackathon. It is a browser-based platform that allows:
- Face registration via webcam
- Real-time face recognition
- Chat interface using RAG (Retrieval-Augmented Generation) to answer face registration queries

---

## 📌 Features

### 👤 Face Registration
- Accesses webcam
- Captures face and stores encoding with name and timestamp

### 🎥 Live Recognition
- Detects and recognizes multiple known faces in real-time
- Uses bounding boxes and labels

### 💬 Chat Interface (RAG)
- Ask questions like:
  - "Who was the last person registered?"
  - "When was Karthik registered?"
- Powered by:
  - LangChain
  - FAISS
  - OpenAI's GPT-3.5

---

## 🛠️ Tech Stack

| Module         | Tech Used                     |
|----------------|-------------------------------|
| Frontend       | React.js                      |
| Backend        | Node.js (for WebSocket), Flask API (for Python) |
| Face Recognition | Python (`face_recognition`, OpenCV) |
| RAG            | LangChain + FAISS + OpenAI GPT |
| Database       | Pickle-based storage (for prototype) |
| LLM            | OpenAI ChatGPT (user API key) |

---

## 🚀 How to Run

### 🔧 Backend Setup

1. Install dependencies:
```bash
cd backend
pip install -r requirements.txt
