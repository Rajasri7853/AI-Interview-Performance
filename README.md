# AI-Interview-Performance

# 🤖 AI Interview Practice Buddy

A smart, interactive AI-powered interview simulator built using **Streamlit** and integrated with **n8n workflows**. This app helps users prepare for job interviews by simulating real-world, role-specific questions and providing constructive feedback using Gemini AI.

---

## 🔍 Features

- 🧠 Role-specific interview questions
- ✍️ Answer input with live feedback
- 🔗 Integration with **n8n** via webhook
- 🤖 AI-generated suggestions for improvement
- 💡 STAR method-based evaluation tips

---

## 📦 Tech Stack

| Component  | Technology          |
|------------|---------------------|
| Frontend   | Streamlit (Python)  |
| AI Engine  | Gemini Pro API (Google) |
| Automation | n8n (Open-source Workflow Automation Tool) |
| HTTP Comm. | Webhooks + JSON     |

---

## 🚀 How It Works

1. User selects a **job role** (e.g., AI Engineer).
2. Gemini generates an **interview question**.
3. User types their **answer** in Streamlit.
4. Streamlit sends the input to **n8n via webhook**.
5. n8n processes and returns **feedback**.
6. Feedback is shown directly in the Streamlit app.

---

## 🛠️ Setup Instructions

### 🔗 Prerequisites
- Python 3.10+
- Streamlit
- n8n (self-hosted or desktop)
- Gemini API key from [https://ai.google.dev](https://ai.google.dev)

---

### 🧱 Installation

#### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/ai-interview-practice-buddy.git
cd ai-interview-practice-buddy
