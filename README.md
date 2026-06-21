# 📚 PeakPath – AI Powered Study Planner & Productivity Dashboard

PeakPath is a full-stack AI-driven study planner built with Flask, SQLite, JavaScript and FullCalendar, packed with productivity features like:
- **✅ Smart Task Scheduling** – Automatically organizes your tasks based on deadlines, priorities, and workload for optimal study flow.
- **📅 Real-Time Calendar Syncing** – Seamlessly reflects your schedule changes using FullCalendar with instant visual updates.
- **🔔 Progress Analytics** – Tracks your task completion and study habits to provide insights into your productivity trends.
- **⏱️ Pomodoro Timer** – Integrated focus timer using the Pomodoro technique to boost concentration and manage breaks effectively.
- **🤖 StudyBot (powered by LLaMA/Groq)** – An AI assistant that helps answer study-related questions and generates summaries or suggestions.
- **🧠 Key Points Journaling** – Allows you to log important notes, concepts, or reflections while studying for future revision.
- **🎯 Theme-Aware UI** – Adapts the interface to light or dark themes for better usability and visual comfort across devices.


# 🛠️ Tech Stack
- **Frontend:**
  - HTML, CSS, JavaScript  
  - Custom JS for interactive UI and Pomodoro functionality
- **Backend:**
  - Flask (Python) – lightweight API for managing tasks, sessions, and bot integration
  - SQLite – lightweight, local database for task storage and journaling
  - LLaMA/Groq API – powering the AI assistant (StudyBot)

# 📈 Potential Use Cases
- 🎓 Students preparing for competitive exams (UPSC, GATE, GRE, Cracking Placements)
- 🧑‍💻 Developers managing learning and project timelines     
- 📖 Researchers or readers tracking literature study
- 🧘 Productivity-minded individuals organizing daily goals

  ## 🚀 How to Run
  
  **1. Clone the repository**
  ```bash
  git clone https://github.com/34anjani/PeakPath.git
  cd PeakPath
  
  2. Create a virtual environment
  
  python -m venv venv
  source venv/bin/activate        # On Mac/Linux
  venv\Scripts\activate           # On Windows
  
  3. Install dependencies
  
  pip install -r requirements.txt
  
  4. Set up the Groq API key
  
  export GROQ_API_KEY=your_api_key_here        # On Mac/Linux
  set GROQ_API_KEY=your_api_key_here           # On Windows
  
  │ Get your free API key from Groq Console (https://console.groq.com/)
  
  5. Run the application
  
  python app.py
  
  6. Open in browser
  
  http://127.0.0.1:5000
      
