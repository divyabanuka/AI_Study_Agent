# 🤖 AI Study Agent

An intelligent AI Study Agent built using Python, Streamlit, and Google Gemini API.

The agent understands the user's request, decides what action is needed, uses the appropriate tool, processes the result, and provides a response.
 
 ## 🌐 Live Demo

🔗 [Open AI Study Agent](https://aistudyagent-gqykextub5hsmgj4nkpvon.streamlit.app/)

## 🚀 Features

- 🤖 AI-powered study assistant
- 🧮 Calculator tool
- 📚 Study plan generator
- 🕒 Current date and time tool
- 💬 Conversation memory
- 🖥️ Interactive Streamlit interface
- 🔐 API key stored securely using Streamlit Secrets

## 🔄 Agent Workflow

Understand Task
      ↓
Decide Action
      ↓
Use Tool
      ↓
Process Result
      ↓
Respond

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- Google GenAI SDK

## 🔧 Tools

### 🧮 Calculator

Performs mathematical calculations.

Example:

calculate 125*48

Result:

6000

### 📚 Study Plan Generator

Creates a study plan based on the subject and available study time.

Example:

Create a study plan for Machine Learning for 2 hours

Result:

- 45 minutes - Learn concepts
- 45 minutes - Practice problems
- 30 minutes - Revision and notes

### 🕒 Current Time

Provides the current date and time.

Example:

What is the current time?

## 📁 Project Structure

AI_Study_Agent/
│
├── app.py
├── agent.py
├── tools.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── .streamlit/
    └── secrets.toml

## ▶️ How to Run

Install the required packages:

pip install -r requirements.txt

Add your Gemini API key to:

.streamlit/secrets.toml

Use:

GEMINI_API_KEY = "YOUR_API_KEY"

Run the application:

python -m streamlit run app.py

The application will open in your browser.

## 🔐 Security

The Gemini API key is stored securely using Streamlit Secrets and is excluded from GitHub using .gitignore.

Never share your API key publicly.

## 🎯 Module 5

This project demonstrates:

- AI Agents
- State management
- Tool calling
- Agent workflow
- Memory
- AI automation
- Safety considerations

## 👩‍💻 Author

Divya Banuka