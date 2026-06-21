# 📚 PeakPath – AI Powered Study Planner & Productivity Dashboard
 
## 📌 Overview

**PeakPath** is a full-stack AI powered study planner and productivity dashboard built with Flask and SQLite that helps students organize their academic workflow. Users can create and track tasks with attributes like deadlines, difficulty levels and completion status all displayed on an interactive FullCalendar with real-time visual syncing. The app includes an integrated StudyBot powered by LLaMA via Groq API that answers study related questions and generates summaries. A Key Points journaling system allows users to log important notes and concepts during study sessions for future revision. The built-in Pomodoro timer helps maintain focused work intervals and a CSV export feature enables offline task analysis. This web app also features secure user authentication with password hashing along with a theme aware UI supporting light and dark modes and progress analytics to track productivity trends over time.

---

## 🔑 Key Features
- **✅ Smart Task Scheduling** – Organizes tasks based on deadlines, priorities, and workload for optimal study flow.
- **📅 Real-Time Calendar Syncing** – Seamlessly reflects schedule changes using FullCalendar with instant visual updates.
- **🔔 Progress Analytics** – Tracks task completion and study habits to provide insights into productivity trends.
- **⏱️ Pomodoro Timer** – Integrated focus timer using the Pomodoro technique to boost concentration and manage breaks effectively.
- **🤖 StudyBot (powered by LLaMA/Groq)** – An AI assistant that helps answer study-related questions and generates summaries or suggestions.
- **🧠 Key Points Journaling** – Allows you to log important notes, concepts, or reflections while studying for future revision.
- **🎯 Theme-Aware UI** – Adapts the interface to light or dark themes for better usability and visual comfort across devices.

---
 
## 🛠️ Tech Stack
- **Frontend:**
  - HTML, CSS, JavaScript  
  - Custom JS for interactive UI and Pomodoro functionality
- **Backend:**
  - Flask (Python) – lightweight API for managing tasks, sessions, and bot integration
  - SQLite – lightweight, local database for task storage and journaling
  - LLaMA/Groq API – powering the AI assistant (StudyBot)

---

## 📈 Potential Use Cases
- 🎓 Students preparing for competitive exams (UPSC, GATE, GRE, Cracking Placements)
- 🧑‍💻 Developers managing learning and project timelines     
- 📖 Researchers or readers tracking literature study
- 🧘 Productivity-minded individuals organizing daily goals

---

## 🚀 How to Run
  
  1. Clone the repository
     ```bash
     git clone https://github.com/34anjani/PeakPath.git
     cd PeakPath
     ```
  
  2. Create a virtual environment
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
  
  3. Install dependencies
     ```bash
     pip install -r requirements.txt
     ```
  
  4. Set up the Groq API key
     ```bash
     set GROQ_API_KEY=your_api_key_here
     ```
     > Get your free API key from Groq Console (https://console.groq.com/)
  
  5. Run the application
     ```bash
     python app.py
     ```
  
  6. Open in browser
     - http://127.0.0.1:5000

 ---
     
## 🧠 AI StudyBot Setup
  The StudyBot uses Groq API + LLaMA-3 by default. You can customize the model in `app.py`:
   ```python
  "model": "meta-llama/llama-4-scout-17b-16e-instruct"

  ```
