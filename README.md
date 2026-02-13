# DYNAMIC-AGENTIC-SYSTEM-BUILDER
🧬 Nexus: Dynamic Agentic System Builder  Nexus is a dynamic multi-agent orchestration platform built using Streamlit, LangChain, LangGraph, and Google Gemini. It allows users to create, configure, and execute custom AI agent teams through a simple CSV upload without hardcoding workflows.

📁 Project Folder
│
├── drl.py
├── dev_team.csv
├── edu_team.csv
├── writing_team.csv
└── README.md

SYSTEM ARCHITECTURE
User Input
     ↓
Supervisor Agent
     ↓
Specialized Worker Agents
     ↓
(If code needed)
Tool Executor (Python Sandbox)
     ↓
Supervisor Decision
     ↓
FINISH

⚙️ Installation
Create Virtual Environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

Install Dependencies
pip install -r requirements.txt
or
pip install streamlit langchain langgraph langchain-google-genai pandas

🔑 Setup Gemini API Key
You need a Google Gemini API key.
Get it from:
https://makersuite.google.com/app/apikey

Run the main file:
streamlit run drl.py

🧩 Creating an Agent System
Click Create New System
Provide a system name
Upload a CSV file with Role & Instrictions




