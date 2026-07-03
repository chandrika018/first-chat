# 🤖 AI Chatbot using Groq + Streamlit

An intelligent AI-powered chatbot built with **Python**, **Streamlit**, and the **Groq API**. The chatbot provides fast, accurate, and natural conversational responses through a clean and responsive web interface.

## 🌐 Live Demo

🚀 **Try the chatbot here:**
https://firstchat.streamlit.app/

---

## 📌 Features

* 💬 Interactive chat interface
* ⚡ Fast responses using Groq LLM
* 🎨 Clean and responsive Streamlit UI
* 📝 Chat history support
* 🔒 Secure API key management using Streamlit Secrets
* ☁️ Deployed on Streamlit Community Cloud

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Groq API
* python-dotenv
* Requests

---

## 📂 Project Structure

```text
AI-Chatbot/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
└── .streamlit/
    └── secrets.toml   (Not uploaded to GitHub)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.streamlit/secrets.toml` file and add your Groq API Key:

```toml
GROQ_API_KEY="your_groq_api_key"
```

> **Important:** Never upload your API key to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser automatically.

---

## 🚀 Deployment

This project is deployed using **Streamlit Community Cloud**.

For deployment:

1. Push the project to GitHub.
2. Connect the GitHub repository to Streamlit Community Cloud.
3. Add your `GROQ_API_KEY` under **App Settings → Secrets**.
4. Deploy the application.

---

## 📸 Screenshot

<img width="1890" height="903" alt="Screenshot 2026-07-02 222328" src="https://github.com/user-attachments/assets/e8607f7e-a3a6-43cb-8ea6-2e070a3d4b38" />




