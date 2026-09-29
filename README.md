# 🎓 EduGenie — Google Gemini Powered Learning Assistant

EduGenie is a web-based AI learning assistant that helps students learn more effectively through instant doubt solving and AI-generated quizzes, using Google Gemini API.

---

## ✨ Features

- 🤖 **Ask a Question** — Get instant AI-powered answers to any academic question
- 📝 **Generate Quiz** — Create 5-question multiple-choice quizzes on any topic
- 🧠 **Smart Learning** — Powered by Google Gemini API
- 💡 **Easy to Use** — Clean and simple user interface
- 🎯 **Student Friendly** — Helps clear doubts instantly
- 🔐 **Secure** — API keys stored in environment variables

---

## 🛠️ Tech Stack

- 🐍 **Python** (Flask)
- 🤖 **Google Gemini API** (gemini-3.8-flash)
- 🎨 **HTML / CSS / JavaScript**
- 🔐 **python-dotenv** for environment variables

---

## 🚀 How to Run

1️⃣ Clone this repository
```bash
git clone https://github.com/sandhiya-source/EduGenie.git
cd EduGenie

2️⃣ Create a virtual environment
bash
python -m venv .venv
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # Mac/Linux

3️⃣ Install dependencies
bash
pip install -r Phase-5-Development/requirements.txt

4️⃣ Setup API Key
Create a .env file in the root folder with:

text
GEMINI_API_KEY=your_key_here

5️⃣ Run the app
bash
cd Phase-5-Development
python app.py

6️⃣ Open in browser
text
http://127.0.0.1:5000


📁 Project Structure

EduGenie/
├── Phase-1-Brainstorming/        # 🧠 Ideation
├── Phase-2-Requirement-Analysis/ # 📋 Requirements
├── Phase-3-Project-Design/       # 🎨 System Design
├── Phase-4-Project-Planning/     # 📅 Timeline
├── Phase-5-Development/          # 💻 Main Code
│   ├── app.py
│   ├── requirements.txt
│   ├── static/
│   │   ├── style.css
│   │   └── script.js
│   └── templates/
│       └── index.html
├── Phase-6-Testing/              # 🧪 Test Cases
├── Phase-7-Documentation/        # 📖 Documentation
└── Phase-8-Demonstration/        # 🎬 Demo

🎯 How It Works
📝 User enters a question or topic

🔄 Flask backend sends the request to Google Gemini API

🤖 Gemini AI generates a response

💬 Response is displayed on the frontend

📌 Project Phases
Phase	Description

Phase 1 	🧠 Brainstorming & Ideation
Phase 2	 📋 Requirement Analysis
Phase 3	 🎨 Project Design
Phase 4	 📅 Project Planning
Phase 5	 💻 Development
Phase 6	 🧪 Testing
Phase 7	 📖 Documentation
Phase 8	 🎬 Demonstration


📜 License
This project is developed as part of an academic submission.



