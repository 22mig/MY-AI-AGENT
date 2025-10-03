🤖 AI Agent Chatbot (LangGraph + FastAPI + Streamlit)

This is a full-stack AI-powered chatbot application that integrates LangGraph agents, FastAPI backend, and an interactive Streamlit UI.
The project demonstrates dynamic model selection, retrieval capabilities, and seamless AI-driven interactions using Groq, Tavily, and OpenAI models.

🚀 Features

✅ LangGraph Agents – Build structured AI workflows & reasoning chains

✅ FastAPI Backend – Efficient request handling & API endpoint for processing prompts

✅ Streamlit Frontend – Simple, intuitive, and interactive chat UI

✅ Dynamic Model Selection – Switch between Groq, Tavily, and OpenAI models

✅ Pluggable Architecture – Easy to extend with more LLMs or tools

✅ Developer-Friendly – Clean structure for AI engineering projects

🛠 Tech Stack

Backend: FastAPI, Python

AI Frameworks: LangGraph, OpenAI API, Groq, Tavily

Frontend: Streamlit

Others: Requests, dotenv, etc.

📂 Project Structure
ai-agent-chatbot/
│── backend/                  # FastAPI Backend
│   ├── main.py                # FastAPI entry point
│   ├── routers/               # API routes
│   ├── services/              # LangGraph + AI logic
│   ├── utils/                 # Helper functions
│   ├── requirements.txt
│
│── frontend/                 # Streamlit Frontend
│   ├── app.py                 # Streamlit chat UI
│   ├── components/            # UI components
│   ├── pages/                 # Multi-page support
│
│── README.md                 # Documentation

⚡ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-agent-chatbot.git
cd ai-agent-chatbot

2️⃣ Backend Setup (FastAPI)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

3️⃣ Frontend Setup (Streamlit)
cd frontend
streamlit run app.py






Contributions are welcome! Feel free to fork this repo and submit a PR.



👉 If you want to explore the project, check the code here:
🔗 GitHub Repository
